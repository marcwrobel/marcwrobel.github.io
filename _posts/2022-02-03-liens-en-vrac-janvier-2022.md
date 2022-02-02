---
layout: post
title: Liens en vrac — Janvier 2022
category: liens
youtube_video_id: iZKXoAMmJHE
youtube_video_title: Stella Donnelly - Beware Of The Dogs
---

## Nouvelles

- [Bootstrap Icons v1.8.0](https://blog.getbootstrap.com/2022/01/31/bootstrap-icons-1-8-0/)
  — 140 nouvelles icônes.
- [Highlights from Git 2.35](https://github.blog/2022-01-24-highlights-from-git-2-35/)
  — les nouvelles options de `git stash`, `-p` et `--staged`, m’ont l’air très intéressantes.
- [Angular 2021 Recap and 2022 Preview](https://blog.angular.io/angular-2021-recap-and-2022-preview-cb3067f76217)
  — pour ma part, j’ai particulièrement apprécié la v13 avec ses améliorations de performances au build comme au runtime
  ansi que le support de Node 16 / npm 8.
- [Keycloak certified as FAPI and Brazil Open Banking provider](https://www.keycloak.org/2022/01/fapi)
  — félicitations !
- [Open source maintainer pulls the plug on npm packages colors and faker, now what?](https://snyk.io/blog/open-source-npm-packages-colors-faker/)
  — si ça n'est pas le cas, [utilisez les _lock files_](https://snyk.io/blog/what-is-package-lock-json/).
- [Java 18 : quoi de neuf ?](https://www.loicmathieu.fr/wordpress/informatique/java-18-quoi-de-neuf/)
  — petit tout du propriétaire maintenant que Java 18 est _features complete_.
- [If it looks like a duck, swims like a duck, and QWACs like a duck, then it's probably an EV Certificate](https://scotthelme.co.uk/looks-like-a-duck-swims-like-a-duck-qwacs-like-a-duck-probably-an-ev-certifiacate/)
  — les autorités de certification se cherchent un nouveau business ?

## Articles, podcasts et vidéos

- [Six Features From Java 12 to 17 to Get Excited About!](https://www.infoq.com/articles/six-features-jdk12-to-jdk17)
  — auxquelles j'ajouterais [`Stream.toList()`](https://todd.ginsberg.com/post/java-16/stream-tolist/).
- [On Rocks and Sand](https://www.2ndquadrant.com/en/blog/on-rocks-and-sand/)
  — avec PostgreSQL l’ordre des colonnes d’une table n’est généralement pas très important, enfin généralement...
- [Object Mapping Observations and the Deprecated Dozer](https://adambien.blog/roller/abien/entry/object_mapping_observations_and_the)
  — tl;dr : _With Java Records, JSON-P, or Java Records and JSON-B you get interesting out-of-the-box alternatives to an
  external library and so dependency._
- [Java Enums, JPA and Postgres enums - How do I make them work together?](https://stackoverflow.com/a/43125099)
  — `stringtype=unspecified` a l’air d’être une solution simple et efficace.
- [How to start spring-boot app without depending on Database?](https://stackoverflow.com/a/23875516)
  — si vous vous posiez la question, voilà la réponse.
- [A table with both a sticky header and a sticky first column](https://css-tricks.com/a-table-with-both-a-sticky-header-and-a-sticky-first-column/)
  — celui-là je le garde sous le coude.
- [The burden of an Open Source maintainer](https://www.jeffgeerling.com/blog/2022/burden-open-source-maintainer)
  — soyez sympas et compréhensifs avec les mainteneurs de projets open source !
- [When does a table become too big?](https://connor-mcdonald.com/2021/11/13/when-does-a-table-become-too-big/)
  — l’efficacité des moteurs de base de données m’étonnera toujours. 
- [Initialization Strategies With Testcontainers For Integration Tests](https://rieckpil.de/initialization-strategies-with-testcontainers-for-integration-tests/)
  et [Using Testcontainers in Spring Boot Tests For Database Integration Tests](https://blog.sandra-parsick.de/2020/05/21/using-testcontainers-in-spring-boot-tests-for-database-integration-tests/)
  — quelques bons articles sur `Testcontainers`.
- [What's in a Good Error Message?](https://www.morling.dev/blog/whats-in-a-good-error-message/)
  — une description, du contexte, et, si possible, des informations pour s’en dépêtrer.
- [5 ways to make your Ansible modules work faster](https://www.redhat.com/sysadmin/faster-ansible-modules)
  — le module [`synchronize`](https://docs.ansible.com/ansible/latest/collections/ansible/posix/synchronize_module.html)
  m’a l’air sympathique.

## Découvertes

- [How to Download Windows 10 for Free](https://www.extremetech.com/computing/260524-download-windows-10-free)
  — en fait, Windows c'est gratuit.
- [My Little Team](https://www.mylittleteam.com)
  — un _job-board_ un peu différent.
- [`dstat`](https://haydenjames.io/dstat-command-in-linux-examples/)
  — `vmstat` + `iostat` + `ifstat` + `netstat`.

That’s all folks !

*[EV]: Extended Validation
*[FAPI]: Financial-grade API
*[JPA]: Java Persistence API
*[JSON-P]: JSON Processing
*[JSON-B]: JSON Binding
*[QWACs]: Qualified Website Authentication Certificates
*[npm]: Node Package Manager
