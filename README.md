Sources du site Web [www.marcwrobel.fr](http://www.marcwrobel.fr/).

## Caractéristiques

Le site Web [www.marcwrobel.fr](http://www.marcwrobel.fr/) utilise le générateur de site statique
[Jekyll](https://jekyllrb.com) et est hébergé sur [GitHub Pages](https://pages.github.com/).

[www.marcwrobel.fr](http://www.marcwrobel.fr/) utilise aussi :

- [Bootstrap](https://getbootstrap.com/) pour la mise en forme,
- [Font Awesome 4](https://fontawesome.com/v4.7.0/icons/) pour les icônes (la version 5 étant
  beaucoup moins pratique à utiliser dans le cadre de ce site web, on reste sur la 4),
- [Simple-Jekyll-Search](https://github.com/christian-fei/Simple-Jekyll-Search) pour la
  fonctionnalité de recherche,
- [IntelliJ IDEA](https://www.jetbrains.com/idea/) pour le développement du site et la rédaction du
  contenu,
- [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fwww.marcwrobel.fr),
  [GiftOfSpeed](https://www.giftofspeed.com/) et
  [Accessibility Checker](https://www.accessibilitychecker.org/audit/?website=https%3A%2F%2Fwww.marcwrobel.fr%2F&flag=eu)
  pour l’analyse du site et la recommandation de bonnes pratiques.

## Prérequis

Ce site utilise le générateur de site statique [Jekyll](https://jekyllrb.com). Pour l’installer vous
pouvez vous référer à [la documentation officielle](https://jekyllrb.com/docs/installation/).

## Mise à jour du site

Lancez tout d’abord le serveur local :

```shell script
bin/serve
```

Apportez ensuite vos modifications et pré-visualisez les au fur et à mesure [dans votre
navigateur](http://localhost:4000/).

Commitez enfin vos modifications sur la branche `master`. Tout ce qui est commité sur cette branche
est automatiquement publié sur [www.marcwrobel.fr](http://www.marcwrobel.fr/).

## Mise à jour des dépendances

La mise à jour de l'ensemble des dépendances du site passe par le script `update-dependencies`. Pour l'utiliser,
exécuter :

```shell script
./bin/update-dependencies
```

Une fois cela fait il ne reste plus qu’à tester que le site fonctionne bien puis commiter le tout, généralement en
séparant le type de mise à jour (Jekyll, Bootstrap...).

Quelques petites choses doivent de plus être connus en fonction du type de dépendances.

### Paquets Ruby

Les dépendances Ruby sont décrites dans le fichier [Gemfile](/Gemfile). Le script `update-dependencies` met à jour les
paquets en fonction de ce fichier.

La plupart des versions utilisées [dépendent de GitHub Pages](https://pages.github.com/versions/).

### CSS et JS

À cause de [problématiques liées à la
RGPD](https://www.jsdelivr.com/blog/how-the-german-courts-ruling-on-google-fonts-affects-jsdelivr-and-why-it-is-safe-to-use/)
les dépendances CSS et JS sont hébergées [dans le répertoire `assets`](/assets) et non sur un CDN. Le script
`update-dependencies` met à jour ces dépendances en fonction [d'informations renseignées dans le script
lui-même](/bin/update-dependencies).

Généralement toutes les mises à jour se font automatiquement, à l'exception des mises à jour pouvant nuire au bon
fonctionnement du site (Bootstrap). Ces mises à jour doivent être appliquées à la main en modifiant
[le script `update-dependencies`](/bin/update-dependencies).

### Ruby

La version de Ruby utilisée en production est [celle de GitHub Pages](https://pages.github.com/versions/). En
développement on utilisera la [version maintenue](https://www.ruby-lang.org/en/downloads/branches/) la plus proche.

### Suivi des mises à jour

Que ce soit en grande partie automatique (pour Jekyll, avec [Bundler](https://bundler.io/)) ou manuel (pour Bootstrap ou simple-jekyll-search) pour mettre à
jour les dépendances utilisées par ce site il faut déjà que vous soyez au courant que ces mises à jour existent. Pour cela plusieurs moyens :

- suivre les blogs des projets ([Jekyll](https://jekyllrb.com/news/), [Bootstrap](https://blog.getbootstrap.com/), [Font Awesome](https://fontawesome.com/)),
- suivre les pages [GitHub](https://github.com) des projets ([Jekyll](https://github.com/jekyll/jekyll), [Bootstrap](https://github.com/twbs/bootstrap),
  [Font Awesome](https://github.com/FortAwesome/Font-Awesome), [simple-jekyll-search](https://github.com/christian-fei/Simple-Jekyll-Search)),
- ou, plus simplement, utiliser [librairies.io](https://libraries.io/) ([Jekyll](https://libraries.io/rubygems/jekyll), [Bootstrap](https://libraries.io/npm/bootstrap),
  [Font Awesome](https://libraries.io/npm/font-awesome), [simple-jekyll-search](https://libraries.io/npm/simple-jekyll-search)).

## Documentation utile

- https://jekyllrb.com/docs/
- https://getbootstrap.com/docs/
- https://fontawesome.com/v4.7.0/icons/
- https://fontawesome.com/v4.7.0/accessibility/

## License

Le contenu de ce site Web est, sauf indication contraire, sous licence [Creative Commons
Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE).
