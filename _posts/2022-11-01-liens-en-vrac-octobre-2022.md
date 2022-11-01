---
layout: post
title: Liens en vrac — Octobre 2022
category: liens
youtube_video_id: nbb8RyvK7Us
youtube_video_title: Agnes Obel - It's Happening Again
---

## Nouvelles

- [Text4Shell: A Vulnerability in Java library Apache Commons Text (CVE-2022-42889)](https://www.lunasec.io/docs/blog/text4shell-java-rce-cve-2022-42889/),
  [What the OpenSSL Vulnerabilities Are…and Aren't (CVE-2022-3786 & CVE-2022-3602)](https://blog.sonatype.com/what-the-openssl-vulnerabilities-are-and-arent)
  — pensez à vous mettre à jour !
- [PostgreSQL 15 Released!](https://www.postgresql.org/about/news/postgresql-15-released-2526/)
  — avec à nouveau des améliorations de performance, le support de `MERGE`, l'ajout de `jsonlog` et plein d'autres
  choses sympas. Attention, [de nouvelles restrictions sont désormais appliquées sur le schéma
  `public`](https://www.crunchydata.com/blog/be-ready-public-schema-changes-in-postgres-15). Pour plus d'informations,
  je vous recommande d'écouter l'épisode [PostgreSQL 15 sur Postgres FM](https://postgres.fm/episodes/postgresql-15).
- [ArchUnit 1.0.0](https://github.com/TNG/ArchUnit/releases/tag/v1.0.0)
  — peu d'améliorations, mais quelques _breaking changes_. Félicitations aux développeurs de cette belle bibliothèque !
- [Keycloak 20.0.0 released](https://www.keycloak.org/2022/11/keycloak-2000-released)
  — au menu : retrait de la distribution Wildfly, support d'OpenJDK 17, et tout un tas d'autres choses. 
- [Node.js 19 is now available!](https://nodejs.org/en/blog/announcements/v19-release-announce/)
  — et [Node.js 18](https://nodejs.org/en/blog/release/v18.12.0/) devient la nouvelle version LTS. Au passage
  [npm 9.0.0](https://github.blog/changelog/2022-10-24-npm-v9-0-0-released/) vient lui aussi de sortir.
- [GitLab 15.5 released with GitLab Cloud Seed and Autocomplete suggestions](https://about.gitlab.com/releases/2022/10/22/gitlab-15-5-released/)
  — des petites améliorations sympas, mais rien de majeur (dans la version gratuite).
- [SonarQube 9.7 is here!](https://blog.sonarsource.com/sonarqube-9.7-is-here/)
  — L'intégration avec GitHub s'améliore, mais il reste toujours aussi compliqué
  [d'analyser les pull requests issues de forks](https://community.sonarsource.com/t/how-to-use-sonarcloud-with-a-forked-repository-on-github/).
- [Introducing the Event-Driven Ansible developer preview](https://www.ansible.com/blog/introducing-event-driven-ansible)
  — il est désormais possible de déclencher l'exécution de playbooks Ansible sur des évènements au travers d'une
  nouvelle commande, [ansible-rulebook](https://blog.stephane-robert.info/post/ansible-event-driven/). Ça ouvre de
  nouvelles possibilités !
- [Selectively Shifting and Constraining Computation](https://openjdk.org/projects/leyden/notes/02-shift-and-constrain)
  — Mark Reinhold parle du projet Leyden et introduit un nouveau concept qui pourrait bientôt être ajouté à la Java
  Platform Specification : celui de _condenser_.
- [Oracle aligns GraalVM development with Java development](https://www.infoworld.com/article/3678348/oracle-aligns-graalvm-development-with-java-development.html)
  — le même jour que la
  [sortie de GraalVM 22.3](https://medium.com/graalvm/graalvm-22-3-is-here-jdk-19-builds-jlink-support-new-monitoring-features-and-more-f6e2b2eeff95),
  Oracle [annonce](https://www.graalvm.org/2022/openjdk-announcement/) le transfert de certaines parties de GraalVM
  (GraalVM JIT et _native image_) à OpenJDK. Ils espèrent ainsi favoriser l'adoption de GraalVM.
- [Introducing the Java SE Subscription Enterprise Performance Pack](https://blogs.oracle.com/java/post/introducing-the-java-se-subscription-enterprise-performance-pack)
  — ça peut être sympa pour ceux qui sont coincés sur le JDK 8 et qui veulent gagner en performance à moindres frais
  (l'accès à ce pack nécessite une [souscription Java SE](https://www.oracle.com/java/java-se-subscription/)).
- [Adoptium Welcomes Google](https://blog.adoptium.net/2022/10/adoptium-welcomes-google/)
  — étonnant, Google n'a pas créé son propre build d'OpenJDK 😝.
- [Sigstore Announces General Availability for Rekor and Fulcio](https://blog.sigstore.dev/sigstore-ga-ddd6ba67894d),
  [Announcing GUAC, a great pairing with SLSA (and SBOM)!](https://security.googleblog.com/2022/10/announcing-guac-great-pairing-with-slsa.html),
  [How Is the Sonatype Safety Rating Determined?](https://blog.sonatype.com/how-is-the-sonatype-safety-rating-determined)
  — il y a vraiment beaucoup d'initiatives liées à la sécurisation de la chaîne d'approvisionnement logicielle cette
  année !
- [Meetup ElasticFR #80 - Stateless Elasticsearch](https://www.youtube.com/watch?v=863CPmN2JTU)
  — j'ai eu l'impression en participant à ce meetup qu'Elastic s'oriente très fortement vers le
  [SaaS](https://www.elastic.co/fr/blog/how-moving-to-the-cloud-leads-to-a-better-customer-experience) au détriment du
  [_on-premises_](https://www.elastic.co/fr/blog/when-to-scale-from-free-software-to-cloud-services).
- [Dependabot now updates comments in GitHub Actions workflows referencing action versions](https://github.blog/changelog/2022-10-31-dependabot-now-updates-comments-in-github-actions-workflows-referencing-action-versions/)
  — cool !

## Articles, podcasts et vidéos

- [Introducing Spring Modulith](https://spring.io/blog/2022/10/21/introducing-spring-modulith)
  — j'aime bien cette approche, même si je n'ai jamais pu la tester "en vrai".
- [Spring Tips: the road to Spring Boot 3: Spring Framework 6](https://spring.io/blog/2022/10/26/spring-tips-the-road-to-spring-boot-3-spring-framework-6)
  — dans cette vidéo, Josh Long nous montre quelques-unes des nouvelles fonctionnalités de Spring Framework 6 et de
  Spring Boot 3 : l'intégration de la [RFC 7807: Problem Details for HTTP APIs](https://www.rfc-editor.org/rfc/rfc7807),
  la nouvelle [Observation API](https://spring.io/blog/2022/10/12/observability-with-spring-boot-3) et
  le support de la [compilation native](https://spring.io/blog/2022/09/26/native-support-in-spring-boot-3-0-0-m5).
- [Migrating to Hibernate 6](https://thorben-janssen.com/migrating-to-hibernate-6/)
  — ça pourrait vous aider, notamment si vous prévoyez une migration vers Spring Framework 6 / Spring Boot 3.
- [JSpecify - Standard Java Annotations for Static Analysis](https://jspecify.dev/)
  — est-ce qu'on va enfin avoir une réponse définitive à la question
  [Which @NotNull Java annotation should I use?](https://stackoverflow.com/q/4963300/374236) !?
- [Building a Distributed Audit Log with YugabyteDB](https://vladmihalcea.com/audit-log-yugabytedb/)
  — l'approche utilisée est intéressante.
- [10 More Common Mistakes Java Developers Make when Writing SQL](https://dzone.com/articles/10-more-common-mistakes-java)
  — c'est la première fois que je vois un article qui encourage l'utilisation des contraintes SQL pour des questions de
  performance.
- [pgbouncer: Types of PostgreSQL connection pooling](https://www.cybertec-postgresql.com/en/pgbouncer-types-of-postgresql-connection-pooling/)
  — si comme moi vous ne saviez pas qu'il y avait plusieurs types de _connection pooling_.
- [Devops - Diagrams as Code](https://blog.stephane-robert.info/post/devops-diagram-as-code/)
  — [Diagrams](https://github.com/mingrammer/diagrams) est plus joli et extensible que PlantUML ou Mermaid.js, mais
  quand même moins pratique à utiliser je trouve.
- [jmtd → log → podman generate](https://jmtd.net/log/podman_generate/)
  — bon à savoir : _Running the docker CLI under a process supervisor only results in supervising the CLI process_.
- [How to use Java DTOs to stay secure](https://snyk.io/blog/how-to-use-java-dtos/)
  — au-delà du découplage entre différentes couches ou sous-systèmes, l'utilisation de DTO spécialisés (c.-à-d.
  non réutilisés dans des contextes différents) a aussi l'avantage de diminuer le risque de fuites de données
  accidentelles.
- [Maintaining monopolies with the cloud](https://pluralistic.net/2022/09/28/other-peoples-computers/) et
  [The Cloud is Not a Railroad - An Argument Against the Vertical Separation of Cloud Providers](http://highscalability.com/blog/2022/10/24/the-cloud-is-not-a-railroad-an-argument-against-the-vertical.html)
  — deux argumentaires très intéressants (et contradictoires) sur le _cloud business_.

## Découvertes

- [Shodan - Search Engine for the Internet of Everything](https://www.shodan.io/)
  — j'en avais entendu parlé plusieurs fois mais je n'avais jamais testé. C'est puissant !
- [badssl.com - Memorable site for testing clients against bad SSL configs](https://badssl.com/)
  — on n'en a pas besoin tous les jours, mais ça peut être très pratique.
- [Upscayl - Free and Open Source AI Image Upscaler](https://github.com/upscayl/upscayl)
  — pratique pour magnifier des photos dont la résolution est basse. Le résultat n'est pas magique, mais reste assez
  bluffant.
- [Legapass - Sécurisez la transmission de votre patrimoine numérique](https://legapass.com/)
  — mieux vaut y réfléchir plus tôt que tard.

That’s all folks !

<!-- prettier-ignore-start -->
*[AI]: Artificial Intelligence
*[API]: Application Programming Interface
*[APIs]: Application Programming Interfaces
*[CLI]: Command-Line Interface
*[DTO]: Data Transfer Object
*[DTOs]: Data Transfer Objects
*[GUAC]: Graph for Understanding Artifact Composition
*[HTTP]: Hypertext Transfer Protocol
*[JDK]: Java Development Kit
*[JIT]: Just-In-Time
*[LTS]: Long Term Support
*[npm]: Node Package Manager
*[RFC]: Request For Comments
*[SaaS]: Software as a Service
*[SBOM]: Software Bill Of Materials
*[SE]: Standard Edition
*[SLSA]: Supply chain Levels for Software Artifacts
*[SQL]: Structured Query Language
*[SSL]: Secure Sockets Layers
<!-- prettier-ignore-end -->
