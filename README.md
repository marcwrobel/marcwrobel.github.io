Sources du site Web [www.marcwrobel.fr](http://www.marcwrobel.fr/).


## Caractéristiques
Le site Web [www.marcwrobel.fr](http://www.marcwrobel.fr/) utilise le générateur de site statique
[Jekyll](https://jekyllrb.com) et est hébergé sur [GitHub Pages](https://pages.github.com/).

Les outils suivants sont ou ont aussi été utilisés :
* [Bootstrap](https://getbootstrap.com/),
* [Font Awesome](https://fontawesome.com/),
* [npm](https://www.npmjs.com/),
* [webpack](https://webpack.js.org/),
* [IntelliJ IDEA](https://www.jetbrains.com/idea/),
* [favicon.io](https://favicon.io/favicon-generator/?t=MW&ff=Geo&fs=70&fc=%23FFFFFF&b=circle&bc=%23000),
* [Google Analytics](https://analytics.google.com),
* [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fwww.marcwrobel.fr).


## Pré-requis
Ce site utilise le générateur de site statique [Jekyll](https://jekyllrb.com). Pour l'installer vous
pouvez vous référer à [la documentation officielle](https://jekyllrb.com/docs/installation/).

Ce site utilise aussi [npm](https://www.npmjs.com/) pour gérer ses dépendances. Une manière pratique
pour installer npm est d'utiliser [Node Version Manager](https://github.com/nvm-sh/nvm).

Quand tout est installé, exécutez la commande suivante pour installer toutes les dépendances du
projet :
```shell script
npm run install
```


## Mise à jour du site
Lancez tout d'abord le serveur local :
```shell script
npm run jekyll serve
```

Apportez ensuite vos modifications et pré-visualisez les au fur et à mesure [dans votre
navigateur](http://localhost:4000/).

Commitez enfin vos modifications sur la branche `master`. Tout ce qui est commité sur cette branche
est automatiquement publié sur [www.marcwrobel.fr](http://www.marcwrobel.fr/).


## Mise à jour des dépendances
Lancez la commande suivante
```shell script
npm run update
```

Vérifiez que le site fonctionne toujours comme attendu :
```shell script
npm run jekyll serve
```

Commitez enfin vos modifications sur la branche `master`. Tout ce qui est commité sur cette branche
est automatiquement publié sur [www.marcwrobel.fr](http://www.marcwrobel.fr/).


## License
Le contenu de ce site Web est, sauf indication contraire, sous licence [Creative Commons
Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE).
