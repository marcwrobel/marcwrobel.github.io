---
layout: post
title: Liens en vrac — Mars 2023
category: liens
seo:
  date_modified: 2023-04-11
---

Nouvelles, articles, podcasts, vidéos et découvertes intéressantes du mois de mars 2023.

## Nouvelles

- [It’s Java 20 Release Day! Here’s What’s New](https://foojay.io/today/its-java-20-release-day-heres-whats-new/)
  — au menu : maturation des JEP autours du _pattern matching_ (Pattern Matching for switch, Record
  Patterns), de la concurrence (Virtual Threads, Scoped Values, Structured Concurrency) et du natif
  (Foreign Function & Memory API, Vector API). [Côté sécurité](https://seanjmullan.org/blog/2023/03/22/jdk20)
  DTLS 1.0 et les cipher suites ECDH sont désormais désactivés par défaut. À noter aussi : les
  méthodes `suspend`, `resume` et `stop` de la classe `Thread` déclenchent dorénavant une
  `UnsupportedOperationException` quand elles sont utilisées, et le support de Java 7 a été retiré
  de `javac`.
- [Announcing TypeScript 5.0](https://devblogs.microsoft.com/typescript/announcing-typescript-5-0/)
  — beaucoup de changements internes, permettant des gains importants en performance / taille.
  Pour les utilisateurs, la migration ne devrait pas être beaucoup plus compliquée que d’habitude.
  De plus des améliorations sympas ont été faites, telle que la modernisation des decorators.
- [New Design, New Features: Maven Central Improvements for Developers](https://blog.sonatype.com/new-design-new-features-maven-central-improvements-for-developers)
  — la nouvelle version de [search.maven.org](https://search.maven.org/) est désormais officiellement
  sortie.
- [Generate an SBOM from the dependency graph](https://github.blog/changelog/2023-03-28-generate-an-sbom-from-the-dependency-graph/)
  — il est désormais possible de générer un SBOM au format SPDX pour un projet GitHub.
- [Docker Compose: What’s New, What’s Changing, What’s Next](https://www.docker.com/blog/new-docker-compose-v2-and-v1-deprecation/)
  — Compose V1 ne sera plus supporté à partir de Juin 2023.
- [Your.Online: Gandi continues its development](https://news.gandi.net/en/2023/03/your-online-gandi-continues-its-development/)
  — Gandi fusionne avec TWS (un hébergeur néerlandais). TWS est renommé au passage Your.Online, mais
  Gandi reste autonome, en tout cas pour le moment.
- [GPT-4: Commotion And Controversy](https://www.forbes.com/sites/calumchace/2023/03/30/gpt-4-commotion-and-controversy/?sh=2d9a449251fd),
  [Introducing Mozilla.ai: Investing in trustworthy AI](https://blog.mozilla.org/en/mozilla/introducing-mozilla-ai-investing-in-trustworthy-ai/),
  [Italy blocks OpenAI’s ChatGPT, opens probe over privacy failings](https://www.france24.com/en/europe/20230331-italy-blocks-openai-s-chatgpt-opens-probe-over-privacy-failings)
  — ça bouge toujours autant côté IA !


## Articles, podcasts et vidéos

- [Leveling Up in Job Interviews for Software Engineers](https://phauer.com/2022/leveling-up-job-interviews/)
  — de bons conseils, j’aurais aimé avoir vu ce lien il y a quelques mois.
- [Spring Boot Multi-tenant Architecture Overview](https://medium.com/@konstde00/spring-boot-multi-tenant-architecture-overview-88198ea3991f)
  — un article très complet sur le sujet, et pour une fois avec des exemples détaillés.
- [Boosting password security! Pwned Passwords, zxcvbn, and more!](https://scotthelme.co.uk/boosting-account-security-pwned-passwords-and-zxcvbn/)
  — excellent article qui donne beaucoup d’idées sur les choses à mettre en place pour améliorer la
  sécurité des mots de passe d’une application.
- [How to find dead code in your Java services](https://blog.picnic.nl/how-to-find-dead-code-in-your-java-services-d167c8f22838)
  — une utilisation très originale de JaCoCo sur une application Java en production.
- [5 Great Reasons to use jOOQ](https://foojay.io/today/5-great-reasons-to-use-jooq/)
  — je vais avoir l’occasion d’utiliser cette librairie dans le cadre de mon nouveau job : ça m’a
  l’air prometteur !
- [The Cargo Cult of Good Code](https://pboyd.io/posts/cargo-cult-of-good-code/)
  — une jolie reflexion sur l’écriture de "bon code".
- [The problem with development speed](https://www.infoworld.com/article/3690319/the-problem-with-development-speed.html)
  — tl;dr : cherchez plutôt à maximiser l’impact que la vitesse.
- [Pagination and the problem of the total result count](https://www.cybertec-postgresql.com/en/pagination-problem-total-result-count/)
  — un bon résumé de différentes techniques de pagination.
- [Is your Postgres ready for production?](https://www.crunchydata.com/blog/is-your-postgres-ready-for-production)
  — une petite liste de contrôle des choses à vérifier côté PostgreSQL avant de passer en production.
- [Web fingerprinting is worse than I thought](https://www.bitestring.com/posts/2023-03-19-web-fingerprinting-is-worse-than-I-thought.html)
  — tl;dr : utilisez Tor Browser ou Firefox (avec `resistFingerprinting=true`).
- [Pentest : Aspects juridiques (podcast)](https://www.nolimitsecu.fr/pentest-aspects-juridiques/)
  — expliqués par un avocat, [Marc-Antoine Ledieu](https://technique-et-droit-du-numerique.fr/ledieu-avocats-technique-et-droit-du-numerique/),
  contributeur de longue date à NoLimitSecu.
- [Ansible - Durcissez vos rôles avec OpenScap](https://blog.stephane-robert.info/post/ansible-collections-hardening/)
  — intelligent comme approche !

## Découvertes

- [Diátaxis](https://diataxis.fr/)
  — _A systematic framework for technical documentation authoring_.
- [PostgREST](https://postgrest.org/)
  — _Serve a RESTful API from any Postgres database_.
- [Ballerina](https://www.infoworld.com/article/3688921/ballerina-a-programming-language-for-the-cloud.html)
  — _A programming language for the cloud_.

[That’s all folks](https://www.youtube.com/watch?v=zzHQQEFCyX0 "Plini - Electric Sunrise"){:target="_blank"} !

<!-- prettier-ignore-start -->
*[AI]: Artificial Intelligence
*[API]: Application Programming Interface
*[DTLS]: Datagram Transport Layer Security
*[ECDH]: Elliptic-curve Diffie-Hellman
*[GPT-4]: Generative Pre-trained Transformer 4
*[IA]: Intelligence Artificielle
*[JEP]: JDK Enhancement-Proposal
*[jOOQ]: Java Object-Oriented Querying
*[LTS]: Long Term Support
*[SBOM]: Software Bill Of Materials
*[SPDX]: Software Package Data Exchange
*[tl;dr]: too long; didn’t read
*[TWS]: Total Web Solutions
<!-- prettier-ignore-end -->
