---
layout: post
title: Liens en vrac — Juin 2022
category: liens
seo:
  date_modified: 2022-11-15
---

Nouvelles, articles, podcasts, vidéos et découvertes intéressantes du mois de juin 2022.

## Nouvelles

- [New Hertzbleed Side Channel Attack Affects All Modern AMD and Intel CPUs](https://thehackernews.com/2022/06/new-hertzbleed-side-channel-attack.html)
  — elle est étonnante cette nouvelle attaque !
- [Spring Data MongoDB SpEL Expression Injection Vulnerability (CVE-2022-22980)](https://spring.io/blog/2022/06/20/spring-data-mongodb-spel-expression-injection-vulnerability-cve-2022-22980)
  — pensez à vous mettre à jour si nécessaire.
- [JDK 7: The Long Hello and the Long Goodbye](https://www.azul.com/blog/jdk-7-the-long-hello-and-the-long-goodbye/)
  — Oracle met fin au support étendu du JDK 7 le 19/07/2022, néanmoins Azul prendra la relève (payant) jusqu’à au moins décembre 2027.
- [PostgreSQL 14.4 Released!](https://www.postgresql.org/about/news/postgresql-144-released-2470/)
  — cette version corrige [un problème de corruption d’indexes](https://www.postgresql.org/about/news/postgresql-14-out-of-cycle-release-coming-june-16-2022-2466/)
  introduit dans PostgreSQL 14. À noter qu’il y a aussi un problème avec
  [PostgreSQL 14 et les drivers Java et .NET](https://www.infoq.com/news/2022/06/PostgreSQL-14-Breaking-Change/)
  quand on utilise l’instruction `BEGIN ATOMIC ... END` dans des fonctions ou des procédures.
- [Bringing forward the End-of-Life Date for Node.js 16](https://nodejs.org/en/blog/announcements/nodejs16-eol/)
  — bon à savoir.
- [Ansible 6.0.0 has been released!](https://groups.google.com/g/ansible-announce/c/yprrt94l22w)
  — avec [ansible-core 2.13](https://github.com/ansible/ansible/blob/stable-2.13/changelogs/CHANGELOG-v2.13.rst),
  la nouvelle commande `ansible-community` et des mises à jour majeures de collections en pagaille.
- [Ansible 5.10.0 has been released!](https://groups.google.com/g/ansible-announce/c/7rnkSYhdjSY)
  — la dernière version dans la série des 5.x, pour ceux qui ne peuvent pas se mettre à jour en 6.0 tout de suite.
- [Hibernate 6.1 Final](https://in.relation.to/2022/06/14/orm-61-final/), [](https://in.relation.to/2022/06/24/hibernate-orm-61-features/)
  — cool, Hibernate supporte de plus en plus de _database types_ nativement.
- [Quarkus 2.10.0.Final released - Preliminary work on Loom’s virtual threads and various refinements all over the place](https://quarkus.io/blog/quarkus-2-10-0-final-released/)
  — l’équipe de Quarkus commence à expérimenter les
  _[virtual threads](https://blogs.oracle.com/javamagazine/post/going-inside-javas-project-loom-and-virtual-threads)_.
- [GitLab 15.1 released with SAML Group Sync and SLSA level 2 build artifact attestation](https://about.gitlab.com/releases/2022/06/22/gitlab-15-1-released/)
  — et pas mal de petites améliorations sympathiques.
- [Elasticsearch 8.3: Easily revive that old data archive](https://www.elastic.co/fr/blog/whats-new-elasticsearch-8-3-0)
  — bonne nouvelle, la quantité de ressources à réserver par shard a considérablement diminué (le guide,
  [Size your shards](https://www.elastic.co/guide/en/elasticsearch/reference/8.3/size-your-shards.html), a été mis à jour en conséquence).
- [Highlights from Git 2.37](https://github.blog/2022-06-27-highlights-from-git-2-37/)
  — beaucoup d’améliorations liées aux performances.
- [Vim 9.0 released](https://www.vim.org/vim90.php)
  — beaucoup de corrections et de petites améliorations, ainsi que l’ajout d’un nouveau langage de script, _Vim9 script_.
- [Almost there! Jakarta EE 10 is nearly ready, and the celebrations have already started!](https://blogs.eclipse.org/post/tanja-obradovic/almost-there-jakarta-ee-10-nearly-ready-and-celebrations-have-already-started)
  — c’est super de voir les choses bouger à nouveau côté _Java EE_. Pour un récapitulatif des nouveautés :
  [What’s new in Jakarta EE 10](http://www.mastertheboss.com/java-ee/jakarta-ee/whats-new-in-jakarta-ee-10/).
- [RFC 9114: Hypertext Transfer Protocol Version 3 (HTTP/3)](https://www.bortzmeyer.org/9114.html)
  — une nouvelle version de HTTP proche de HTTP/2, mais basée sur le protocole de transport [QUIC](https://www.bortzmeyer.org/quic.html).
- [AWS annonce Amazon CodeWhisperer (version préliminaire)](https://aws.amazon.com/fr/about-aws/whats-new/2022/06/aws-announces-amazon-codewhisperer-preview/)
  — Amazon vient concurrencer GitHub Copilot, [qui vient de passer en GA](https://github.blog/2022-06-21-github-copilot-is-generally-available-to-all-developers/).
- [Project Leyden Delays OpenJDK AOT Compiler, Optimizes JIT Compiler Instead](https://www.infoq.com/news/2022/06/project-leyden-delays-aot/)
  — quelques éclaircissements au sujet du projet Leyden.
- [Google Universal Analytics s’arrêtera le 1er juillet 2023](https://www.programmez.com/actualites/google-universal-analytics-sarretera-le-1er-juillet-2023-34179)
  — si vous avez créé votre propriété avant le 14 octobre 2020, vous êtes concernés, néanmoins…
- [Google Analytics et transferts de données : comment mettre son outil de mesure d’audience en conformité avec le RGPD ?](https://www.cnil.fr/fr/cookies-et-autres-traceurs/regles/google-analytics-et-transferts-de-donnees-comment-mettre-son-outil-de-mesure-daudience-en-conformite), [Questions-réponses sur les mises en demeure de la CNIL concernant l’utilisation de Google Analytics](https://www.cnil.fr/fr/cookies-et-autres-traceurs/regles/questions-reponses-sur-les-mises-en-demeure-de-la-cnil-concernant-lutilisation-de-google-analytics)
  — …il est temps de penser à migrer vers un autre outil.
- [How the German court’s ruling on Google Fonts affects jsDelivr and why it is safe to use](https://www.jsdelivr.com/blog/how-the-german-courts-ruling-on-google-fonts-affects-jsdelivr-and-why-it-is-safe-to-use/)
  — si vous avez la possibilité d’embarquer directement les dépendances hébergées hors-Europe dans votre site c’est plus sûr.
- [Broadcom to acquire VMware as IT growth transitions to containerisation](https://www.architecting.it/blog/broadcom-vmware/)
  — un éclairage intéressant sur le rachat de VMWare par Broadcom.

## Articles, podcasts et vidéos

- [Pourquoi un ministère du numérique ?](https://podcasts.google.com/feed/aHR0cHM6Ly9mZWVkcy5zb3VuZGNsb3VkLmNvbS91c2Vycy9zb3VuZGNsb3VkOnVzZXJzOjM5ODM4NTg1NS9zb3VuZHMucnNz/episode/dGFnOnNvdW5kY2xvdWQsMjAxMDp0cmFja3MvMTI4MjQ0MjMwOA?ep=14)
  — c’est toujours enthousiasmant d’entendre parler [Quentin Adam](https://www.waxzce.org/) de numérique (sujet en lien
  avec la tribune _[Pour un ministère du numérique de plein exercice](https://www.latribune.fr/opinions/tribunes/pour-un-ministere-du-numerique-de-plein-exercice-916582.html)_).
- [Et s’il fallait être conservateur pour innover et (vraiment) changer le monde ?](https://philippesilberzahn.com/2022/06/13/et-si-il-fallait-etre-conservateur-pour-innover-et-vraiment-changer-le-monde/)
  — je ne sais pas, mais c’est convaincant.
- [The Surprising Truth About Pixels and Accessibility](https://www.joshwcomeau.com/css/surprising-truth-about-pixels-and-accessibility/)
  — un excellent article sur `px`, `em` et `rem`.
- [Five Easy to Miss PostgreSQL Query Performance Bottlenecks](https://pawelurbanek.com/postgresql-query-bottleneck)
  — intéressant !
- [Replacing Finalizers with Cleaners](https://inside.java/2022/05/25/clean-cleaner/)
  — j’étais complètement passé à côté de cette fonctionnalité du JDK 9.
- [The best Spring Data JpaRepository](https://vladmihalcea.com/best-spring-data-jparepository/)
  — un _repository JPA_ permettant d’éviter le _save method anti-pattern_.
- [Lessons learned from modernising a lesser maintained (Spring Boot) service](https://www.jvt.me/posts/2022/05/12/modernise-spring-boot-lessons/)
  — un retour d’expérience intéressant à lire.
- [Logging Performance Comparison](https://blog.sebastian-daschner.com/entries/logging-performance-comparison)
  — journaliser a un coût non négligeable.
- [Hard things in Computer Science](https://blog.frankel.ch/hard-things-computer-science/)
  — c’est pas simple l’informatique !
- [Execution in the Kingdom of Nouns](https://steve-yegge.blogspot.com/2006/03/execution-in-kingdom-of-nouns.html)
  — amusant à lire.
- [On the Evilness of Feature Branching - The Problems](https://thinkinglabs.io/articles/2022/05/30/on-the-evilness-of-feature-branching-the-problems.html)
  — tl;dr : _Continuous Integration is really about exposing changes as quickly as possible to increase feedback._
- [Migrating Your Spring Boot Application to use Structured Logging](https://www.jvt.me/posts/2021/05/31/spring-boot-structured-logging/),
  [Use (End-to-End) Tracing or Correlation IDs](https://www.jvt.me/posts/2021/11/22/correlation-ids/),
  [Globally Logging all Spring (Boot) Exceptions](https://www.jvt.me/posts/2020/10/29/spring-log-all-exceptions/)
  — je viens de découvrir le blog de Jamie Tanna : quelques articles intéressants sur les logs.
- [jannie-louwrens/spring-boot-keycloak-angular](https://github.com/jannie-louwrens/spring-boot-keycloak-angular),
  [Articles, tutorials, guides and examples about Keycloak](https://www.thomasvitale.com/tag/keycloak/),
  [Sécurisez vos APIs Spring avec Keycloak : #5 – Mise en place d’une authentification multidomaines](https://blog.ineat-group.com/2018/11/securisez-vos-apis-spring-avec-keycloak-5-mise-en-place-dune-authentification-multi-domaines/),
  [Faking OAuth2 Single Sign-on in Spring, 3 Ways](https://tanzu.vmware.com/content/pivotal-engineering-journal/faking-oauth2-single-sign-on-in-spring-3-ways)
  — quelques "vieux" articles intéressants liés à Keycloak et à OAuth que je n’avais jamais publié sur ce blog.
- [Votre téléphone est sur écoute : vérifier et protéger son smartphone](https://blog.ostraca.fr/votre-telephone-est-sur-ecoute-verifier-et-proteger-son-smartphone/)
  — je ne connaissais pas tous ces codes : `*#21#`, `##002#`, `*#62#`, `*#06#`…
- [I won free load testing](https://fasterthanli.me/articles/i-won-free-load-testing)
  — ou comment faire face à une attaque DDoS.
- [Ctrl-Shift-U conflicts with applications shortcut](https://github.com/ibus/ibus/issues/1889)
  — si comme moi vous vous demandez pourquoi le raccourci Ctrl-Shift-U ne fonctionne plus sur Intellij IDEA,
  c’est peut-être à cause de IBus. Vous pouvez changer sa configuration grâce à la commande `ibus-setup`.
- [Reproducible Development with Devcontainers](https://www.infoq.com/articles/devcontainers/)
  — sans aller jusque-là, l’utilisation de conteneurs en développement simplifie pas mal de choses.
- [Optimisez votre outillage CLI avec direnv](https://blog.wescale.fr/optimiser-cli-avec-direnv/)
  — ça à l’air intéressant, à creuser.

## Découvertes

- [Pico.css](https://picocss.com/)
  — _Minimal CSS Framework for semantic HTML_.
- [javadoc.io](https://www.javadoc.io/)
  — _javadoc hosting for open source projects hosted on Central Maven_.
- [Password generator for BIOS](https://bios-pw.org/)
  — _Quick and easy way to recover BIOS passwords on laptops._
- [Spotless](https://github.com/diffplug/spotless)
  — une alternative ou un complément à [Prettier](https://prettier.io/).
- [formatter-maven-plugin](https://github.com/revelc/formatter-maven-plugin)
  — une alternative à [git-code-format-maven-plugin](https://github.com/Cosium/git-code-format-maven-plugin).

[That’s all folks](https://www.youtube.com/watch?v=brBAsOfxvkA "Elysian Fields - Passing On The Stairs"){:target="_blank"} !

<!-- prettier-ignore-start -->
*[AOT]: Ahead-Of-Time
*[AWS]: Amazon Web Services
*[BIOS]: Basic Input/Output System
*[CLI]: Command-Line Interface
*[CNIL]: Commission Nationale de l’Informatique et des Libertés
*[CPUs]: Central Processing Units
*[CSS]: Cascading Style Sheets
*[DDoS]: Distributed Denial of Service
*[EE]: Enterprise Edition
*[GA]: General Availability
*[HTML]: HyperText Markup Language
*[HTTP]: HyperText Transfer Protocol
*[HTTP/2]: HyperText Transfer Protocol, version 2
*[HTTP/3]: HyperText Transfer Protocol, version 3
*[IT]: Information Technology
*[JDK]: Java Development Kit
*[JPA]: Java Persistence API
*[JIT]: Just-in-Time
*[QUIC]: Quick UDP Internet Connections
*[RGPD]: Règlement Général sur la Protection des Données
*[SAML]: Security Assertion Markup Language
*[SLSA]: Supply-chain Levels for Software Artifacts
*[SpEL]: Spring Expression Language
*[tl;dr]: too long; didn’t read
<!-- prettier-ignore-end -->
