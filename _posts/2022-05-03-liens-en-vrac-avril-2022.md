---
layout: post
title: Liens en vrac — Avril 2022
category: liens
youtube_video_id: 3wDw-W9S0j4
youtube_video_title: Russian Circles - Quartered
---

## Nouvelles

- [Java Cryptography Implementation Mistake Allows Digital-Signature Forgeries](https://www.schneier.com/blog/archives/2022/04/java-cryptography-implementation-mistake-allows-digital-signature-forgeries.html)
  , [Spring4Shell extends to Glassfish and Payara: same vulnerability, new exploit](https://snyk.io/blog/spring4shell-rce-vulnerability-glassfish-payara/)
  — pensez à vous mettre à jour.
- [2022 State of the Java Ecosystem Report](https://newrelic.com/resources/report/2022-state-of-java-ecosystem)
  — Java 11 passe enfin devant Java 8 en terme d'utilisation constatée par New Relic.
- [IntelliJ IDEA 2022.1 Is Out](https://blog.jetbrains.com/idea/2022/04/intellij-idea-2022-1/)
  — si vous avez la version _ultimate_, vous aurez désormais
  [des alertes de sécurité](https://blog.jetbrains.com/idea/2022/04/ensure-greater-software-security-with-package-analysis-by-checkmarx-in-intellij-idea/)
  sur vos dépendances Maven et Gradle.
- [OpenSSH 9.0 Released With Hardening Against Future Quantum Computers](https://www.openssh.com/releasenotes.html#9.0)
  — entre autres : `scp` utilise désormais le protocole SFTP par défaut, ajout du nouvel algorithme
  [post-quantique](https://www.ssi.gouv.fr/publication/migration-vers-la-cryptographie-post-quantique/) de
  _Key Exchange_ [`sntrup761x25519-sha512@openssh.com`](https://eric-diehl.com/openssh-prepares-post-quantum/).
- [Canonical Ubuntu 22.04 LTS is released](https://ubuntu.com/blog/ubuntu-22-04-lts-released)
  — cette version sera supportée pendant 10 ans.
- [Keycloak 18.0.0 released](https://www.keycloak.org/2022/04/keycloak-1800-released)
  — avec plein de nouvelles choses !
- [GitLab 14.10 released with individual compliance violation reporting and a UI for streaming audit events](https://about.gitlab.com/releases/2022/04/22/gitlab-14-10-released/)
  — comme d’habitude il y a beaucoup de nouveautés, mais rien qui ne m’ait tapé dans l’œil ce mois-ci.
- [Node.js 18 is now available!](https://nodejs.org/en/blog/announcements/v18-release-announce/)
  — les débuts de la future LTS (et donc la fin de Node.js 12).
- [Ansible 5.6.0 has been released](https://groups.google.com/g/ansible-announce/c/hbjjROVq5dA),
  [Ansible 5.7.0 has been released](https://groups.google.com/g/ansible-announce/c/-HctLPdjWaM)
  — R.A.S.
- [Debian To Consider Changing How It Treats Closed-Source Firmware](https://www.phoronix.com/scan.php?page=news_item&px=Debian-Considering-Firmware)
  — en attendant, il y a l’image [unofficial non-free images including firmware
  packages](https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/).
- [Waiting for PostgreSQL 15 – JSON_TABLE](https://www.depesz.com/2022/04/06/waiting-for-postgresql-15-json_table/)
  — j'ai hâte !
- [Oracle JRE and JDK Cryptographic Roadmap](https://www.java.com/en/jre-jdk-cryptoroadmap.html)
  — ça vaut toujours le coup d’y jeter un coup d’œil.

## Articles, podcasts et vidéos

- [Pimp Up Your Resume](https://www.yegor256.com/2016/03/08/pimp-up-your-resume.html)
  — un vieil article qui va m’être utile prochainement ;) !
- [Beautify your GitHub repo](https://blog.frankel.ch/beautify-github-repo/)
  — je ne connaissais
  ni [`SECURITY`](https://docs.github.com/en/code-security/getting-started/adding-a-security-policy-to-your-repository)
  ni [`CITATION`](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files)
  .
- [Spring Security – Map Authorities from JWT](https://www.baeldung.com/spring-security-map-authorities-jwt)
  — un article riche sur le sujet, à compléter avec [Spring Boot security expressions for Auth0
  JWT](https://www.ivarprudnikov.com/spring-boot-security-expressions-for-auth0-jwt/).
- [Which Kinds of Tests Should I Write?](https://blog.thecodewhisperer.com/permalink/which-kinds-of-tests-should-i-write)
  — un avis clair et concis que je partage.
- [Valider des données avec Vavr](https://blog.ippon.fr/2022/04/15/valider-des-donnees-avec-vavr/)
  — une alternative sympathique à `javax.validation`.
- [Java into Containers, A Match Made in Heaven?](https://inside.java/2022/04/06/java-in-containers/)
  — un bon résumé des choses qu’il faut connaitre lorsque vous conteneurisez vos applications Java.
- [Deux techniques de base pour le code Legacy](https://blog.octo.com/deux-techniques-de-base-pour-le-code-legacy/)
  — une explication des _Sprout Method_ et _Wrap Method_.
- [The 2022 Java Developer RoadMap](https://javarevisited.blogspot.com/2019/10/the-java-developer-roadmap.html)
  — une [_mind map_](https://en.wikipedia.org/wiki/Mind_map) qui aide à se guider dans son apprentissage de Java.
- [Ma boite à outils DevOps (édition 2021)](https://www.damyr.fr/posts/boite-a-outil-devops-2021/)
  — plein de petits outils sympas, et en bonus des astuces pour simplifier les changements de contexte (projet ou
  client).
- [Tag All The Things](https://www.databasesoup.com/2015/01/tag-all-things-part-3.html)
  — une vieille série d’articles sur les tags et PostgreSQL.
- [Deduction-Based Polymorphism in Jackson 2.12](https://www.baeldung.com/jackson-deduction-based-polymorphism)
  — ça à l’air puissant ce `@JsonTypeInfo(use = Id.DEDUCTION)`.
- [Strictly typed forms in Angular](https://blog.ninja-squad.com/2022/04/21/strictly-typed-forms-angular/)
  — cette nouvelle fonctionnalité arrivera dans Angular 14.
- [One Email Rule - Have a separate Inbox and an Inbox CC to reduce email stress. Guaranteed.](https://www.hanselman.com/blog/one-email-rule-have-a-separate-inbox-and-an-inbox-cc-to-reduce-email-stress-guaranteed)
  — pas bête !
- [Chopping the monolith](https://blog.frankel.ch/chopping-monolith/)
  — tl;dr : _Microservices, as presented in conferences, are doomed to fail in most organizations. Because it’s hard to
  know all parts before the first deployment, it makes sense to start with a simple monolith_.
- [How To Avoid Anti-Patterns In Cypress](https://www.javacodegeeks.com/2022/04/how-to-avoid-anti-patterns-in-cypress.html)
  — quelques petites choses à éviter lorsqu’on utilise Cypress (ou d’autres frameworks de tests similaires).

## Découvertes

- [Lightrun – the best way to debug production problems](https://vladmihalcea.com/lightrun-debug-production-problems/)
  — tout est dans le titre.
- [Deep dive on Ansible VScode extension](https://www.ansible.com/blog/deep-dive-on-ansible-vscode-extension)
  — à tester dès que possible !
- [delta](https://github.com/dandavison/delta)
  — _A syntax-highlighting pager for git, diff, and grep output_.
- [crt.sh](https://crt.sh/?q=www.marcwrobel.fr)
  — une re-découverte : très pratique pour monitorer ou, plus simplement, visualiser vos certificats.

That’s all folks !

<!-- prettier-ignore-start -->
*[JDK]: Java Development Kit
*[JRE]: Java Runtime Environment
*[JWT]: JSON Web Token
*[LTS]: Long Term Support
*[R.A.S.]: Rien À Signaler
*[SFTP]: Ssh File Transfer Protocol
*[tl;dr]: too long; didn’t read
*[UI]: User Interface
<!-- prettier-ignore-end -->
