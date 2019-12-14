Sources du site Web [www.marcwrobel.fr](http://www.marcwrobel.fr/).


## Caractéristiques
Le site Web [www.marcwrobel.fr](http://www.marcwrobel.fr/) utilise le générateur de site statique
[Jekyll](https://jekyllrb.com) et est hébergé sur [GitHub Pages](https://pages.github.com/).

[www.marcwrobel.fr](http://www.marcwrobel.fr/) utilise aussi :
* [Bootstrap](https://getbootstrap.com/) pour la mise en forme,
* [Font Awesome 4](https://fontawesome.com/v4.7.0/icons/) pour les icônes (la version 5 étant
  beaucoup moins pratique à utiliser dans le cadre de ce site web, on reste sur la 4),
* [IntelliJ IDEA](https://www.jetbrains.com/idea/) pour le développement du site et la rédaction du
  contenu,
* [favicon.io](https://favicon.io/favicon-generator/?t=MW&ff=Geo&fs=70&fc=%23FFFFFF&b=circle&bc=%23000)
  pour la création du [logo](assets/icon-512.png),
* [Google Analytics](https://analytics.google.com) pour l'analyse des audiences,
* [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fwww.marcwrobel.fr) et
  [GiftOfSpeed](https://www.giftofspeed.com/) pour l'analyse du site et la recommandation de bonnes
  pratiques.


## Pré-requis
Ce site utilise le générateur de site statique [Jekyll](https://jekyllrb.com). Pour l'installer vous
pouvez vous référer à [la documentation officielle](https://jekyllrb.com/docs/installation/).


## Mise à jour du site
Lancez tout d'abord le serveur local :
```shell script
bundle exec jekyll serve
```

Apportez ensuite vos modifications et pré-visualisez les au fur et à mesure [dans votre
navigateur](http://localhost:4000/).

Commitez enfin vos modifications sur la branche `master`. Tout ce qui est commité sur cette branche
est automatiquement publié sur [www.marcwrobel.fr](http://www.marcwrobel.fr/).


## Mise à jour de Jekyll et de ses dépendances
Pour mettre à jour Jekyll et ses dépendances sur [les même versions que celle utilisées sur GitHub
Pages](https://pages.github.com/versions/), exécuter :
```shell script
bundle update
```

Il est à noter que des dépendances à Bootstrap et Font Awesome ont été déclarée dans le Gemfile. Ces
dépendances n'ont vocation qu'à nous tenir au courant des mises à jour.


## Mise à jour des librairies tierces (CSS, JS)
Bootstrap et Font Awesome ont été intégrées au code source du site en tant que _partial_ Sass pour
minimiser le nombre de requêtes et faciliter l'utilisation de directives Sass avec Jekyll/Markdown
(comme la directive `@extend` utilisée pour appliquer la mise en forme Bootstrap à l'ensemble des
éléments `table`). Cette intégration ne vient malheureusement pas sans inconvénient, notamment en ce
qui concerne la mise à jour de ces librairies.

Pour mettre à jour Bootstrap télécharger la version _Compiled CSS and JS_ sur [getbootstrap.com](https://getbootstrap.com/)
puis copiez `css/bootstrap.css` dans `_sass/_bootstrap.scss`.

Pour mettre à jour Font Awesome télécharger la librairie sur [fontawesome.com](https://fontawesome.com)
puis copier `css/font-awesome.css` dans `_sass/_font-awesome.scss` et remplacer le répertoire
`fonts` du projet par celui de la librairie.


# Documentation utile
* https://jekyllrb.com/docs/
* https://getbootstrap.com/docs/
* https://fontawesome.com/v4.7.0/icons/
* https://fontawesome.com/v4.7.0/accessibility/

## License
Le contenu de ce site Web est, sauf indication contraire, sous licence [Creative Commons
Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE).
