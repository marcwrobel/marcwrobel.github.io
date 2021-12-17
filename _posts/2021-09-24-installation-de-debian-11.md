---
layout: post
title: Installation de Debian 11
category: administration
---

Quelques notes sur la manière dont j’installe généralement
une [Debian 11 "bullseye"](https://www.debian.org/News/2021/20210814.html).

## Lancement de l’installation

Tout d’abord il vous faudra télécharger l’image _netinstall_ amd64 de
Debian [sur le site de debian](https://www.debian.org/distrib/netinst). Si nécessaire (carte réseau/wifi non supportée
par exemple) on pourra plutôt télécharger une
[unofficial non-free images including firmware packages](https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/)
.

Ensuite pour créer une clé USB bootable :

```bash
sudo dd if=/path/to/debian.iso of=/dev/sdx bs=4M status=progress oflag=sync
```

Il ne restera plus qu’à booter sur la clé USB, choisir l’une des options _expert install_ (dans _Advanced options_),
graphique ou non, et suivre toutes les étapes dans l’ordre.

## Paramètres linguistiques

Je trouve qu’il est plus confortable d’utiliser Debian en anglais. Pour cela :

* langue : Anglais
* locale : en_US.UTF-8
* pays : France
* clavier : Français
* fuseau horaire : Europe/Paris

## Réseau

La plupart du temps, utilisez DHCP pour configurer cette partie. Si vous avez absolument besoin de configurer une adresse
IP statique choisissez cette option et laissez vous guider.

Pour le hostname utilisez votre imagination. Si vous possédez un nom de domaine vous pouvez l’utiliser en tant que
domain name du système.

## Comptes utilisateurs

Créer un compte utilisateur _normal_ pour administrer le système et désactiver le login en tant que
`root`. Pour exécuter des commandes en tant que `root` on utilisera [`sudo`](https://wikipedia.org/wiki/Sudo).

## Partitionnement

Pour des questions de sécurité et de confidentialité le disque doit être intégralement chiffré. Pour cela utiliser
l’option _Guided - use entire disk and set up encrypted LVM_.

Une fois cela fait, adaptez le schéma de partitionnement. Vous pouvez vous inspirer du schéma suivant :

| Volume logique | Taille initiale | Type de partition | Point de montage    |
|----------------|-----------------|-------------------|---------------------|
| root           | 25 Go           | ext4              | /                   |
| home           | 50 Go           | ext4              | /home               |
| var            | 10 Go           | ext4              | /var                |
| opt            | 10 Go           | ext4              | /opt                |
| docker         | 10 Go           | ext4              | /var/lib/docker     |
| srv            | 1 Go            | ext4              | /srv                |
| tmp            | 5 Go            | ext4              | /tmp                |

Les options de montage par défaut suffisent, car elles contiennent l’option `relatime`
[depuis longtemps déjà](https://unix.stackexchange.com/questions/17844/when-was-relatime-made-the-default).

Il n’est pas nécessaire de trop réfléchir aux tailles des partitions : il sera toujours possible, par la suite, de les
augmenter en utilisant la commande qui suit :

```bash
sudo lvextend -L+<size>G -r /dev/vg/<name>
```

À noter qu’il n’est pas utile de créer une partition swap. En fonction de la quantité de mémoire disponible sur le
système et [de votre utilisation](https://wiki.debian.org/Swap) vous pourrez éventuellement créer un fichier de swap
plus tard de la manière suivante :

```bash
sudo fallocate -l 1G /swap
sudo chmod 600 /swap
sudo mkswap /swap
sudo swapon /swap
echo '/swap none swap sw 0 0' | sudo tee -a /etc/fstab
```

## Logiciels

* utilisation d’un miroir sur le réseau : oui (HTTP / France / deb.debian.org)
* utilisation de logiciels non-free : oui
* popularity-contest : oui
* services : security updates, release updates, backported software
* logiciels : Gnome, SSH server, standard system utilities

*[DHCP]: Dynamic Host Control Protocol
*[HTTP]: Hypertext Transfer Protocol
*[IP]: Internet Protocol
*[LVM]: Logical Volume Manager
*[SSH]: Secure SHell
