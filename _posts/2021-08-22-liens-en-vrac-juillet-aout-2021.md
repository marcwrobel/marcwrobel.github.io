---
layout: post
title: Liens en vrac — Juillet / Août 2021
category: liens
seo:
  date_modified: 2022-11-15
---

Nouvelles, articles, podcasts, vidéos et découvertes intéressantes des mois de juillet / août 2021.

## Nouvelles

- [Debian 11 "bullseye" has been released!](https://bits.debian.org/2021/08/bullseye-released.html)
  — comme d’habitude tout a été mis à jour, notamment : le kernel en 5.10, GNOME en 3.38, LibreOffice en 7.0, OpenSSH en
  8.4, PostgreSQL en 13... Plus d’information dans
  les [notes de version](https://www.debian.org/releases/bullseye/releasenotes).
- [Bootstrap 5.1.0](https://blog.getbootstrap.com/2021/08/04/bootstrap-5-1-0/)
  — sympa ce nouveau petit composant `placeholders`.
- [Firewalld 1.0 Released With Big Improvements](https://www.phoronix.com/scan.php?page=news_item&px=Firewalld-1.0)
  — après plus de 10 ans !
- [Apache Maven 3.8.2 released](https://blogs.apache.org/maven/entry/apache-maven-3-8-2)
  — principalement du correctif.
- [OpenZFS 2.1 Released With dRAID, Compatibility Property, Better Performance](https://www.phoronix.com/scan.php?page=news_item&px=OpenZFS-2.1)
  — tout est dans le titre.
- [Lancement de la toute première solution Limitless XDR gratuite et ouverte du secteur avec Elastic 7.14.0](https://www.elastic.co/fr/blog/whats-new-elastic-7-14-0)
  — [Elastic Agent](https://www.elastic.co/fr/blog/elastic-agent-and-fleet-make-it-easier-to-integrate-your-systems-with-elastic)
  passe en disponibilité générale, espérons que ça facilite la collecte des données.
- [Good-bye AdoptOpenJDK. Hello Adoptium!](https://blog.adoptopenjdk.net/2021/08/goodbye-adoptopenjdk-hello-adoptium/)
  — si j’ai bien tout compris le projet _AdoptOpenJDK_ devient _Eclipse Adoptium_ et le build _AdoptOpenJDK_ devient
  _Temurin_.
- [JVM Ecosystem Report 2021](https://snyk.io/jvm-ecosystem-report-2021/)
  — pas forcément très représentatif (le public interrogé est relativement restreint) mais ça vaut quand même le coup
  d’oeil.
- [Hello, Spring GraphQL](https://spring.io/blog/2021/07/06/hello-spring-graphql)
  — une intégration de [GraphQL Java](https://www.graphql-java.com/) dans Spring.
- [EBICS 3.0 in the home stretch](https://www.ebicsblog.com/2021/08/ebics-30-in-home-stretch.html)
  — EBICS 3.0 se démocratise un peu plus (EBICS 2.5 reste néanmoins supporté par tout le monde).
- [« Service après-vente bonjour ! » : Le futur de la French Tech ?](https://www.dontkillfrenchtech.fr/)
  — tl;dr : _Un groupe de jeunes développeurs et autres travailleurs du logiciel et du cloud s’alarment, dans une
  tribune au
  « [Monde](https://www.lemonde.fr/idees/article/2021/06/27/les-entreprises-francaises-de-la-tech-constituent-un-atout-majeur-dans-la-mise-en-place-d-une-reelle-strategie-de-souverainete-numerique_6085887_3232.html)
  », de l’incapacité des pouvoirs publics à faire confiance aux jeunes entreprises de la tech française et à préférer
  les Gafam._
- [GitHub Copilot - Your AI pair programmer](https://copilot.github.com/)
  — l’initiative semble intéressante, mais difficile de se faire une idée sans pouvoir tester (l’accès est limité et la
  liste d’attente semble interminable).

## Articles, podcasts et vidéos

- [Ripe for the picking: 11 essential Java features to help modernize your code](https://blogs.oracle.com/javamagazine/java-modernization-streams-records-lambdas-sealedclasses)
  — une petite sélection de fonctionnalités apportées dans les versions de Java 8 à 15.
- [On the Evilness of Feature Branching - A Tale of Two Teams](https://thinkinglabs.io/articles/2021/07/14/on-the-evilness-of-feature-branching-a-tale-of-two-teams.html)
  — je suis plutôt [Scaled Trunk-Based Development](https://trunkbaseddevelopment.com/#scaled-trunk-based-development).
- [Securing an Angular app which uses multiple identity providers](https://damienbod.com/2021/08/02/securing-an-angular-app-which-uses-multiple-identity-providers/)
  — ça peut servir à l’occasion.
- [Computing and Caching](https://tapoueh.org/blog/2018/07/computing-and-caching/)
  — je n’avais bizarrement jamais pensé à utiliser une vue matérialisée comme cache.
- [HTML Tips](https://markodenic.com/html-tips/)
  — un joli petit panaché de d’astuces en HTML !
- [PostgreSQL Security: Things to avoid in real life](https://www.cybertec-postgresql.com/en/postgresql-security-things-to-avoid-in-real-life/)
  — une petite liste de contrôle qui peut s’avérer pratique.
- [Quentin Adam : Hype Driven Architecture, ou, faire face au code du monde réel](https://www.youtube.com/watch?v=1dTPoBXPDcg)
  — ça vaut le coup d’oeil !

## Découvertes

- [Git alias to delete merged branches](https://dev.to/wojciechko/git-alias-to-delete-merged-branches-3cop)
  — `git branch --merged` c’était déjà bien, mais `git cleanup` c’est encore mieux.
- [Plausible dépasse les 30 000$ de revenu mensuel](https://serveur410.com/plausible-alternative-a-google-analytics-depasse-les-30-000-de-revenu-mensuel/)
  — si vous cherchez une alternative à Google Analytics.
- [Kroki - Creates diagrams from textual descriptions!](https://github.com/yuzutech/kroki)
  — ça pourrait être sympa à utiliser quand PlantUML n’est intégré / intégrable.
- [pkgs.org](https://pkgs.org/)
  — _packages Search for Linux and Unix_, pratique pour savoir rapidement si un paquet sera disponible sur la plupart
  des distributions populaires.

[That’s all folks](https://www.youtube.com/watch?v=dPThzBElZ1c "Damon Albarn - The Story of a Cheating Heart"){:target="_blank"} !

<!-- prettier-ignore-start -->
*[EBICS]: Electronic Banking Internet Communication Standard
*[GNOME]: GNU Network Object Model Environment
*[GraphQL]: Graph Query Language
*[HTML]: HyperText Markup Language
*[JDK]: Java Development Kit
*[RAID]: Redundant Array of Independent Disks
*[SQL]: Structured Query Language
*[SSH]: Secure SHell
*[tl;dr]: too long; didn’t read
*[UML]: Unified Modeling Language
*[XDR]: eXtended Detection and Response
*[ZFS]: Z File System
<!-- prettier-ignore-end -->
