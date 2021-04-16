---
layout: post
title: Liens en vrac - Juillet 2019
category: liens
tags: debian elastic ansible sonarqube java jakarta jee rest coverage postgresql brin spring-data bash trivy pg_qualstat plantuml sécurité json docker rest microservices
---

## News
* [Debian 10 "buster" released](https://www.debian.org/News/2019/20190706)
  — parmi les nombreuses nouveautés : mise à jour de GNOME en 3.30 / Linux kernel en 4.19 / OpenJDK
    en 11 / PostgreSQL en 11, AppArmor est maintenant activé par défaut, `nftables` remplace
    `iptables`, support de secure-boot.
* [Debian buster: changes in util-linux](https://michael-prokop.at/blog/2019/07/26/debian-buster-changes-in-util-linux-newinbuster/),
  [Debian buster: changes in coreutils](https://michael-prokop.at/blog/2019/07/26/debian-buster-changes-in-coreutils-newinbuster/)
  — des comptes-rendus bien sympathiques sur ces paquets essentiels.
* [Lancement de la Suite Elastic 7.3.0](https://www.elastic.co/fr/blog/elastic-stack-7-3-0-released)
  — _data frames_, détection des anomalies dans Elastic SIEM, Elastic Maps en GA et plus encore…
* [Thoughts on Restructuring the Ansible Project](https://www.ansible.com/blog/thoughts-on-restructuring-the-ansible-project)
  — de gros changements en perspective sur le projet Ansible.
* [The Definitive Guide to SonarQube 7.9 LTS](https://www.sonarqube.org/sonarqube-7-9-lts/)
  — SonarQube 7.9 LTS vient de sortir.
* [Java EE Specifications Renamed Jakarta EE](https://www.infoq.com/news/2019/07/javaee-specs-renamed-jakarta/)
  — et `javax` devint `jakarta`.

## Articles
* [80 ou 90% de couverture de tests pour un nouveau projet?](https://blog.ippon.fr/2019/07/22/80-ou-90-de-couverture-de-tests/)
  — la couverture de test est un indicateur, pas un objectif.
* [Tips for Upgrading to, And Securing, Debian Buster](https://changelog.complete.org/archives/9999-tips-for-upgrading-to-and-securing-debian-buster)
  — toujours bon à savoir.
* [BRIN Index for PostgreSQL: Don’t Forget the Benefits](https://www.percona.com/blog/2019/07/16/brin-index-for-postgresql-dont-forget-the-benefits/)
  — à regarder de toute urgence pour ceux qui utilisent PostgreSQL et qui ne connaissent pas ce type
    d’indexe.
* [How to (unit) test Spring Data repositories?](https://stackoverflow.com/questions/23435937/how-to-test-spring-data-repositories)
  — tl;dr : n’écrivez pas de tests unitaires sur des repositories Spring Data, cela n’a pas de sens.
* [How to write idempotent Bash scripts](https://arslan.io/2019/07/03/how-to-write-idempotent-bash-scripts/)
  — comment écrire des scripts bash plus robustes.
* [Discovering RESTful Web Microservices: A Traveler's Guide](https://www.youtube.com/watch?v=JJAWxtVeElc)
  — une présentation très intéressant sur les microservices, REST et le WWW.

## Découvertes
* [Avec Trivy, c’est trivial d’identifier les vulnérabilités de vos conteneurs](https://blog.octo.com/avec-trivy-cest-trivial-didentifier-les-vulnerabilites-de-vos-conteneurs/)
  — s’intègre bien dans une CI pour réaliser l’analyse des vulnérabilités de vos conteneurs.
* [Automatic Index Recommendations in PostgreSQL using pg_qualstats and hypopg](https://www.percona.com/blog/2019/07/22/automatic-index-recommendations-in-postgresql-using-pg_qualstats-and-hypopg/)
  — à tester !
* [Real World PlantUML](https://real-world-plantuml.com/)
  — de nombreux exemples d’utilisation de PlantUML.
* [Starting Up Security](https://scrty.io/)
  — guides for the growing security team.
* [A data templating language for app and tool developers](https://jsonnet.org)
  — semble intéressant, même si je n’ai pas encore l’occasion de tester.
* [A tool for exploring each layer in a docker image](https://github.com/wagoodman/dive)
  — ne manque plus que l’`alias dive='docker run --rm -it -v /var/run/docker.sock:/var/run/docker.sock
    wagoodman/dive:latest’` et c’est parti !

That’s all folks !

*[BRIN]: Block Range INdex
*[CI]: Continuous Integration
*[GA]: General Availability
*[JDK]: Java Development Kit
*[LTS]: Long Term Support
*[REST]: REpresentational State Transfer
*[SIEM]: Security Information Management System
*[tl;dr]: too long; didn’t read
*[UML]: Unified Modeling Language
*[WWW]: World Wide Web
