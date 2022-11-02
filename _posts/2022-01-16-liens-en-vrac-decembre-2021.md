---
layout: post
title: Liens en vrac — Décembre 2021
category: liens
---

## Nouvelles

- [Log4Shell](https://github.com/snyk-labs/awesome-log4shell)
  — Apache Log4j 2 bénéficie d’une _code review_ sans précédent !
- [Log4j 2 Vulnerability and Spring Boot](https://spring.io/blog/2021/12/10/log4j2-vulnerability-and-spring-boot)
  — mais par chance Spring Boot utilise logback par défaut (qui a néanmoins aussi dû
  [prendre des mesures pour renforcer sa sécurité](http://mailman.qos.ch/pipermail/announce/2021/000165.html)).
- [Keycloak 16.0.0 released](https://www.keycloak.org/2021/12/keycloak-1600-released),
  [Keycloak 16.1.0 released](https://www.keycloak.org/2021/12/keycloak-1610-released),
  [Keycloak 15.1.0 released](https://www.keycloak.org/2021/12/keycloak-1510-released.html) et
  [Keycloak 15.1.1 released](https://www.keycloak.org/2021/12/keycloak-1511-released)
  — des mises à jour plutôt techniques (WildFly, Quarkus), mais aussi
  [une vulnérabilité importante](https://www.keycloak.org/2021/12/cve) corrigée.
- [Windows Terminal as your Default Command Line Experience](https://devblogs.microsoft.com/commandline/windows-terminal-as-your-default-command-line-experience/)
  et
  [Microsoft rolls out Notepad with dark mode for Windows 11 Insiders](https://www.theverge.com/2021/12/7/22822651/microsoft-windows-11-notepad-redesign-find-replace-insider)
  — Microsoft se décide enfin à moderniser ses vieux trucs !
- [This Year in Spring - December 28th, 2021](https://spring.io/blog/2021/12/28/this-year-in-spring-december-28th-2021)
  — rétrospective 2021 sur l'écosystème Spring par [Josh Long](https://twitter.com/starbuxman).
- [From Maven 3 to Maven 5](https://www.javaadvent.com/2021/12/from-maven-3-to-maven-5.html)
  — bientôt du neuf sur Maven on dirait !?

## Articles, podcasts et vidéos

- [The Best Spring Data JPA Logging Configuration in Spring Boot](https://thorben-janssen.com/spring-data-jpa-logging/)
  et [The best way to log SQL statements with Spring Boot](https://vladmihalcea.com/log-sql-spring-boot/)
  — +1 pour [spring-boot-data-source-decorator](https://github.com/gavlyukovskiy/spring-boot-data-source-decorator) !
- [Spring Data Mock DAO](https://www.javacodegeeks.com/2021/12/spring-data-mock-dao.html)
  — à garder sous le coude, ça peut effectivement servir dans quelques cas.
- [La CNIL publie une nouvelle version de son guide RGPD pour les développeurs](https://www.cnil.fr/fr/la-cnil-publie-une-nouvelle-version-de-son-guide-rgpd-pour-les-developpeurs)
  — une bonne initiative de la CNIL.
- [Five Tips For a Healthier Postgres Database in the New Year](https://blog.crunchydata.com/blog/five-tips-for-a-healthier-postgres-database-in-the-new-year)
  — quelques petites astuces PostgreSQL à garder en tête.
- [My Custom CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/),
  [Defensive CSS](https://ishadeed.com/article/defensive-css/)
  — intéressant !
- [Anti-Patterns when building container images](https://jpetazzo.github.io/2021/11/30/docker-build-container-images-antipatterns/)
  — quelques trucs, astuces et recommandations sur la construction d’images Docker.
- [My Backup Plan](https://www.jeffgeerling.com/blog/2021/my-backup-plan)
  — le [_3-2-1 backup plan_](https://en.wikipedia.org/wiki/Backup#3-2-1_rule) : 3 copies des données, sur 2 supports
  différents, avec 1 copie hors-ligne.
- [Composition over inheritance: Gradle vs Maven](https://melix.github.io/blog/2021/12/composition-in-gradle.html)
  — une explication intéressante sur les différences de philosophie entre Gradle et Maven.
- [CSP: report-uri deprecation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy/report-uri)
  — la directive `Content-Security-Policy` `report-uri` va être dépréciée au profit de
  [`report-to`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy/report-to).

## Découvertes

- [spring-boot-data-source-decorator](https://github.com/gavlyukovskiy/spring-boot-data-source-decorator)
  — _Spring Boot integration with p6spy, datasource-proxy, flexy-pool and spring-cloud-sleuth_.
- [Semgrep](https://semgrep.dev/)
  — _static analysis at ludicrous speed : find bugs and enforce code standards_.
- [Useful sed](https://github.com/adrianscheff/useful-sed)
  — _useful sed tips, techniques and tricks for daily usage_.
- [Grok Debugger](https://grokdebug.herokuapp.com/)
  — très pratique pour déboguer les expressions Logstash.
- [CVE.report](https://cve.report)
  — beaucoup plus sympa à lire que [cve.mitre.org](https://cve.mitre.org/).

[That’s all folks](https://www.youtube.com/watch?v=zzE-kVadtNw "Vivaldi - Quattro Stagioni - Janine Jansen"){:target="_blank"} !

<!-- prettier-ignore-start -->
*[CNIL]: Commission Nationale de l’Informatique et des Libertés
*[CSP]: Content Security Policy
*[CSS]: Cascading Style Sheets
*[DAO]: Data Access Object
*[JPA]: Java Persistence API
*[RGPD]: Règlement Général sur la Protection des Données
*[SQL]: Structured Query Language
<!-- prettier-ignore-end -->
