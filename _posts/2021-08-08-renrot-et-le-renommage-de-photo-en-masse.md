---
layout: post
title: Renrot et le renommage de photos en masse
category: outils
seo:
  date_modified: 2022-11-15
---

[`renrot`](https://puszcza.gnu.org.ua/projects/renrot/) est un utilitaire en ligne de commande très pratique qui permet
de renommer et corriger (sans perte)
l’orientation de photos en masse à partir de leurs informations EXIF. Il
est [disponible sous forme de paquet](https://pkgs.org/download/renrot) CentOS, Debian, Fedora, FreeBSD ou Ubuntu.

Pour utiliser `renrot` pour renommer l’ensemble des photos d’un album rien de plus simple :

```shell
cd /path/to/album
renrot --extension jpg --name-template="vacances-%Y%m%d-%H%M%S"
```

Les photos de l’album seront toutes renommées avec le préfixe `vacances-` et la date à laquelle la photo a été prise au
format `YYYYmmdd-HHMMSS`. Par exemple une photo à l’origine nommée `1.jpg` et prise le 08/08/2021 à 14 h 32 min 27 s
sera renommée en `vacances-20210808-143227.jpg`. De plus si l’orientation de la photo n’est pas correcte elle sera
corrigée au passage.

`renrot` possède bien d’autres fonctionnalités telles que la création de vignettes, la possibilité de ranger les photos
dans des sous-répertoires, la possibilité d’éditer les mots clés de l’image... Si vous souhaitez en savoir plus la
documentation complète de `renrot` est disponible
sur [https://puszcza.gnu.org.ua/software/renrot/manual/renrot.html](https://puszcza.gnu.org.ua/software/renrot/manual/renrot.html)
ou dans la [manpage](http://manpages.ubuntu.com/manpages/artful/man1/renrot.1p.html) qui lui est dédiée.

<!-- prettier-ignore-start -->
*[EXIF]: EXchangeable Image File Format
<!-- prettier-ignore-end -->
