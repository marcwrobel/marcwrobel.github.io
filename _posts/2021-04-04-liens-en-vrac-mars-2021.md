---
layout: post
title: Liens en vrac - Mars 2021
category: liens
tags: debian java jdk openjdk sms gitlab elastic securite sms ovh spring solarwinds git applet tls pratiques hibernate jpa spectre sigstore keycloak cloud-iam nginx
---

## Nouvelles

- [Debian 11.0 Is Now Under A Hard Freeze](https://www.phoronix.com/scan.php?page=news_item&px=Debian-11.0-Hard-Freeze)
  – c'est pour bientôt !
- [JDK 16 is live!](https://blogs.oracle.com/thejavatutorials/jdk-16-is-live)
  – au menu : les _records_ font maintenant partie du language, la valeur par défaut de `--illegal-access` passe de `permit` à `deny`, support des _Unix domain
  sockets_, ajout de la méthode `Stream.toList()`, ZGC devient _pauseless_, support des algorithmes de signature basés sur SHA-3, `jpackage` sort d'incubation
  pour devenir une fonctionnalité permanente, et [bien d'autres choses encore](https://jdk.java.net/16/release-notes) (pensez à jeter aussi un coup d’œil à [JDK
  16 Security Enhancements](https://seanjmullan.org/blog/2021/03/18/jdk16)).
- [GitLab 13.10 released with Admin Enhancements and Vulnerability Management](https://about.gitlab.com/releases/2021/03/22/gitlab-13-10-released/)
  – avec la possibilité de créer des _releases_ à partir d’un tag, de définir le type d’environnement dans `.gitlab-ci.yml`, l'amélioration de
  `parallel: matrix`, de nouvelles variables prédéfinies (`CI_JOB_STARTED_AT`, `CI_PIPELINE_CREATED_AT`)...
- [Lancement d'Elastic 7.12 : disponibilité générale du schéma de lecture, préversion technique du niveau gelé et support pour le scaling automatique](https://www.elastic.co/fr/blog/whats-new-elastic-7-12-0-schema-on-read-frozen-tier-autoscaling)
  – avec comme d’habitude tellement de nouveautés que je vous laisse lire l’article.
- [Can We Stop Pretending SMS Is Secure Now?](https://krebsonsecurity.com/2021/03/can-we-stop-pretending-sms-is-secure-now/)
  – pensez à retirer l’option SMS de vos authentifications 2FA quand c’est possible.
- [OVH News - Incendie sur notre site de Strasbourg](https://www.ovh.com/fr/news/presse/cpl1785.dernieres-informations-notre-site-strasbourg)
  – et [Octave Klaba, Président OVH s'exprimant après un incendie dans le Datacenter OVH Strasbourg](https://www.youtube.com/watch?v=AU5_rqQc1-g).
- [Announcing Spring Native Beta!](https://spring.io/blog/2021/03/11/announcing-spring-native-beta)
  – un grand pas vers la compilation native d'application Spring.
- [SolarWinds Blames Intern for 'solarwinds123' Password Lapse](https://thehackernews.com/2021/03/solarwinds-blame-intern-for-weak.html)
  – c’est petit...
- [The new Git default branch name](https://about.gitlab.com/blog/2021/03/10/new-git-default-branch-name/)
  – le nom de la branche par défaut passera de `master` à `main` à partir de GitLab 14.0 pour les nouveaux projets.
- [Applets Java : c'est vraiment fini](https://www.programmez.com/actualites/applets-java-cest-vraiment-fini-31592)
  – enfin !
- [RFC 8996: Deprecating TLSv1.0 and TLSv1.1](https://www.bortzmeyer.org/8996.html)
  – pensez à retirer le support de ces protocoles si ça n’est pas encore fait.


## Articles, podcasts et vidéos

- [Êtes-vous sûrs de vos bonnes pratiques ?](https://www.geek-directeur-technique.com/2021/02/18/etes-vous-surs-de-vos-bonnes-pratiques)
  – les bonnes pratiques suivent des modes.
- [Hibernate Slow Query Log – The easiest way to find slow queries](https://thorben-janssen.com/hibernate-slow-query-log/)
  – sympa si vous n’avez pas la main [sur la base de données](https://www.cybertec-postgresql.com/en/3-ways-to-detect-slow-queries-in-postgresql/).
- [A Spectre proof-of-concept for a Spectre-proof web](https://security.googleblog.com/2021/03/a-spectre-proof-of-concept-for-spectre.html)
  – flippant !
- [Introducing sigstore: Easy Code Signing & Verification for Supply Chain Integrity](https://security.googleblog.com/2021/03/introducing-sigstore-easy-code-signing.html)
  – j’ai encore un peu de mal à voir comment ça fonctionne, mais ça à l’air intéressant.
- [Pull Requests Considered Harmful](https://medium.com/@franciscomt/pull-requests-considered-harmful-c3a10af8becd)
  – ça ne fait pas de mal de se poser la question.
- [67 New Features in JDK 16](https://www.azul.com/67-new-features-in-jdk-16/)
  – un bon résumé des nouveautés du JDK 16.
- [Stop using JPA / Hibernate](https://www.stemlaur.com/blog/2021/03/30/tech-hibern-hate/)
  – j’y pense depuis un petit moment...
- [How to turn off the Keycloak theme cache](https://keycloakthemes.com/blog/how-to-turn-off-the-keycloak-theme-cache)
  – indispensable si vous développez votre thème Keycloak.

## Découvertes

- [`column` - Displaying CSV files in a readable way on the terminal](http://meta.libera.cc/2021/03/displaying-csv-files-in-readable-way-on.html)
  – une petite commande sympa disponible [sur tous les systèmes Linux](https://fr.wikipedia.org/wiki/Util-linux).
- [JustDeleteMe](https://justdeleteme.xyz/)
  – _A directory of direct links to delete your account from web services_.
- [Cloud-IAM](https://www.cloud-iam.com/)
  – _Keycloak Identity and Access Management as a Service_.
- [ bunkerity/bunkerized-nginx](https://github.com/bunkerity/bunkerized-nginx)
  – _nginx Docker image secure by default_.

That's all folks !

*[CSV]: Comma-Separated Values
*[JDK]: Java Development Kit
*[JPA]: Java Persistence API
*[SHA-3]: Secure Hash Algorithm 3
*[SMS]: Short Message Service
*[TLSv1.0]: Transport Layer Security v1.0
*[TLSv1.1]: Transport Layer Security v1.1
*[ZGC]: Z Garbage Collector
