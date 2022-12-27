---
layout: post
title: Liens en vrac — Décembre 2022
category: liens
seo:
  date_modified: 2023-01-08
---

Nouvelles, articles, podcasts, vidéos et découvertes intéressantes du mois de décembre 2022.

## Nouvelles

- [Tableau de bord des téléchargements vulnérables de Log4j](https://fr.sonatype.com/resources/log4j-vulnerability-resource-center)
  — un an après Log4Shell, l’utilisation de versions vulnérables de Log4j reste très élevée (~25 %).
  Ça ne veut pas dire qu’un quart des applications utilisant Log4j sont vulnérables, mais le chiffre
  reste étonnant !
- [GitLab 15.7 released introducing the GitLab CLI and with browser based DAST GA](https://about.gitlab.com/releases/2022/12/22/gitlab-15-7-released/)
  — c’est au tour de GitLab de proposer une CLI officielle : `glab`. Comme celle de GitHub, ça peut
  rendre certaines actions plus simples (comme le _checkout_ d’une _merge request_ provenant d’un
  dépôt _forké_), et c’est pratique pour du scripting. Il y a aussi pas mal d’autres choses sympas,
  comme l’amélioration de la recherche globale (qui en avait bien besoin !), la possibilité de
  spécifier la taille d’une image en Markdown ou la version bêta du nouvel IDE Web basé sur VS Code.
- [Leaked a secret? Check your GitHub alerts…for free](https://github.blog/2022-12-15-leaked-a-secret-check-your-github-alerts-for-free/)
  — bonne nouvelle, même si je croyais que c’était déjà le cas. Attention cette fonctionnalité doit
  être activée manuellement pour chaque projet (cherchez _Code security and analysis > Secret
  scanning_ dans les paramètres).
- [Docs are being translated to French, German, Korean, and Russian](https://github.blog/changelog/2022-12-05-docs-are-being-translated-to-french-german-korean-and-russian/)
  — la documentation de GitHub est en train d’être traduite en français. Ça doit être l’effet
  Microsoft :-).
- [Highlights from Git 2.39](https://github.blog/2022-12-12-highlights-from-git-2-39/)
  — c’est une bonne lecture si vous ne connaissez pas `git shortlog`.
- [SonarQube 9.8 is here!](https://www.sonarsource.com/products/sonarqube/whats-new/sonarqube-9-8/)
  — avec le support de Java 17 et enfin une meilleure prise en charge des renommages de fichiers.
- [GraalVM, Galahad, and a New Release Schedule](https://medium.com/graalvm/graalvm-galahad-and-a-new-release-schedule-d081d1031bba)
  — des détails sur Galahad, le projet d’intégration de certaines parties de GraalVM à OpenJDK.

## Articles, podcasts et vidéos

- [Signing Git Commits with Your SSH Key](https://calebhearth.com/sign-git-with-ssh)
  — je ne savais même pas que c’était possible ! Et c’est supporté par GitHub et, depuis la version
  15.7, par GitLab.
- [Gently Down the Stream](https://www.gentlydownthe.stream/), [A walk to the Cloud](https://a.walktothe.cloud/)
  — des introductions à Apache Kafka et au Cloud sous forme de bande dessinée. C’est très agréable
  à lire.
- [7 Awesome Libraries for Java Unit & Integration Testing (vidéo)](https://www.youtube.com/watch?v=JVPHSdHViMg)
  — une présentation succincte de sept super librairies Java pour les tests :
  [AssertJ](https://assertj.github.io/doc/), [Awaitility](http://www.awaitility.org/),
  [Mockito](https://site.mockito.org/), [Wiremock](https://wiremock.org/),
  [Wiser](https://github.com/voodoodyne/subethasmtp/blob/master/Wiser.md),
  [Memoryfilesystem](https://github.com/marschall/memoryfilesystem) et
  [Testcontainers](https://www.testcontainers.org/). À regarder si vous ne les connaissez pas déjà
  toutes.
- [The Wild World of Unique Identifiers (UUID, ULID, Snowflake, etc)](https://medium.com/geekculture/the-wild-world-of-unique-identifiers-uuid-ulid-etc-17cfb2a38fce)
  — je n’en connaissais même pas la moitié !
- [The best UUID type for a database Primary Key](https://vladmihalcea.com/uuid-database-primary-key/)
  — c’est [TSID](https://github.com/f4b6a3/tsid-creator) d’après l’auteur (que je ne connaissais pas
  non plus). Et il possède bien des avantages par rapport aux UUID, notamment le fait qu’ils soient
  triés par heure et beaucoup plus petits.
- [How to create SBOM in Java with Maven and Gradle](https://snyk.io/blog/create-sboms-java-maven-gradle/)
  — un bon article sur le sujet. Il y a deux standards principaux : SPDX (Fondation Linux) et
  CycloneDX (OWASP). Pour des questions d’outillage, il semble préférable de choisir CycloneDX. En
  effet, le projet [`spdx-maven-plugin`](https://github.com/spdx/spdx-maven-plugin) n’est pas très
  actif en comparaison de [`cyclonedx-maven-plugin`](https://github.com/CycloneDX/cyclonedx-maven-plugin).
  De plus il existe un plugin Gradle pour CycloneDX (`cyclonedx-gradle-plugin`) mais pas pour SPDX.
- [Why the number input is the worst input](https://stackoverflow.blog/2022/12/26/why-the-number-input-is-the-worst-input/)
  — et en plus l’article n’évoque même pas les problèmes d’internationalisation.
- [Define multiple languages in HTML root element's lang attribute?](https://stackoverflow.com/a/21246457/374236)
  — ça n’est pas malheureusement pas possible, dommage.
- [Reasons to avoid Javascript CDNs](https://blog.wesleyac.com/posts/why-not-javascript-cdn)
  — tl;dr : risque systémique, vie privée, sécurité et... vitesse de chargement !
- [What I learned at GitLab that I don’t want to forget](https://boleary.dev/what-i-learned-at-gitlab-that-i-dont-want-to-forget/)
  — l’organisation chez GitLab à l’air vachement sympa.
- [Why Picnic Picked Java](https://foojay.io/today/why-picnic-picked-java/)
  — quoiqu’on pense du choix et des arguments, ce genre de retour d’expérience est toujours
  intéressant à lire.
- [Le RGPD en 10 minutes](https://blog.davidlibeau.fr/le-rgpd-en-10-minutes/)
  — un article utile pour ceux qui n’ont jamais lu le texte de la RGPD (et ne le liront peut-être
  jamais).
- [#232 Kevin Trethewey on his extreme programming journey (podcast)](https://devjourney.info/Guests/232-KevinTrethewey.html)
  — j’ai beaucoup aimé son histoire et sa façon de voir les choses. Il faudra que je creuse cette
  histoire de [Spine Model](https://spinemodel.info/documentation.html).
- [ChatGPT remplacera-t-il les programmeuses et programmeurs ?](https://www.bortzmeyer.org/chatgpt-programmation.html)
  — on dirait bien que non. Par contre, à l’instar de Copilot, ça pourrait bien radicalement changer
  notre manière de travailler.

## Découvertes

- [Monkeyble — End-to-end testing framework for Ansible](https://hewlettpackard.github.io/monkeyble/)
  — enfin un framework qui permet de tester le code ansible lui-même, et non pas l’état du système
  après exécution d’un playbook. [Une très bonne présentation en français est disponible sur
  LinuxFR](https://linuxfr.org/news/presentation-de-monkeyble-framework-de-test-bout-en-bout-pour-ansible).
- [maven-test-profiler — Maven extension to get information about tests](https://github.com/khmarbaise/maven-test-profiler)
  — pratique pour identifier facilement les tests qui prennent le plus de temps.  
- [PieterExplainsTech — Visual guides on various technology topics like computer networking and programming](https://www.youtube.com/channel/UCaNX_EGXBgJYyrsRrziKnDQ)
  — une super chaîne Youtube, c’est toujours bien expliqué et on apprend souvent des choses même sur
  les sujets les plus basiques.
- [DB-Engines Ranking — Trend Popularity](https://db-engines.com/en/ranking_trend)
  — pour se faire une idée de la popularité des différents moteurs de base de données.

[That’s all folks](https://www.youtube.com/watch?v=Lb8Yw7mhEbo "Rover — Rising High"){:target="_blank"} !

<!-- prettier-ignore-start -->
*[CDNs]: Content Delivery Networks
*[CLI]: Command Line Interface
*[DAST]: Dynamic Application Security Testing
*[GA]: General Availability
*[GPT]: Generative Pre-trained Transformer
*[HTML]: HyperText Markup Language
*[IDE]: Integrated Development Environment
*[OWASP]: Open Web Application Security Project
*[RGPD]: Règlement Général sur la Protection des Données
*[SBOM]: Software Bill Of Materials
*[SPDX]: Software Package Data Exchange
*[tl;dr]: too long; didn’t read
*[TSID]: Time-Sorted unique IDentifier
*[ULID]: Unique Lexicographically IDentifier
*[UUID]: Universal Unique IDentifier
*[VS]: Visual Studio
<!-- prettier-ignore-end -->
