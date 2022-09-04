---
layout: post
title: Liens en vrac — Août 2022
category: liens
youtube_video_id: mqGAokNRFI8
youtube_video_title: Rammstein - Du Riechst So Gut (Live at Hellfest 2016)
---

## Nouvelles

- [FBI’s team to investigate massive cyberattack in Montenegro](https://apnews.com/article/russia-ukraine-technology-hacking-montenegro-2a8eb2df87f657b6d7b9971b7419bff9),
  [Estonia blocked cyberattacks claimed by Pro-Russia Killnet group](https://securityaffairs.co/wordpress/134560/cyber-warfare-2/estonia-blocked-cyberattacks-killnet.html)
  — après l’Albanie le mois dernier, le Montenegro et l’Estonie, ça n’arrête plus !
- [How 1-Time Passcodes Became a Corporate Liability](https://krebsonsecurity.com/2022/08/how-1-time-passcodes-became-a-corporate-liability/)
  — l’utilisation de SMS en tant que second facteur d’authentification est pourtant déconseillée
  [depuis un bout de temps](https://www.lemagit.fr/actualites/450404283/Deconseille-pour-lauthentification-a-double-facteur-le-SMS-est-encore-la).
- [Bleu, S3ns : pourquoi les offres Cloud de confiance seront certainement soumises au Cloud Act](https://www.latribune.fr/technos-medias/internet/bleu-s3ns-pourquoi-les-offres-cloud-de-confiance-seront-certainement-soumises-au-cloud-act-928831.html)
  — ça part mal pour le _cloud de confiance_ on dirait.
- [Another free CA to use via ACME!](https://scotthelme.co.uk/another-free-ca-to-use-via-acme/)
  — je ne sais pas si c’est nouveau, mais c’est bon à savoir.
- [What’s new in Angular 14.2?](https://blog.ninja-squad.com/2022/08/26/what-is-new-angular-14.2/)
  — [TypeScript 4.8](https://devblogs.microsoft.com/typescript/announcing-typescript-4-8/) et une nouvelle directive
  expérimentale, `NgOptimizedImage`.
- [The State of end-to-end testing with Angular](https://blog.angular.io/the-state-of-end-to-end-testing-with-angular-d175f751cb9c)
  — Protractor n’étant plus inclus dans Angular depuis la version 12, l’équipe Angular fait le point.
- [GitLab 15.3 released with tasks for managing your work and free GitOps features](https://about.gitlab.com/releases/2022/08/22/gitlab-15-3-released/)
  — et on peut enfin créer des tâches depuis les tickets.
- [GitHub Dependabot Now Alerts Developers On Vulnerable GitHub Actions](https://thehackernews.com/2022/08/github-dependabot-now-alerts-developers.html)
  — et c’est pas du luxe !
- [NIST’s Post-Quantum Cryptography Standards](https://www.schneier.com/blog/archives/2022/08/nists-post-quantum-cryptography-standards.html)
  — un petit historique qui parle du choix des algorithmes de cryptographie post-quantique par le NIST.
- [Linux 5.20 Likely To Be Called Linux 6.0](https://www.phoronix.com/news/Linux-5.20-Is-Linux-6.0)
  — la version majeure du noyau Linux est incrémentée quand la version mineure atteint 19 ou 20.
- [Please stop citing TIOBE](https://blog.nindalf.com/posts/stop-citing-tiobe/)
  — la méthodologie utilisée est effectivement absurde.

## Articles, podcasts et vidéos

- [Adopting Remote Development Environments at Slack](https://www.infoq.com/news/2022/08/slack-remote-development-env/),
  [Announcing Microsoft Dev Box Preview](https://azure.microsoft.com/en-us/blog/announcing-microsoft-dev-box-preview/),
  [jetpack-io/devbox](https://github.com/jetpack-io/devbox),
  [How to Set Up Your Local Node.js Development Environment Using Docker](https://www.docker.com/blog/how-to-setup-your-local-node-js-development-environment-using-docker/)
  — l’utilisation d’environnements de développement isolés / reproductibles gagnerait-elle en popularité ?
- [Don’t Use Kubernetes, Yet](https://matt-rickard.com/dont-use-kubernetes-yet)
  — un complément à l’article
  [Scaling to 100k Users](https://alexpareto.com/scalability/systems/2020/02/03/scaling-100k.html) du mois dernier.
- [Finding Gmail Messages with No Label](https://raisedbyturtles.org/view-unlabeled-gmail)
  — aucune de ces méthodes ne fonctionne parfaitement, mais ça permet de s’en sortir.
- [Hotwire: A new (old) approach for modern web applications](https://blog.codecentric.de/en/2022/08/hotwire-new-approach-for-modern-web-applications/)
  — vers un retour en grâce du HTML rendu côté serveur ?
  [L’interview de Carson Gross](https://podcasts.apple.com/us/podcast/hateoas-data-apis-java-and-how-htmx-happened/id1296655154?i=1000571015862),
  l’auteur de htmx, est aussi très intéressante à ce sujet.
- [apt_key deprecated in Debian/Ubuntu - how to fix in Ansible](https://www.jeffgeerling.com/blog/2022/aptkey-deprecated-debianubuntu-how-fix-ansible)
  — bon à savoir : il est possible de mettre des certificats au format ASCII-armored dans `/etc/apt/trusted.gpg.d` juste
  en suffixant le fichier avec `.asc`.
- [End-to-end tracing with OpenTelemetry](https://blog.frankel.ch/end-to-end-tracing-opentelemetry/),
  [OpenTelemetry Concepts](https://opentelemetry.io/docs/concepts/)
  — ça a l’air super OpenTelemetry !
- [Best practices for managing Java dependencies](https://snyk.io/blog/best-practices-for-managing-java-dependencies/)
  — plein de bons conseils, et j’en rajouterais un : si vous le pouvez,
  [réutilisez un POM tel que `spring-boot-dependencies`](https://github.com/marcwrobel/parent).
- [How to integrate Hibernates Multitenant feature with Spring Data JPA in a Spring Boot application](https://spring.io/blog/2022/07/31/how-to-integrate-hibernates-multitenant-feature-with-spring-data-jpa-in-a-spring-boot-application)
  — un très bon article sur le sujet.
  [L’article de Vlad Mihalcea sur le sujet](https://vladmihalcea.com/database-multitenancy/), plus général, a aussi été
  mis à jour récemment.
- [The best way to fetch a Spring Data JPA DTO Projection](https://vladmihalcea.com/spring-jpa-dto-projection/)
  — les mille et unes manières de récupérer un DTO avec Spring Data JPA.
- [Fix bugs in Bash scripts by printing a stack trace](https://opensource.com/article/22/7/print-stack-trace-bash-scripts)
  — dommage que ce soit aussi complexe d’en arriver à ce résultat.
- [Exhaustive JUNIT5 Testing with Combinations, Permutations, and Products](https://dzone.com/articles/exhaustive-junit5-testing-with-combinations-permut)
  — [Chronicle Test Framework](https://github.com/OpenHFT/Chronicle-Test-Framework), un framework à connaitre.
- [Marble testing](https://blog.ippon.fr/2022/07/27/marble-testing/)
  — c’est compliqué, mais il est toujours bon de savoir que ça existe.
- [Le Data Mapping Typescript au service de vos requêtes](https://blog.zenika.com/2022/07/12/le-data-mapping-typescript-au-service-de-vos-requetes/)
  — j’avais hésité à utiliser cette approche lors de l’un de mes derniers projets, j’ai un peu regretté de ne pas
  l’avoir fait !
- [Postgres FM](https://postgres.fm/)
  — un nouveau podcast sur PostgreSQL qui présente, toutes les semaines, un sujet lié à PostgreSQL. J’ai
  particulièrement apprécié
  [BUFFERS by default](https://postgres.fm/episodes/buffers-by-default) (cf.
  [EXPLAIN (ANALYZE) needs BUFFERS to improve the Postgres query optimization process](https://postgres.ai/blog/20220106-explain-analyze-needs-buffers-to-improve-the-postgres-query-optimization-process)
  si vous préférez lire).
- [Retour aux fondamentaux du craft : trois exemples](https://blog.octo.com/retour-aux-fondamentaux-du-craft-trois-exemples/)
  — ça ne fait parfois pas de mal de revoir les choses qu’on pense déjà connaitre.

## Découvertes

- [Data Structure Visualizations](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)
  — un dessin est parfois plus simple qu’une grosse description.
- [Vale - A linter for prose](https://vale.sh/)
  — un must-have lorsque vous écrivez beaucoup de documentation. Dommage que l’outil
  [ne supporte pas bien la javadoc](https://github.com/errata-ai/vale/discussions/482).
- [DuckDuckGo Email Protection](https://duckduckgo.com/email/)
  — _Block email trackers and hide your address without switching your email provider._
- [Renovate, a Dependabot alternative](https://blog.frankel.ch/renovate-alternative-dependabot/)
  — si vous n’utilisez pas GitHub…

That’s all folks !

<!-- prettier-ignore-start -->
*[ACME]: Automated Certificate Management Environment
*[ASCII]: American Standard Code for Information Interchange
*[CA]: Certificate Authority
*[DTO]: Data Transfer Object
*[FBI]: Federal Bureau of Investigation
*[FM]: Frequency Modulation
*[HTML]: HyperText Markup Language
*[JPA]: Java Persistence API
*[NIST]: National Institute of Standards and Technology
*[POM]: Project Object Model
*[SMS]: Short Message Service
<!-- prettier-ignore-end -->
