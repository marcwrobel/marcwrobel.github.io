---
layout: post
title: Liens en vrac — Février 2022
category: liens
youtube_video_id: k5yaCHEyxMo
youtube_video_title: The Districts - Young Blood
---

## Nouvelles

- [GitLab 14.8 released with new SSH key types and security approval policies](https://about.gitlab.com/releases/2022/02/22/gitlab-14-8-released/)
  — GitLab supporte désormais les clés SSH ecdsa-sk et ed25519-sk, plus qu’à tester !
- [Release notes for Groovy 4.0](https://groovy-lang.org/releasenotes/groovy-4.0.html)
  — avec le support des _switch expressions_ et des _sealed types_ : attention il faut désormais utiliser le groupId
  `org.apache.groovy` à la place de `org.codehaus.groovy`.
- [Keycloak 17.0.0 released](https://www.keycloak.org/2022/02/keycloak-1700-released)
  — Quarkus remplace désormais WildFly par défaut et la distribution Wildfly sera dépréciée fin juin 2022, pour info
  [certains _adapters_ seront aussi dépréciés fin décembre 2022](https://www.keycloak.org/2022/02/adapter-deprecation).
- [Elastic 8.0: A new era of speed, scale, relevance, and simplicity](https://www.elastic.co/blog/whats-new-elastic-8-0-0)
  — la version 6.x n’est désormais plus du tout supportée.
- [What’s new in Angular 13.2?](https://blog.ninja-squad.com/2022/01/27/what-is-new-angular-13.2/)
  — quelques petites améliorations intéressantes.
- [Schrems II - Quelles conséquences si vous utilisez Google Analytics & Co. en 2022 ?](https://blog.ostraca.fr/schrems-ii-quels-consequences-si-vous-utilisez-google-analytics-and-co.-en-2022/)
  ,
  [German Court Rules Websites Embedding Google Fonts Violates GDPR](https://thehackernews.com/2022/01/german-court-rules-websites-embedding.html)
  — l’utilisation de Google Analytics (ou des polices de caractères Google) sans consentement viole le RGPD (depuis
  2020 !?).
- [Breaking 256-bit Elliptic Curve Encryption with a Quantum Computer](https://www.schneier.com/blog/archives/2022/02/breaking-245-bit-elliptic-curve-encryption-with-a-quantum-computer.html)
  — c’est pas demain la veille !
- [The Angular Mini-Book 2.0](https://www.infoq.com/minibooks/angular-mini-book-v2/)
  — Le livre a été mis à jour pour Angular 13 et Spring Boot 2.6.
- [Include diagrams in your Markdown files with Mermaid](https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/)
  — après GitLab et Azure Devops, c’est au tour de GitHub.
- [JEP draft: Sequenced Collections](https://openjdk.java.net/jeps/8280836)
  — c’est tout bête, mais ça serait bien pratique.

## Articles, podcasts et vidéos

- [LCC 272 - Interview sur Log4Shell avec this](https://lescastcodeurs.com/2022/02/12/lcc-272-interview-sur-log4shell-avec-this/)
  — un très bon retour à froid sur Log4Shell.
- [System Logger](https://blog.frankel.ch/system-logger/)
  — j’étais passé à côté, que dire à part _encore un framework de logs_ !
- [Regular Expressions With Java’s Text Blocks / Multiline Strings](https://adambien.blog/roller/abien/entry/regular_expressions_with_java_s)
  — tl;dr : `Pattern.DOTALL`.
- [The best way to use the Spring Transactional annotation](https://vladmihalcea.com/spring-transactional-annotation/)
  — en
  complément : [Spring Data — Never Rollback Readonly Transactions](https://dev.to/kirekov/spring-never-rollback-readonly-transactions-28kb)
  .
- [The best way to handle time zones in a Java web application](https://vladmihalcea.com/time-zones-java-web-application/)
  — tl;dr : _use UTC as much as possible_.
- [#113 – Froggit : un SaaS Git souverain avec Christophe Chaudier](https://www.youtube.com/watch?v=oSKvAGG5bJY)
  — je me laisserai peut-être tenter par [Froggit](https://froggit.fr/).
- [Jakarta EE8, EE9, EE9.1. …. What???](https://ralph.blog.imixs.com/2022/01/17/jakarta-ee8-ee9-ee9-1-what/)
  — tl;dr: Jakarta EE 8 - juste un changement de nom, Jakarta EE 9/9.1 - des versions intermédiaires pour les outils et
  librairies pour préparer la migration `javax.*` ⇾ `jakarta.*`, Jakarta EE 10 - première version ou la
  migration `javax.*` ⇾ `jakarta.*` devient possible pour les applications clientes.
- [Aurore Stéphant : L’effondrement, le point critique ?](https://www.thinkerview.com/aurore-stephant-leffondrement-le-point-critique/)
  — long, putaclic, mais très intéressant !
- [How to encrypt and decrypt JSON properties with JPA](https://vladmihalcea.com/encrypt-decrypt-json-jpa/)
  — à garder sous le coude.
- [10 habits of great Ansible users](https://www.redhat.com/sysadmin/10-great-ansible-practices)
  — un bon rappel.
- [A Hairy PostgreSQL Incident](https://ardentperf.com/2022/02/10/a-hairy-postgresql-incident/)
  — je n’ai pas compris grand-chose, mais le REX est intéressant à lire.
- [Can you get pwned with CSS?](https://scotthelme.co.uk/can-you-get-pwned-with-css/)
  — tl;dr: _Based on my own experience, I’ve never seen an attack that leveraged the injection of CSS to cause harm._.
- [The Ultimate Guide on Client-Generated IDs in JPA Entities](https://www.jpa-buddy.com/blog/the-ultimate-guide-on-client/)
  — un article complet sur le sujet.
- [The Flatten Maven plugin](https://blog.frankel.ch/maven-flatten-plugin/)
  — ou comment construire un [_consumer POM_](https://cwiki.apache.org/confluence/display/MAVEN/Build+vs+Consumer+POM)
  sans Maven 5.

## Découvertes

- [reload4j](https://reload4j.qos.ch/news.html)
  — très utile si vous n’avez pas la possibilité de migrer vers Log4j 2.x (ou autre chose).
- [Most common Bash date commands for timestamping](https://zxq9.com/archives/795)
  — si vous en avez marre des `man date`.
- [ShedLock : l’allié de choix pour vos tâches planifiées Spring](https://blog.ippon.fr/2022/02/28/shedlock-lallie-de-choix-pour-vos-taches-planifiees-spring/)
  — ça m’a l’air tout à fait sympa !

That’s all folks !

<!-- prettier-ignore-start -->
*[CSS]: Cascading Style Sheets
*[ecdsa-sk]: Elliptic Curve Digital Signature Algorithm - Security Key
*[ed25519-sk]: Edwards-curve Digital Signature Algorithm - Security Key (SHA-512 / Curve25519)
*[EE]: Enterprise Edition
*[GDPR]: General Data Protection Regulation
*[IDs]: Identifiers
*[JEP]: JDK Enhancement-Proposal
*[JPA]: Java Persistence API
*[LCC]: Les Cast Codeurs
*[POM]: Project Object Model
*[RGPD]: Règlement Général sur la Protection des Données
*[REX]: Retour d’Expérience
*[SSH]: Secure SHell
*[tl;dr]: too long; didn’t read
*[UTC]: Universal Time Coordinated
<!-- prettier-ignore-end -->
