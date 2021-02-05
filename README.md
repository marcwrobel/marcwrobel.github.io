Sources du site Web [www.marcwrobel.fr](http://www.marcwrobel.fr/).


## Caractéristiques
Le site Web [www.marcwrobel.fr](http://www.marcwrobel.fr/) utilise le générateur de site statique
[Jekyll](https://jekyllrb.com) et est hébergé sur [GitHub Pages](https://pages.github.com/).

[www.marcwrobel.fr](http://www.marcwrobel.fr/) utilise aussi :
* [Bootstrap](https://getbootstrap.com/) pour la mise en forme,
* [Font Awesome 4](https://fontawesome.com/v4.7.0/icons/) pour les icônes (la version 5 étant
  beaucoup moins pratique à utiliser dans le cadre de ce site web, on reste sur la 4),
* [Simple-Jekyll-Search](https://github.com/christian-fei/Simple-Jekyll-Search) pour la
  fonctionnalité de recherche,
* [IntelliJ IDEA](https://www.jetbrains.com/idea/) pour le développement du site et la rédaction du
  contenu,
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
bin/serve
```

Apportez ensuite vos modifications et pré-visualisez les au fur et à mesure [dans votre
navigateur](http://localhost:4000/).

Commitez enfin vos modifications sur la branche `master`. Tout ce qui est commité sur cette branche
est automatiquement publié sur [www.marcwrobel.fr](http://www.marcwrobel.fr/).


## Mise à jour de Jekyll et de ses dépendances
Pour mettre à jour Jekyll et ses dépendances sur [les même versions que celle utilisées sur GitHub
Pages](https://pages.github.com/versions/), exécuter :
```shell script
bin/update-dependencies
```


### Mise à jour de Bootstrap, Font Awesome et Simple-Jekyll-Search

1. Allez sur [jsDelivr](https://www.jsdelivr.com/) à l'aide de l'un de ces liens :
  - [bootstrap.min.css](https://www.jsdelivr.com/package/npm/bootstrap?path=dist%2Fcss),
  - [font-awesome.css](https://www.jsdelivr.com/package/npm/font-awesome?path=css),
  - [simple-jekyll-search.min.js](https://www.jsdelivr.com/package/npm/simple-jekyll-search))
2. Sélectionner la version souhaitée.
3. Ajoutez le fichier à mettre à jour à votre collection.
4. Cliquer sur le bouton _SHOW & CONFIGURE ALL LINKS_.
5. Cliquer sur le bouton _SRI_ (_Enable Subresource Integrity check for increased security_).
6. Reportez les liens (`href`) et les hash (`integrity`) indiqués sur jsDelivr dans le fichier [_config.yml](/_config.yml) (propriété `dependencies`).

Contrairement à Jekyll il vous faudra malheureusement suivre les mises à jour vous-même (via par exemple le [blog de bootstrap](https://blog.getbootstrap.com/)
ou [le dépôt du projet Simple-Jekyll-Search sur GitHub](https://github.com/christian-fei/Simple-Jekyll-Search)).


### Suivi des mises à jour

Que ce soit en grande partie automatique (pour Jekyll, avec [Bundler](https://bundler.io/)) ou manuel (pour Bootstrap ou simple-jekyll-search) pour mettre à
jour les dépendances utilisées par ce site il faut déjà que vous soyez au courant que ces mises à jour existent. Pour cela plusieurs moyens :

- suivre les blogs des projets ([Jekyll](https://jekyllrb.com/news/), [Bootstrap](https://blog.getbootstrap.com/), [Font Awesome](https://fontawesome.com/)),
- suivre les pages [GitHub](https://github.com) des projets ([Jekyll](https://github.com/jekyll/jekyll), [Bootstrap](https://github.com/twbs/bootstrap),
  [Font Awesome](https://github.com/FortAwesome/Font-Awesome), [simple-jekyll-search](https://github.com/christian-fei/Simple-Jekyll-Search)),
- ou, plus simplement, utiliser [librairies.io](https://libraries.io/) ([Jekyll](https://libraries.io/rubygems/jekyll), [Bootstrap](https://libraries.io/npm/bootstrap),
  [Font Awesome](https://libraries.io/npm/font-awesome), [simple-jekyll-search](https://libraries.io/npm/simple-jekyll-search)).

## Documentation utile
* https://jekyllrb.com/docs/
* https://getbootstrap.com/docs/
* https://fontawesome.com/v4.7.0/icons/
* https://fontawesome.com/v4.7.0/accessibility/

## License
Le contenu de ce site Web est, sauf indication contraire, sous licence [Creative Commons
Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE).
