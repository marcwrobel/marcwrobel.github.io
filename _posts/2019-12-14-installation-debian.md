---
layout: post
title: Installation de Debian 10
category: administration
---

Quelques notes sur l’installation d’une [Debian 10 "Buster"](https://www.debian.org/News/2019/20190706).

## Lancement de l’installation

Tout d’abord télécharger l’image _netinstall_ amd64 de
Debian [sur le site de debian](https://www.debian.org/distrib/netinst). Si nécessaire (carte réseau/wifi non supportée
par exemple) on pourra plutôt télécharger une
[unofficial non-free images including firmware packages](https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/)
.

Ensuite pour créer la clé USB bootable :

```bash
sudo dd if=/path/to/debian.iso of=/dev/sdx bs=4M status=progress oflag=sync
```

Il ne restera plus qu’à booter sur la clé USB, choisir l’une des options _expert install_ (dans
_Advanced options_) et suivre toutes les étapes dans l’ordre.

## Paramètres linguistiques

Je trouve qu’il est plus confortable d’utiliser Debian en anglais. Pour cela :

- langue : Anglais
- locale : en_US.UTF-8
- pays : France
- clavier : Français
- fuseau horaire : Europe/Paris

## Comptes utilisateurs

Créer un compte utilisateur _normal_ pour administrer le système et désactiver le login en tant que
`root`. Pour exécuter des commandes en tant que `root` on utilisera [`sudo`](https://wikipedia.org/wiki/Sudo).

## Partitionnement

Pour des questions de sécurité et de confidentialité le disque doit être intégralement chiffré. Pour cela utiliser
l’option _Guided - use entire disk and set up encrypted LVM_.

Une fois cela fait utilisez un schéma de partitionnement similaire à :

| Volume logique | Taille initiale | Type de partition | Point de montage    |
|----------------|-----------------|-------------------|---------------------|
| root           | 20 Go           | ext4              | /                   |
| home           | 50 Go           | ext4              | /home               |
| var            | 10 Go           | ext4              | /var                |
| opt            | 10 Go           | ext4              | /opt                |
| docker         | 10 Go           | ext4              | /var/lib/docker     |
| postgresql     | 10 Go           | ext4              | /var/lib/postgresql |
| srv            | 1 Go            | ext4              | /srv                |
| tmp            | 5 Go            | ext4              | /tmp                |

Les options de montage par défaut suffisent car elles contiennent
l’option `relatime` [depuis longtemps déjà](https://unix.stackexchange.com/questions/17844/when-was-relatime-made-the-default).

Il sera toujours possible, par la suite, d’augmenter la taille de ces partitions en utilisant la commande qui suit :

```bash
sudo lvextend -L+<size>G -r /dev/vg/<name>
```

## Logiciels installés

- utilisation d’un miroir sur le réseau : oui (http / France / deb.debian.org)
- utilisation de logiciels non-free : oui
- popularity-contest : oui
- logiciels : Gnome, print server, SSH server, standard system utilities

## Création de la swap

Pour plus de souplesse utiliser un fichier plutôt qu’une partition pour la swap. Pour cela, après l’installation :

```bash
sudo fallocate -l 1G /swap
sudo chmod 600 /swap
sudo mkswap /swap
sudo swapon /swap
echo '/swap none swap sw 0 0' | sudo tee -a /etc/fstab
```

Pour plus d’informations, consulter [la page dédiée sur wiki.debian.org](https://wiki.debian.org/Swap).
