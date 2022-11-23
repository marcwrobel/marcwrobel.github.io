---
layout: post
title: Liens en vrac — Novembre 2022
category: liens
seo:
  date_modified: 2022-12-02
---

Nouvelles, articles, podcasts, vidéos et découvertes intéressantes du mois de novembre 2022.

## Nouvelles

- [PostgreSQL JDBC 42.5.1, 42.4.3, 42.3.8, 42.2.27.jre7 Security update for CVE-2022-41946](https://www.postgresql.org/about/news/postgresql-jdbc-4251-4243-4238-42227jre7-security-update-for-cve-2022-41946-2551/),
  [Quarkus 2.14.2.Final and 2.13.5.Final released - Fix for CVE-2022-4116](https://quarkus.io/blog/quarkus-2-14-2-final-released/)
  — pensez à vous mettre à jour !
- [Spring Boot 3.0 Goes GA](https://spring.io/blog/2022/11/24/spring-boot-3-0-goes-ga)
  — avec Java 17 en version minimale, l’ajout de la compilation AOT, le support de la compilation native, un support
  amélioré de l’observabilité, et surtout une tétrachiée de mises à jour, notamment :
  [Spring Framework 6.0](https://spring.io/blog/2022/11/16/spring-framework-6-0-goes-ga),
  [Jakarta EE 10](https://jakarta.ee/release/10/),
  [Hibernate ORM 6.1](https://in.relation.to/2022/06/24/hibernate-orm-61-features/),
  [Spring Security 6.0](https://spring.io/blog/2022/11/21/spring-security-5-8-and-6-0-are-now-ga),
  [Spring Data 2022.0](https://spring.io/blog/2022/11/18/spring-data-2022-0-goes-ga),
  [Flyway 9](https://flywaydb.org/documentation/learnmore/releaseNotes#9.0.0),
  [Groovy 4.0](https://groovy-lang.org/releasenotes/groovy-4.0.html)… Quelques liens pour faciliter la migration :
  - [Preparing for Spring Boot 3.0](https://spring.io/blog/2022/05/24/preparing-for-spring-boot-3-0),
  - [Spring Boot 3.0 Migration Guide](https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-3.0-Migration-Guide),
  - [The best way to do the Spring 6 migration](https://vladmihalcea.com/spring-6-migration/).
- [Starting Quarkus 3](https://quarkus.io/blog/road-to-quarkus-3/)
  — une nouvelle version majeure est en préparation chez Quarkus. Elle a l’air beaucoup moins impactante que celle de
  Spring Boot 3.0, mais on y retrouve certains sujets tels que la migration vers Jakarta EE 10 / Hibernate ORM 6.
- [Angular v15 is now available!](https://blog.angular.io/angular-v15-is-now-available-df7be7f2f4c8)
  — les _standalone components_ et la directive `NgOptimizedImage` sont désormais considérés stables, et `angular-cli`
  supporte officiellement NodeJS v18. Comme d’habitude Ninja Squad nous résume tout ça dans ses articles
  [What’s new in Angular 15?](https://blog.ninja-squad.com/2022/11/16/what-is-new-angular-15.0/) et
  [What’s new in Angular CLI 15.0?](https://blog.ninja-squad.com/2022/11/16/angular-cli-15.0/), et nous fait au passage
  découvrir [angular-cli-diff](https://github.com/cexbrayat/angular-cli-diff/).
- [Ansible 7](https://github.com/ansible-community/ansible-build-data/blob/main/7/CHANGELOG-v7.rst#release-summary)
  — avec [ansible-core 2.14](https://github.com/ansible/ansible/blob/stable-2.14/changelogs/CHANGELOG-v2.14.rst).
  Attention cette version impose de nouvelles contraintes sur les _control node_ : Python 3.9 au minimum, UTF-8 comme
  locale et UTF-8 comme encoding du système de fichier (pour plus d’informations, jetez un coup d’œil au
  [guide de migration](https://docs.ansible.com/ansible/devel/porting_guides/porting_guide_7.html)).
- [GitLab 15.6 released with improvements to security policies, CI/CD variables, and DAST API](https://about.gitlab.com/releases/2022/11/22/gitlab-15-6-released/)
  — des petites améliorations sympas, mais rien de majeur (dans la version gratuite).
- [What is EPSS? A new rating system for vulnerabilities to replace CVSS.](https://www.lunasec.io/docs/blog/what-is-epss/)
  — le machine learning semble de plus en plus utilisé [dans des indicateurs de
  sécurité](https://blog.sonatype.com/how-is-the-sonatype-safety-rating-determined).
- [Numérique : que sont le DMA et le DSA, les règlements européens qui veulent réguler internet ?](https://www.touteleurope.eu/economie-et-social/numerique-que-sont-le-dma-et-le-dsa-les-reglements-europeens-qui-veulent-reguler-internet/)
  — ces directives ont été publiées ce mois-ci et s’appliqueront en 2023-2024.
  [Il va y avoir du boulot chez Facebook !](https://www.programmez.com/actualites/meta-ne-serait-pas-capable-de-comprendre-comment-les-donnees-de-facebook-sont-traitees-34653)
- [LCC 288 - L’épisode marathon mastodonien](https://lescastcodeurs.com/2022/11/21/lcc-288-l-episode-marathon-mastodonien/)
  — l’épisode où on cite [jbanking](https://github.com/marcwrobel/jbanking) !

## Articles, podcasts et vidéos

- [Which Version of JDK Should I Use?](https://whichjdk.com/)
  — une page très bien faite pour vous aider à choisir votre JDK en fonction de vos contraintes.
- [Clean Code with Records, Sealed Classes and Pattern Matching](https://inside.java/2022/10/17/clean-code-with-amber/)
  — José Paumard présente les possibilités actuelles et futures du _pattern matching_ en Java. Intéressant !
- [Understanding Java’s Project Loom](https://www.marcobehler.com/guides/java-project-loom)
  — Marco Behler démystifie, de manière concise, les _virtual threads_.
- [The Spring Data JPA findById Anti-Pattern](https://vladmihalcea.com/spring-data-jpa-findbyid/)
  — Vlad Mihalcea nous explique pourquoi l'utilisation de `findById` peut être contre-productive.
- [Spring Modulith: have we reached modularity maturity?](https://blog.frankel.ch/spring-modulith-modularity-maturity/),
  [Spring Modulith Structures Spring Boot 3 Applications with Modules and Events](https://www.infoq.com/news/2022/11/spring-modulith-launch/)
  — quelques articles sur ce projet que je trouve prometteur.
- [What is the Quarkus support policy?](https://github.com/quarkusio/quarkus/discussions/29161)
  — bon à savoir : il est possible d’avoir du support sur Quarkus en utilisant les
  [Red Hat builds of Quarkus](https://access.redhat.com/products/quarkus).
- [Why Isn’t Functional Programming the Norm?](https://www.youtube.com/watch?v=QyJZzq0v7Z4)
  — excellente présentation de Richard Feldman sur l’histoire des languages, ce qui a fait leur popularité et pourquoi
  il n'y a pas de langage "purement fonctionnel" dans les languages les plus populaires. Dans la même veine, vous pouvez
  aussi lire l'article de Ties van de Ven : [The Problem with Functional
  Programming](https://foojay.io/today/the-problem-with-functional-programming/).
- [A poor man’s API](https://blog.frankel.ch/poor-man-api/)
  — très bonne idée ! Sinon, si votre API est statique (par exemple si elle retourne des informations sur les pays),
  vous pouvez aussi envisager de la publier en combinant votre CI/CD et un générateur de sites statiques. Pour un
  exemple voir [endoflife.date](https://github.com/endoflife-date/endoflife.date/blob/master/_plugins/create-json-files.rb).
- [My Keycloak learning journey](https://blog.codecentric.de/my-keycloak-learning-journey)
  — comment bien débuter avec Keycloak.
- [How to do proper backups (with PostgreSQL)](https://mydbanotebook.org/post/how-to-do-proper-backups/)
  — tl;dr : _use `pgBackRest` and relax_.
- [Convert JSON file to YAML using JQ](https://www.javacodegeeks.com/2022/11/convert-json-file-to-yaml-using-jq.html)
  — ça fait aussi le café `jq` ?
- [#180 — Olivier Koch — Des IA plus grandes, plus efficaces et plus rapidement](https://ifttd.io/ia-a-grande-echelle/)
  — très intéressant si comme moi vous n’y connaissez pas grand-chose en IA ou en machine learning.
- [Réutiliser un leak, c’est légal ou c’est pénal ?](https://www.nolimitsecu.fr/re-utiliser-un-leak-cest-legal-ou-cest-penal/)
  — en tout cas, comme tout ce qui touche au droit, c’est compliqué.
- [tea.xyz - Something new is brewing](https://medium.com/teaxyz/tea-brew-478a9e736638),
  [GitHub Accelerator - An open source economy–built by developers, for developers](https://github.blog/2022-11-09-an-open-source-economy-built-by-developers-for-developers/)
  — de nouvelles idées pour financer l’open source apparaissent : sympa !

## Découvertes

- [junit-pioneer — JUnit 5 extension pack, pushing the frontiers on Jupiter](https://junit-pioneer.org/docs/)
  — pleins de petites annotations qui peuvent faciliter l'écriture de certains types de tests.
- [cheat.sh — the only cheat sheet you need](https://cheat.sh)
  — [tldr](https://tldr.sh/) sous stéroïde.
- [`jc` — CLI tool that converts the output of popular command line tools to JSON](https://github.com/kellyjonbrazil/jc)
  — un outil qui permet de manipuler facilement la sortie de nombreuses de commandes (`crontab`, `dig`, `date`,
  `sysctl`...) dans des scripts ou des playbooks Ansible.
- [IE Virtual Machines — Test IE11 and Microsoft Edge Legacy using free Windows 10 virtual machines you download and manage locally](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/)
  — si vous avez ponctuellement besoin d’une VM Windows (les images sont malheureusement un peu anciennes).

[That’s all folks](https://www.youtube.com/watch?v=NiwqRSCWw2g "Sepultura - Ratamahatta"){:target="_blank"} !

<!-- prettier-ignore-start -->
*[AOT]: Ahead-Of-Time
*[API]: Application Programming Interface
*[CD]: Continuous Delivery
*[CI]: Continuous Integration
*[CVSS]: Common Vulnerability Scoring System
*[DAST]: Dynamic Application Security Testing
*[DMA]: Digital Markets Act
*[DSA]: Digital Services Act
*[EE]: Enterprise Edition
*[EPSS]: Exploit Prediction Scoring System
*[GA]: General Availability
*[IA]: Intelligence Artificielle
*[IE]: Internet Explorer
*[IE11]: Internet Explorer 11
*[JDBC]: Java DataBase Connectivity
*[JDK]: Java Development Kit
*[JPA]: Java Persistence API
*[JSON]: JavaScript Object Notation
*[LCC]: Les Cast Codeurs
*[ORM]: Object-Relational Mapping
*[PyPI]: Python Package Index
*[tl;dr]: too long; didn’t read
*[UTF-8]: Universal character set Transformation Format - 8 bits
*[VM]: Virtual Machine
*[YAML]: Yet Another Markup Language
<!-- prettier-ignore-end -->
