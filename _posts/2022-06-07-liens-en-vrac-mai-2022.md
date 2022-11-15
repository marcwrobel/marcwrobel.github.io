---
layout: post
title: Liens en vrac — Mai 2022
category: liens
seo:
  date_modified: 2022-11-15
---

Nouvelles, articles, podcasts, vidéos et découvertes intéressantes du mois de mai 2022.

## Nouvelles

- [Confluence Server and Data Center - CVE-2022-26134 - Critical severity unauthenticated remote code execution vulnerability](https://confluence.atlassian.com/doc/confluence-security-advisory-2022-06-02-1130377146.html),
  [Spring Security 5.7.0, 5.6.4, 5.5.7 Released - Fixes CVE-2022-22978 & CVE-2022-22976](https://spring.io/blog/2022/05/15/spring-security-5-7-0-5-6-4-5-5-7-released-fixes-cve-2022-22978-cve-2022-22976),
  [Spring Security OAuth reaches End-of-Life](https://spring.io/blog/2022/06/01/spring-security-oauth-reaches-end-of-life),
  [Ansible 2.9 is officially end of life](https://groups.google.com/g/ansible-announce/c/kegIH5_okmg/m/MNxt0oM1AwAJ?pli=1),
  [Debian 9 soon out of (free) security support](https://raphaelhertzog.com/2022/05/11/debian-9-soon-out-of-free-security-support/)
  — pensez à vous mettre à jour !
- [Spring Boot 2.7.0 available now](https://spring.io/blog/2022/05/19/spring-boot-2-7-0-available-now)
  — avec l’auto-configuration pour [Spring for GraphQL 1.0](https://spring.io/blog/2022/05/19/spring-for-graphql-1-0-release),
  le support de Podman pour la construction d’image Docker et une myriade d’autres choses.
- [Angular v14 is now available!](https://blog.angular.io/angular-v14-is-now-available-391a6db736af)
  — avec entre autre le support des _Strictly typed forms_ et des _Standalone components_ (en expérimental), comme
  d’habitude Ninja Squad [nous résume tout ça avec brio](https://blog.ninja-squad.com/2022/06/02/what-is-new-angular-14.0/).
  L’équipe Angular nous partage aussi [sa vision sur le futur d’Angular](https://blog.angular.io/angulars-vision-for-the-future-3cfca5e7b448).
- [Announcing the GA release of Red Hat Enterprise Linux 9.0](https://access.redhat.com/announcements/6958409)
  — j’ai découvert à cette occasion l’existence d’AlmaLinux, une alternative gratuite à RHEL
  [dont la version 9.0 est aussi déjà sortie](https://www.phoronix.com/scan.php?page=news_item&px=AlmaLinux-9.0-Released).
- [New releases: ansible-core 2.13.0 - Nobody’s Fault but Mine](https://groups.google.com/g/ansible-announce/c/AEjCH6lMkZ0)
  — Python 2.6 n’est plus supporté, cette version sera intégrée à Ansible 6.0.0.
- [Ansible 5.8.0 has been released](https://groups.google.com/g/ansible-announce/c/pT_VuSf9uS4),
  [Ansible 5.9.0 has been released](https://groups.google.com/g/ansible-announce/c/0VB8THGeG2w)
  — le support d’Ansible 2.9 et d’ansible-base 2.10 commence à être retiré des diverses collections.
- [PostgreSQL 14.3, 13.7, 12.11, 11.16, and 10.21 Released!](https://www.postgresql.org/about/news/postgresql-143-137-1211-1116-and-1021-released-2449/)
  — attention, [cette mise à jour n’est pas complètement transparente](https://jkatz05.com/post/postgres/may-2022-release-should-i-update/). L’équipe rappelle que PostgreSQL 10 arrivera en fin de vie le 10/11/2022.
- [GitLab 15.0 released with WYSIWYG for Wiki, container scanning in all tiers](https://about.gitlab.com/releases/2022/05/22/gitlab-15-0-released/)
  — au menu : amélioration de l’éditeur WYSIWYG (qui devrait encore s’améliorer
  [avec l’intégration de Visual Studio Code](https://about.gitlab.com/blog/2022/05/23/the-future-of-the-gitlab-web-ide/)),
  intégration de fonctionnalités de CRM, mise à disposition en gratuit de fonctionnalités basiques de scan de conteneurs,
  support des secrets de type _fichier binaire_ (beta), promotion de Semgrep pour le SAST…
- [Project Leyden: Beginnings](https://openjdk.java.net/projects/leyden/notes/01-beginnings)
  — Mark Reinhold propose l’introduction d’_images statiques_ dans le but d’améliorer les performances de démarrage
  ainsi que l’empreinte des applications Java.
- [Broadcom Announces Plan To Acquire VMware For $61 Billion USD](https://www.phoronix.com/scan.php?page=news_item&px=Broadcom-VMware-Acquisition)
  — il est un peu tôt pour en dire quoique ce soit, notamment quant à l’impact sur Spring.
- [NVIDIA Transitioning To Official, Open-Source Linux GPU Kernel Driver](https://www.phoronix.com/scan.php?page=article&item=nvidia-open-kernel&num=1)
  — il n’est jamais trop tard pour s’y mettre !
- [Open Source Software Security: Turning Sand into Concrete](https://linuxfoundation.org/blog/open-source-software-security-turning-sand-into-concrete/)
  — la _Linux Foundation_ et l’_Open Source Security Foundation_ ont présenté
  l’_[Open Source Software Security Mobilization Plan](https://openssf.org/oss-security-mobilization-plan/)_
  en réaction aux récentes et nombreuses _software supply chain attack_,
  au passage Google a annoncé la formation de son _[Open Source Maintenance Crew](https://blog.google/technology/safety-security/shared-success-in-building-a-safer-open-source-community/)_.
- [Here’s a New Tool That Scans Open-Source Repositories for Malicious Packages](https://thehackernews.com/2022/05/heres-new-tool-that-scans-for-malicious.html)
  — ça tombe bien, [ce type d’attaque](https://thehackernews.com/2022/05/malicious-npm-packages-target-german.html) est
  [de plus en plus courant](https://snyk.io/blog/snyk-200-malicious-npm-packages-cobalt-strike-dependency-confusion-attacks/).
- [Google cloud ouvre sa région France ce 30 juin](https://www.lemondeinformatique.fr/actualites/lire-google-cloud-ouvre-sa-region-france-ce-30-juin-86815.html)
  — AWS, Azure et GCP ont désormais tous une région en France.
- [The Magic of Docker Desktop is Now Available on Linux](https://www.docker.com/blog/the-magic-of-docker-desktop-is-now-available-on-linux/)
  — à tester pour voir si ça a un intérêt suffisant sous Linux.
- [Enquête Codingame & Coderpad Sur Le Recrutement Tech En 2022](https://www.codingame.com/work/fr/codingame-coderpad-tech-hiring-survey-2022/)
  — toujours intéressant à lire.
- [Before You Hit ’Submit’, This Company Has Already Logged Your Personal Data](https://gizmodo.com/before-you-hit-submit-this-company-has-already-logge-1795906081)
  — c’est moche comme pratique !

## Articles, podcasts et vidéos

- [JEP draft: String Templates (Preview)](https://openjdk.java.net/jeps/8273943)
  — ça discute (enfin !) d’interpolation de chaînes en Java, en attendant il y a :
  [Java: Text Blocks + String#formatted = JSON](https://adambien.blog/roller/abien/entry/java_text_blocks_string_formatted),
  [Groovy](https://groovy-lang.org/syntax.html#_string_interpolation),
  [Kotlin](https://kotlinlang.org/docs/idioms.html#string-interpolation)...
- [@Incubating features in Hibernate 6](https://thorben-janssen.com/incubating-features-in-hibernate-6/)
  — la liste des fonctionnalités en cours d’incubation dans Hibernate 6.
- [Keycloak.X, but secure – without vulnerable libraries](https://blog.codecentric.de/en/2022/05/keycloak-x-but-secure-without-vulnerable-libraries/)
  — un peu lourd à maintenir, mais efficace !
- [API Tokens: A Tedious Survey](https://fly.io/blog/api-tokens-a-tedious-survey/)
  — intéressant, notamment [Biscuit](https://www.nolimitsecu.fr/biscuit/).
- [ZFS 101—Understanding ZFS storage and performance](https://arstechnica.com/information-technology/2020/05/zfs-101-understanding-zfs-storage-and-performance/)
  — un article bien foutu sur ZFS.
- [Btrfs : révolution ou catastrophe ? Où en est-on aujourd’hui ?](https://blog.flozz.fr/2022/05/22/btrfs-revolution-ou-catastrophe-ou-en-est-on-aujourdhui/)
  — finalement ça vaut peut-être le coup de tester ?
- [5 benefits of switching from Google Analytics to Plausible](https://opensource.com/article/22/5/plausible-analytics)
  — si vous cherchiez une alternative à Google Analytics (payante en SaaS, gratuite si vous l’hébergez).
- [Using CSS variables in Bootstrap](https://blog.getbootstrap.com/2022/05/16/using-bootstrap-css-vars/)
  — une bonne introduction aux CSS variables, dans un contexte Bootstrap.
- [Ansible: variable interpolation in task name](https://stackoverflow.com/q/29001505)
  — tl;dr : _Variables are not resolved inside the name_ (à part peut-être les variables qui ne varient pas en fonction
  de l’hôte).
- [Constraint Composition with Bean Validation](https://www.baeldung.com/java-bean-validation-constraint-composition)
  — je ne connaissais ni `@ReportAsSingleViolation`, ni `@ConstraintComposition`.
- [The Case Against Logging](https://blog.sebastian-daschner.com/entries/the-case-against-logging)
  — une opinion bien argumentée et un peu différente de ce qu’on entend d’habitude sur les logs, notamment dans un
  contexte _cloud-native_.
- [Common DB schema change mistakes](https://postgres.ai/blog/20220525-common-db-schema-change-mistakes)
  — de bons conseils et un lien sympa : [GitLab’s Migration Style Guide](https://docs.gitlab.com/ee/development/migration_style_guide.html).
- [Preparing for Spring Boot 3.0](https://spring.io/blog/2022/05/24/preparing-for-spring-boot-3-0)
  — tl;dr : passez à Spring Boot 2.7 / Java 17 et jetez un coup d’œil aux dépendances qui ne sont pas gérées par
  Spring Boot.

## Découvertes

- [Lissy93/personal-security-checklist](https://github.com/Lissy93/personal-security-checklist)
  — _A curated checklist of tips to protect your digital security and privacy_ : ça va être long à lire !
- [Open Source Insights](https://opensource.googleblog.com/2021/06/introducing-open-source-insights-project.html)
  — j’ai un peu de boulot sur [jbanking](https://deps.dev/maven/fr.marcwrobel%3Ajbanking).
- [pgmetrics](https://pgmetrics.io/)
  — _Easily collect and report PostgreSQL metrics for scripting, automation and troubleshooting_.
- [PostgreSQL Anonymizer 1.0](https://www.postgresql.org/about/news/postgresql-anonymizer-10-privacy-by-design-for-postgres-2452/)
  — une extension PostgreSQL permettant d’anonymiser une base de données en déclarant des transformations sur les
  colonnes sensibles (PII).

[That’s all folks](https://www.youtube.com/watch?v=L4XTJao2iLA "Joe Hisaishi - Studio Ghibli 25 Years Concert"){:target="_blank"} !

<!-- prettier-ignore-start -->
*[API]: Application Programming Interface
*[AWS]: Amazon Web Services
*[Btrfs]: B-tree file system
*[CRM]: Customer Relationship Management
*[CSS]: Cascading Style Sheets
*[GA]: General Availability
*[GCP]: Google Cloud Platform
*[IDE]: Integrated Development Environment
*[JEP]: Java Enhancement Proposal
*[JDK]: Java Development Kit
*[JSON]: JavaScript Object Notation
*[npm]: Node Package Manager
*[NPM]: Node Package Manager
*[PII]: Personally Identifiable Information
*[RHEL]: Red Hat Enterprise Linux
*[SAST]: Static Application Security Testing
*[tl;dr]: too long; didn’t read
*[USD]: United States dollar
*[WYSIWYG]: What You See Is What You Get
*[ZFS]: Z File System
<!-- prettier-ignore-end -->
