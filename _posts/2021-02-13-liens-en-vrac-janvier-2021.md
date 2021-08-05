---
layout: post
title: Liens en vrac - Janvier 2021
category: liens
tags: keycloak debian bootstrap gitlab rhel elastic maven unpoly java pratique css rest api grid front jdk status cloudflare coep coop corp cors corb spring-boot validation rest patch commit protonmail jfr java intellij-idea
---

## Nouvelles

- [Keycloak 12.0.0 released](https://www.keycloak.org//2020/12/keycloak-1200-released.html)
  — le `login theme` de base a été mis à jour, attention à vos thèmes spécifiques.
- [Debian 11 Freeze Begins, Debian 12 Might Reduce Focus On i386 Support](https://www.phoronix.com/scan.php?page=news_item&px=Debian-11-Freeze-Starts)
  — pour un aperçu des nouveautés [allez voir ici](https://www.debian.org/releases/bullseye/amd64/release-notes/ch-whats-new.fr.html).
- [Bootstrap v4.6.0](https://blog.getbootstrap.com/2021/01/19/bootstrap-4.6.0/)
  — peu de changements, l’équipe se concentre sur [Bootstrap v5](https://blog.getbootstrap.com/2021/02/10/bootstrap-5-beta-2/).
- [GitLab 13.8 released with a Pipeline Editor and DORA metrics](https://about.gitlab.com/releases/2021/01/22/gitlab-13-8-released/)
  — et beaucoup de petites améliorations sympathiques telles que le _multiline merge request_, le support des variables prédéfinies dans les _includes_…
- [New Year, new Red Hat Enterprise Linux programs: Easier ways to access RHEL](https://www.redhat.com/en/blog/new-year-new-red-hat-enterprise-linux-programs-easier-ways-access-rhel)
  — l’utilisation de RHEL est maintenant gratuite dans certaines
  conditions ([FAQs for no-cost Red Hat Enterprise Linux](https://developers.redhat.com/articles/faqs-no-cost-red-hat-enterprise-linux)).
- [GitLab is moving to a three-tier product subscription model](https://about.gitlab.com/blog/2021/01/26/new-gitlab-product-subscription-model/)
  — et retire les offres _Bronze_ et _Starter_.
- [Amazon : INACCEPTABLE - pourquoi nous avons dû changer de licence pour Elastic](https://www.elastic.co/fr/blog/why-license-change-AWS)
  — Elastic change de license pour ne plus se faire entuber par Amazon.

## Articles, podcasts et vidéos

- [mvnd: Maven’s Speed Daemon, a Conversation with Peter Palaga and Guillaume Nodet](https://www.infoq.com/news/2020/12/mvnd-mavens-speed-daemon/)
  — une initiative qui vise à augmenter la vitesse des _builds_ Maven.
- [It’s not you, it’s us We're breaking up with JavaScript frontends](http://triskweline.de/unpoly-rugb/)
  — le pourquoi de Unpoly, _the unobtrusive JavaScript framework for server-side web applications_.
- [Les exceptions, mauvaise solution pour la gestion des erreurs dans une application](https://blog.engineering.publicissapient.fr/2021/01/11/les-exceptions-mauvaise-solution-pour-la-gestion-des-erreurs-dans-une-application/)
  — très intéressant cet article, même si un peu trop dogmatique.
- [The CSS Grid Layout](https://medium.com/helpful-human/the-css-grid-layout-2d6a0a119196)
  — il n’y a pas à dire, je suis vraiment à la ramasse en CSS…
- [Prerequisites for Font Support in AdoptOpenJDK](https://blog.adoptopenjdk.net/2021/01/prerequisites-for-font-support-in-adoptopenjdk/)
  — pour ceux sur Debian : `apt-get install libfreetype6 fontconfig fonts-dejavu`.
- [Setting up a quick and easy status page with Cloudflare Workers!](https://scotthelme.co.uk/setting-up-a-quick-and-easy-status-page-with-cloudflare-workers/)
  — une alternative intéressante à StatusCake, Pingdom et consort.
- [COEP COOP CORP CORS CORB - CRAP that’s a lot of new stuff!](https://scotthelme.co.uk/coop-and-coep/)
  — OMG !
- [Validation in Spring Boot applications](https://www.mscharhag.com/spring/validation-in-spring-boot-applications)
  — sinon un peu de code dans un bon vieux constructeur ça peu faire aussi l’affaire.
- [REST: Partial updates with PATCH](https://www.mscharhag.com/api-design/rest-partial-updates-patch)
  — la suite d’une belle série sur l’utilisation des verbes HTTP dans une API REST.
- [Amdahl’s & Gunther’s laws pour l’organisation des équipes de développement](https://www.touilleur-express.fr/2021/01/11/amdahls-gunthers-laws-pour-lorganisation-des-equipes-de-developpement/)
  — et oui, l’ajout de développeurs sur un projet n’est pas une solution miracle.
- [How Square writes commit messages](https://medium.com/square-corner-blog/how-square-writes-commit-messages-8e92fcbf77c9#---415-539)
  — toujours intéressant ce genre de retour, et en complément : [Conventional Commits](https://www.conventionalcommits.org/).
- [Keycloak Embedded in a Spring Boot Application](https://www.baeldung.com/keycloak-embedded-in-spring-boot-app)
  — tient tien, c’est intéressant.
- [Using JDK FlightRecorder and JDK Mission Control](https://blog.arkey.fr/2020/06/28/using-jdk-flight-recorder-and-jdk-mission-control/)
  — on peut en faire des choses avec ces outils.

## Découvertes

- [ProtonMail - Best Gmail alternative for privacy and security](https://protonmail.com/blog/gmail-alternative/)
  — avec la gestion des contacts, des calendriers (_Proton Calendar_), et des fichiers (_Proton Drive_) ça commence à être une belle alternative à la suite
  Google.
- [System Lambda](https://github.com/stefanbirkner/system-lambda)
  — une collection d’utilitaires facilitant les tests faisant intervenir `java.lang.System` (variables d’environnement, _System Properties_, `System.out`
  , `System.err`…).
- [Plugin Intellij IDEA - String Manipulation](https://plugins.jetbrains.com/plugin/2162-string-manipulation)
  — un petit bijou !

That’s all folks !

*[API]: Application Programming Interface
*[COEP]: Cross Origin Embedder Policy
*[COOP]: Cross Origin Opener Policy
*[CORB]: Cross Origin Read Blocking
*[CORP]: Cross Origin Resource Policy
*[CORS]: Cross-Origin Resource Sharing
*[CSS]: Cascading Style Sheets
*[DORA]: DevOps Research and Assessment
*[FAQ]: Frequently Asked Questions
*[JDK]: Java Development Kit
*[OMG]: Oh My God!
*[REST]: REpresentational State Transfer
*[RHEL]: Red Hat Enterprise Linux
