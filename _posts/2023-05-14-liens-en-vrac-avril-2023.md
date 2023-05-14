---
layout: post
title: Liens en vrac — Avril 2023
category: liens
seo:
  date_modified: 2023-05-14
---

Nouvelles, articles, podcasts, vidéos et découvertes intéressantes du mois de mars 2023.

## Nouvelles

- [JDK 21: The new features in Java 21](https://www.infoworld.com/article/3689880/jdk-21-the-new-features-in-java-21.html)
  — Virtual Threads, Record Patterns, String Templates, Sequenced collections… : cette prochaine
  version LTS de Java va être sympa !
- [Quarkus 3.0, our new major release, is here!](https://quarkus.io/blog/quarkus-3-0-final-released/)
  — après Spring Boot, c’est au tour de Quarkus de sortir une nouvelle version majeure. Au menu :
  dépréciation de Java 11, des mises à jour majeures de librairie (Jakarta EE 10…) et, comme à
  l’accoutumée, plein d’améliorations diverses et variées. En bonus, l’arrivée prochaine de versions
  LTS a été annoncée.
- [Node.js 20 is now available!](https://nodejs.org/en/blog/announcements/v20-release-announce)
  — Node.js 14 est désormais [EOL](https://endoflife.date/nodejs) et, pour rappel, la fin de Node.js
  16 [a été annoncée pour le 11/09/2023](https://nodejs.org/en/blog/announcements/nodejs16-eol).
  Donc, si vous devez vous mettre à jour, autant directement passer à Node.js 18 qui sera supporté
  jusqu’au 30/04/2025.
- [Announcing SonarQube 10.0](https://www.sonarsource.com/products/sonarqube/whats-new/sonarqube-10-0/)
  — avec, entre autres, l’ajout du _CWE Top 25 2022 security risk report_ et l’analyse des
  Dockerfiles.
- [Debian 12.0 "Bookworm" Planned For Release On 10 June](https://www.phoronix.com/news/Debian-12.0-Release-Date)
  — pensez à jeter un coup d’oeil [aux notes de version](https://www.debian.org/releases/bookworm/amd64/release-notes/).
- [Elastic contributes Elastic Common Schema (ECS) to OpenTelemetry (OTel)](https://www.elastic.co/blog/ecs-elastic-common-schema-otel-opentelemetry-announcement)
  — un peu de standardisation à ce niveau ne peut faire que du bien.
- [Google Authenticator now supports Google Account synchronization](https://security.googleblog.com/2023/04/google-authenticator-now-supports.html),
  — il était temps… Et pour ceux qui n’en veulent pas, cela reste optionnel.
- [Amazon CodeWhisperer est disponible et gratuit pour les particuliers](https://www.programmez.com/actualites/amazon-codewhisperer-est-disponible-et-gratuit-pour-les-particuliers-35220)
  — une alternative si vous aviez aimé GitHub Copilot mais [que vous ne souhaitez pas payer pour
  l’utiliser](https://github.com/features/copilot#pricing).
- [30 years of a free and open Web](https://home.web.cern.ch/fr/node/187836)
  — le World Wide Web a 30 ans, ça n’est pas si vieux quand on y pense !


## Articles, podcasts et vidéos

- [Picnic loves Error Prone: producing high-quality and consistent Java code](https://blog.picnic.nl/picnic-loves-error-prone-producing-high-quality-and-consistent-java-code-b8a566be6886)
  — je ne savais pas qu’[Error Prone](https://errorprone.info/) était si puissant. [Error Prone
  Support](https://error-prone.picnic.tech/) me fait pas mal penser à [OpenRewrite](https://docs.openrewrite.org/),
  mais spécialisé sur la qualité de code.
- [GraphQL: From Excitement to Deception](https://betterprogramming.pub/graphql-from-excitement-to-deception-f81f7c95b7cf)
  — un très bon retour d’expérience sur le sujet.
- [Mastering Maven: Adding Maven Extensions Using extensions.xml](https://blog.mrhaki.com/2023/04/mastering-maven-adding-maven-extensions.html)
  — tiens, il est possible d’utiliser Maven Enforcer sous forme d’extension.
- [LCC 293 - Interview Maven et builds reproductibles avec Hervé Boutemy (podcast)](https://lescastcodeurs.com/2023/04/06/lcc-293-interview-maven-et-builds-reproductibles-avec-herve-boutemy/)
  — très bonne interview sur le futur de Maven et l’intérêt de rendre ses builds reproductibles.
- [A Simpler Testing Pyramid: Getting the Most out of Your Tests](https://www.infoq.com/articles/testing-pyramid-slow-fast-tests/)
  — séparer ses tests entre ceux qui sont rapides et ceux qui sont lents est en effet beaucoup plus
  simple et moins sujet à débat.
- [Queues in Postgres (podcast)](https://postgres.fm/episodes/queues-in-postgres)
  — on peut trouver beaucoup d’articles sur le sujet, mais peu qui décortiquent aussi bien le
  problème.
- [How to encrypt Bash shell variables with Ansible Vault](https://www.redhat.com/sysadmin/ansible-vault-bash-encrypt)
  — une idée intéressante pour stocker ses secrets, même si vous n’utilisez pas Ansible.

## Découvertes

- [OSV](https://osv.dev/)
  — _A distributed vulnerability database for Open Source_.
- [Error Prone Support](https://error-prone.picnic.tech/)
  — _A Picnic-opinionated extension of Google’s Error Prone. It aims to improve code quality,
  focussing on maintainability, consistency and avoidance of common pitfalls_.
- [re:Work](https://rework.withgoogle.com)
  — _Practices, research, and tools from Google to improve your people processes_.

[That’s all folks](https://www.youtube.com/watch?v=PzCmr43L4hQ "Kyrie Kristmanson - A Garden Song"){:target="_blank"} !

<!-- prettier-ignore-start -->
*[CWE]: Common Weakness Enumeration
*[ECS]: Elastic Common Schema
*[EE]: Enterprise Edition
*[EOL]: End-Of-Life
*[LCC]: Les Cast Codeurs
*[LTS]: Long Term Support
*[ORM]: Object-Relational Mapping
*[OTel]: Open Telemetry
<!-- prettier-ignore-end -->
