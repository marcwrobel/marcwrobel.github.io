---
layout: post
title: Sortie de la collection de rôles Ansible marcwrobel.assertions 1.0.0
category: développement
---

La version 1.0.0 de la collection de rôles
Ansible [marcwrobel.assertions](https://galaxy.ansible.com/marcwrobel/assertions) est sortie.

Cette collection de rôles vise à combler ce qui m’a paru être un manque dans l’écosystème Ansible : une collection
d’assertions simples à utiliser et réutilisables. L’utilisation de la
collection [marcwrobel.assertions](https://github.com/marcwrobel/ansible-collection-assertions) permet, par rapport à
l’utilisation directe des briques fournies par
Ansible ([modules](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/assert_module.html),
[filtres](https://docs.ansible.com/ansible/latest/user_guide/playbooks_filters.html)
, [tests](https://docs.ansible.com/ansible/latest/user_guide/playbooks_tests.html)…) :

- de simplifier l’écriture d’assertion,
- d’obtenir des messages d’erreur plus claires,
- de réduire, la plupart du temps, la quantité de code à écrire.

Cette collection vise notamment à être utilisée lors de l’écriture de tests [Molecule](https://molecule.readthedocs.io)
avec le [_verifier_ Ansible](https://molecule.readthedocs.io/en/latest/configuration.html#verifier)
(activé par défaut depuis la version 3.0.0). Elle pourra être aussi utile pour bloquer l’exécution de playbooks quand
certaines conditions ne sont pas remplies
(version d’Ansible, version de la distribution des [_managed
nodes_](https://docs.ansible.com/ansible/latest/network/getting_started/basic_concepts.html#managed-nodes)…).

Pour cette première version les assertions suivantes ont été implémentés :

- [`marcwrobel.assertions.assert_that_ansible`](https://github.com/marcwrobel/ansible-collection-assertions/blob/main/ansible_collections/marcwrobel/assertions/roles/assert_that_ansible/README.md) :
  assertions sur Ansible lui-même (`has_min_version`, `has_max_version`),
- [`marcwrobel.assertions.assert_that_distribution`](https://github.com/marcwrobel/ansible-collection-assertions/blob/main/ansible_collections/marcwrobel/assertions/roles/assert_that_distribution/README.md) :
  assertions sur les distributions (`is_in`),
- [`marcwrobel.assertions.assert_that_file`](https://github.com/marcwrobel/ansible-collection-assertions/blob/main/ansible_collections/marcwrobel/assertions/roles/assert_that_file/README.md) :
  assertions sur les fichiers (`has_content_matching`),
- [`marcwrobel.assertions.assert_that_path`](https://github.com/marcwrobel/ansible-collection-assertions/blob/main/ansible_collections/marcwrobel/assertions/roles/assert_that_path/README.md) :
  assertions sur les chemins d’un système de fichiers (`exists`, `has_type`, `has_mode`, `has_owner`, `has_group`),
- [`marcwrobel.assertions.assert_that_service`](https://github.com/marcwrobel/ansible-collection-assertions/blob/main/ansible_collections/marcwrobel/assertions/roles/assert_that_service/README.md) :
  assertions sur les services (`exists`, `has_state`, `has_status`).

Pour utiliser cette collections il suffit de l’installer en sur votre poste via la commande suivante :

```
ansible-galaxy collection install marcwrobel.assertions
```

Il ne restera plus qu’à l’utiliser dans vos playbooks ou dans vos scénarios Molecule. Quelques exemples :

```yaml
- name: 'Assert that Ansible version is 2.8.x or 2.9.x'
  include_role:
    name: 'marcwrobel.assertions.assert_that_ansible'
  vars:
    has_min_version: '2.8'
    has_max_version: '2.10'

- name: 'Assert that the distribution is supported'
  include_role:
    name: 'marcwrobel.assertions.assert_that_distribution'
  vars:
    is_in: [ 'Debian', 'RedHat 8', 'Ubuntu 20.04' ]

- name: 'Assert that /tmp/test is managed by Ansible'
  include_role:
    name: 'marcwrobel.assertions.assert_that_file'
  vars:
    path: '/path/to/file'
    has_content_matching: '^# Ansible managed'

- name: 'Assert that /path/to/file exists, is a file, have mode 0640 and belongs to root:root'
  include_role:
    name: 'marcwrobel.assertions.assert_that_path'
  vars:
    path: '/path/to/file'
    has_type: 'file'
    has_mode: '0640'
    has_owner: 'root'
    has_group: 'root'

- name: 'Assert that firewalld.service exists, is running and is enabled'
  include_role:
    name: 'marcwrobel.assertions.assert_that_service'
  vars:
    name: 'firewalld.service'
    has_state: 'running'
    has_status: 'enabled'
```

Pour plus d’informations référez-vous à la documentation de la collection disponible
sur [le dépôt GitHub marcwrobel/ansible-collection-assertions](https://github.com/marcwrobel/ansible-collection-assertions)
.
