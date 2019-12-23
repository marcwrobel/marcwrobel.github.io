---
layout: post
title: Installation de Debian
category: administration
tags: administration linux debian
---

Quelques notes sur l'installation d'une Debian 10 "Buster" (sur un ordinateur personnel).

## Lancement de l'installation
Tout d'abord télécharger l'image _netinst_ amd64 de Debian [sur le site de debian](https://www.debian.org/distrib/netinst).
Si nécessaire (carte réseau/wifi non supportée par exemple) on pourra plutôt télécharger une
[unofficial non-free images including firmware packages](https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/).

Ensuite pour créer la clé USB bootable :
```bash
sudo dd if=/path/to/debian.iso of=/dev/sdx bs=4M status=progress oflag=sync
```

Il ne restera plus qu'à booter sur la clé, choisir l'option _expert install_ et suivre toutes les
étapes dans l'ordre. Si aucune précision n'est fournie de le paragraphe qui suit prendre l'option
par défaut.


## Paramètres de configuration
Utiliser la configuration suivante quand c'est nécessaire :
* Language = English
* Country = France (on peut choisir cette option dans other / Europe)
* Timezone = Europe/Paris
* Locale = en_US.UTF-8
* Keyboard keymap = French
* Hostname : xxx
* DomainName : marcwrobel.fr
* username : mwrobel
* Create a normal user account : YES
* Use network mirror : YES / http / France / ftp.fr.debian.org
* Use non-free software : YES
* Participate in the package usage survey : YES
* packages : system, desktop environment


## Partitionnement
Pour des questions de sécurité et de confidentialité le disque doit être intégralement chiffré.
Pour cela utiliser l'option _Guided - use entire disk and set up encrypted LVM_. Pour info le fait
de retailler une partition pour qu'elle n'occupe pas tout le disque ne pose pas de problème.

Une fois cela fait utilisez un schéma de partitionnement similaire à :

| Volume logique | Taille initiale                             | Type de partition | Point de montage    |
|----------------|---------------------------------------------|-------------------|---------------------|
| root           | 20 Go                                       | ext4              | /                   |
| home           | 50 Go                                       | ext4              | /home               |
| var            | 10 Go                                       | ext4              | /var                |
| opt            | 10 Go                                       | ext4              | /opt                |
| docker         | 10 Go                                       | ext4              | /var/lib/docker     |
| postgresql     | 10 Go                                       | ext4              | /var/lib/postgresql |
| tmp            | 2 Go                                        | ext4              | /tmp                |

Quelques informations complémentaires :
* Pour la swap utiliser un fichier plutôt qu'une partition. Pour plus d'informations, consulter [la
  dédiée sur le Wiki Debian](https://wiki.debian.org/Swap).
* Les options de montage par défaut suffisent car elles contiennent l'option `relatime` - cf. [cette
  question sur Stack Exchange](https://unix.stackexchange.com/questions/17844/when-was-relatime-made-the-default).
* L'installation de grub ne doit pas se faire sur le [MBR](https://wikipedia.org/wiki/Master_boot_record).
  Si le MBR venait à être vidé sans aucun avertissement (au hasard, suite à une installation de
  Windows...), cela permettra de récupérer un Linux bootable en réactivant la bonne partition.
