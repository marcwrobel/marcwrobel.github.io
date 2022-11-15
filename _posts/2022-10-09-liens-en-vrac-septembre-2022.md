---
layout: post
title: Liens en vrac — Septembre 2022
category: liens
seo:
  date_modified: 2022-11-15
---

Nouvelles, articles, podcasts, vidéos et découvertes intéressantes du mois de septembre 2022.

## Nouvelles

- [Java 19 Delivers Features for Projects Loom, Panama and Amber](https://www.infoq.com/news/2022/09/java19-released/)
  — pour voir en action les _virtual threads_ et les nouvelles _structured concurrency APIs_ vous pouvez jeter un coup
  d’œil à la vidéo de Nicolai Parlog, [Java 19 in Action](https://www.youtube.com/watch?v=vvXmO2ZMGsk). Et, comme
  d’habitude, Sean Mullan récapitule les [JDK 19 Security Enhancements](https://seanjmullan.org/blog/2022/09/22/jdk19).
- [JDK 20 - Support for 1.7 source and target removed from javac](https://inside.java/2022/09/26/quality-heads-up/)
  — pour rappel Oracle a mis fin au support étendu de Java 7 le 19/07/2022.
- [Jakarta EE 10 Delivers New Core Profile and Updates to Specifications](https://www.infoq.com/news/2022/09/jakarta-ee-10-updates/)
  — la migration vers `jakarta.*` étant derrière eux, de nouvelles fonctionnalités arrivent enfin (tel que le support
  des UUID avec Jakarta Persistence 3.1, le support d’OIDC avec Jakarta Security 3.0...).
- [JUnit 5.9 Supports GraalVM Native Image](https://www.infoq.com/news/2022/09/junit-5-9/)
  — et il est désormais plus facile de désactiver l’exécution de tests en fonction du système d’exploitation via
  `@EnabledOnOs` et `@DisabledOnOs`.
- [Spring Boot 3 Ships November 2022, Delays Java Module Support](https://www.infoq.com/news/2022/10/spring-boot-3-jax-london/)
  — Spring Boot 3, et le support de
  [la compilation native](https://spring.io/blog/2022/09/26/native-support-in-spring-boot-3-0-0-m5),
  c’est pour bientôt ! Pour vous préparer vous pouvez d’ores et déjà jeter un coup d’œil à
  [Spring Boot Migrator](https://www.infoq.com/news/2022/09/spring-boot-migrator/).
- [PostgreSQL 15 – New Features to Be Excited About](https://www.percona.com/blog/postgresql-15-new-features-to-be-excited-about/)
  — si tout va bien, PostgreSQL 15 sortira le 13/10/2022. J’ai hâte d’avoir l’occasion de pouvoir tester la nouvelle
  commande `MERGE`.
- [GitLab 15.4 released with Suggested Reviewers and better VS Code CI/CD experience](https://about.gitlab.com/releases/2022/09/22/gitlab-15-4-released/)
  — la gestion des tâches est améliorée et, pour ceux qui n’ont jamais aimé les `table` markdown, le support
  des `json:table` pourrait être une bonne alternative.
- [Debian Chooses A Reasonable, Common Sense Solution To Dealing With Non-Free Firmware](https://www.phoronix.com/news/Debian-Non-Free-Firmware-Result)
  — les [unofficial non-free images including firmware
  packages](https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/) ne seront bientôt plus
  nécessaires !
- [Canonical launches free personal Ubuntu Pro subscriptions for up to five machines](https://ubuntu.com/blog/ubuntu-pro-beta-release)
  — intéressant pour les projets open source et les petites entreprises.
- [Evolution des prix des nouveaux services chez OVHcloud](https://www.ovhcloud.com/fr/new-services-repricing/)
  — OVH augmente ses prix à cause de l’augmentation du prix de l’énergie.
- [Heroku is dead: Let’s deploy Spring Boot containers on fly.io!](https://blog.codecentric.de/spring-boot-flyio)
  — pour ceux qui chercheraient une alternative à [Heroku](https://blog.heroku.com/next-chapter).
- [A New Life for Certificate Revocation Lists](https://letsencrypt.org/2022/09/07/new-life-for-crls.html)
  — les _Browser-Summarized CRLs_ leur redonnent une nouvelle jeunesse.
- [SEPA 2.0 is in full swing – the migration to new format specifications is starting!](https://www.ebicsblog.com/2022/09/sepa-20-is-in-full-swing-migration-to.html)
  — on dirait qu’il va y avoir du changement en novembre 2023 !

## Articles, podcasts et vidéos

- [Security today: change your habbits and make it safer and efficient](https://www.youtube.com/watch?v=NjCbJbzRmhI)
  — vers une approche plus pragmatique de la sécurité informatique ?
- [Sécurité avec les headers HTTP : Tour d’horizon des attaques et défenses possibles](https://www.youtube.com/watch?v=i9nugl0-2hw)
  — une présentation illustrée de divers headers HTTP liés à la sécurité.
- [Arrêtez (de conseiller) d’utiliser Google Public DNS](https://www.shaftinc.fr/arretez-google-dns.html)
  — je ne savais pas que [la FDN proposait des résolveurs publics](https://www.fdn.fr/actions/dns/).
- [My 3 favorite Podman features](https://www.redhat.com/sysadmin/podman-favorite-features)
  — il serait vraiment temps que je m’y mette !
- [How Not to Use MySQL](https://hackmysql.com/post/book-9/)
  — pas mal de choses sont aussi valables en dehors de MySQL.
- [Why Auto Increment Is A Terrible Idea](https://www.clever-cloud.com/blog/engineering/2015/05/20/why-auto-increment-is-a-terrible-idea/)
  — l’arrivée de [nouveaux formats d’UUID](https://uuid6.github.io/uuid6-ietf-draft/) devrait en plus améliorer les
  choses.
- [A better git blame with --ignore-rev](https://michaelheap.com/git-ignore-rev/)
  — comment ignorer certains commits avec `git blame`.
- [Parallelize Only Java Unit Tests with JUnit 5 and Maven](https://rieckpil.de/parallelize-only-java-unit-tests-with-junit-5-and-maven/)
  — bon à savoir, mais ça peut faire doublon si votre build Maven se fait déjà en parallèle.
- [Architecture documentation as code with Structurizr and Asciidoctor. Part 1: Workflow and tooling](https://blog.codecentric.de/architecture-documentation-docs-as-code-structurizr-asciidoctor),
  [Visualiser l’architecture de vos projets](https://blog.eleven-labs.com/fr/visualiser-l-architecture-de-vos-projets/)
  — deux articles intéressants sur la création de diagrammes d’architecture.
- [Protect Your Angular App From Cross-Site Scripting](https://developer.okta.com/blog/2022/07/06/spa-web-security)
  — une série d’articles sympas sur la sécurité des SPA (avec un focus sur Angular).
- [The new wave of Javascript web frameworks](https://frontendmastery.com/posts/the-new-wave-of-javascript-web-frameworks/)
  — un bel article sur l’historique de l’écosystème Javascript, jusqu’à nos jours.
- [Why you don’t need to worry about scaling your Java webapp](https://www.youtube.com/watch?v=PvApFICtCiI)
  — excellente présentation sur les tests de charge, un exemple concret de ce qu’on peut lire
  sur [Load Testing: An Unorthodox Guide](https://www.marcobehler.com/guides/load-testing).
- [Y’en a marre du software craftsmanship !](https://www.youtube.com/watch?v=KpQ-t9wWU3k)
  — encore un domaine où le dogmatisme fait rage on dirait !
- [Microservices are becoming the default application architecture choice – is it time to jump in?](https://blog.scaleway.com/microservices-are-becoming-the-default-application-architecture-choice-is-it-time-to-jump-in/),
  [What are the benefits of a microservices architecture?](https://about.gitlab.com/blog/2022/09/29/what-are-the-benefits-of-a-microservices-architecture/)
  — beaucoup semblent oublier que développer, déployer et exploiter des microservices, c’est compliqué.

## Découvertes

- [A set of tools made for developers](https://devtools.best/)
  — plein de petits outils dont on a régulièrement besoin quand on développe.
- [BurntSushi/xsv](https://github.com/BurntSushi/xsv)
  — une sorte de [jq](https://stedolan.github.io/jq/), mais pour le CSV.
- [Open Practice Library](https://openpracticelibrary.com/)
  — un ensemble de documentations sur des pratiques et principes pour construire des logiciels.
- [fontsource/fontsource](https://github.com/fontsource/fontsource)
  — pratique si vous utilisez npm et que vous souhaitez vous passer de services d’hébergement de fonts, tels que
  [Google Fonts](https://fonts.google.com/).
- [nmon](http://nmon.sourceforge.net)
  — un outil qui permet de facilement visualiser / sauvegarder toutes sortes d’indicateurs de performance système.
- [cybertec-postgresql/pg_squeeze](https://github.com/cybertec-postgresql/pg_squeeze)
  — _an extension that removes unused space from a table and optionally sorts tuples according to particular index_.

[That’s all folks](https://www.youtube.com/watch?v=pEtseprzors "Philip Glass - Mad Rush (organ version by Donald Joyce)"){:target="_blank"} !

<!-- prettier-ignore-start -->
*[APIs]: Application Programming Interfaces
*[CD]: Continuous Delivery
*[CI]: Continuous Integration
*[CRLs]: Certificate Revocation Lists
*[CSV]: Comma-Separated Values
*[DNS]: Domain Name System
*[FDN]: French Data Network
*[EE]: Enterprise Edition
*[HTTP]: Hypertext Transfer Protocol
*[JDK]: Java Development Kit
*[nmon]: Nigel’s performance Monitor
*[npm]: Node Package Manager
*[OIDC]: OpenID Connect
*[SEPA]: Single Euro Payments Area
*[SPA]: Single-Page Application
*[UUID]: Universal Unique IDentifier
<!-- prettier-ignore-end -->
