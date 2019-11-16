Sources du site Web [www.marcwrobel.fr](http://www.marcwrobel.fr/).


## Pré-requis
Ce site utilise le générateur de site statique [Jekyll](https://jekyllrb.com). Il vous faut donc au
préalable l'[installer](https://jekyllrb.com/docs/installation/).

Pour cela installez tout d'abord un environnement de développement Ruby. Par exemple sur Debian :
```shell script
sudo apt install ruby-full build-essential zlib1g-dev
``` 

Ajoutez ensuite ces quelques lignes dans votre `.bashrc` afin d'installer les `gem` Ruby dans votre
répertoire personnel :
```shell script
# Install Ruby Gems to ~/gems
export GEM_HOME="$HOME/gems"
export PATH="$HOME/gems/bin:$PATH"
``` 

Vous pouvez enfin installer [Jekyll](https://jekyllrb.com) :
```shell script
gem install jekyll bundler
```


## Modifier le site
Démarrez tout d'abord le serveur local Jekyll :
```shell script
bundle exec jekyll serve
```

Apportez ensuite vos modifications et pré-visualisez les [dans votre
navigateur](http://localhost:4000/). 

Commitez enfin vos modifications sur la branche `master`. Tout ce qui est commité sur cette branche
est automatiquement publié sur [www.marcwrobel.fr](http://www.marcwrobel.fr/). Ce site est en effet
hébergé sur [GitHub Pages](https://pages.github.com/).


## License
Le contenu de ce site Web est, sauf indication contraire, sous licence [Creative Commons
Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE).
