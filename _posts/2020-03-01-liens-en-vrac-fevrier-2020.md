---
layout: post
title: Liens en vrac - Février 2020
category: liens
tags: tomcat sécurité lets-encrypt typescript firefox microsoft gitlab groovy elastic angular kiss uuid postgresql noestimate languages webassembly openjdk sshuttle passbolt
---

## News
* [Ghostcat breach affects all Tomcat versions](https://snyk.io/blog/ghostcat-breach-affects-all-tomcat-versions/)
  — une vulnérabilité dans le connecteur AJP d’Apache Tomcat, mettez-vous à jour au plus vite si
    vous êtes concernés !
* [Let’s Encrypt Has Issued a Billion Certificates](https://letsencrypt.org/2020/02/27/one-billion-certs.html)
  — Impressionnant !
* [Multi-Perspective Validation Improves Domain Validation Security](https://letsencrypt.org/2020/02/19/multi-perspective-validation.html)
  — Let’s Encrypt s’améliore encore un peu plus.
* [Certificate lifetime capped to 1 year from Sep 2020](https://scotthelme.co.uk/certificate-lifetime-capped-to-1-year-from-sep-2020/)
  — merci Apple !
* [Announcing TypeScript 3.8](https://devblogs.microsoft.com/typescript/announcing-typescript-3-8/)
  — au menu : des améliorations sur les imports / exports, le support des champs privés ECMAScript,
    et le support des instructions `await` en dehors de block `async` (_top-level await_).
* [New CWE List of Common Security Weaknesses](https://www.us-cert.gov/ncas/current-activity/2020/02/26/new-cwe-list-common-security-weaknesses-0)
  — l’organisme [MITRE](https://wikipedia.org/wiki/MITRE) sort la version 4.0 de sa liste [CWE](https://cwe.mitre.org/) qui prend désormais aussi en compte les
    vulnérabilités matérielles.
* [Firefox enables DNS-over-HTTPS by default (with Cloudflare) for all U.S. users](https://thehackernews.com/2020/02/firefox-dns-over-https.html)
  — l’option peut aussi être activée depuis les paramètres réseaux.
* [Microsoft Brings Defender Antivirus for Linux, Coming Soon for Android and iOS](https://thehackernews.com/2020/02/windows-defender-atp-linux-android.html)
  — surprenant…
* [GitLab 12.8 released with Log Explorer, NuGet, and Compliance](https://about.gitlab.com/releases/2020/02/22/gitlab-12-8-released/)
  — rien de plus à dire.
* [Release notes for Groovy 3.0](http://groovy-lang.org/releasenotes/groovy-3.0.html)
  — Groovy 3.0 est enfin sorti. De nombreuses améliorations ont été apportées au language, notamment
    au niveau de l’interopérabilité avec Java.
* [Elastic Stack 7.6.0 released](https://www.elastic.co/blog/elastic-stack-7-6-0-released)
  — un nouveau moteur de détection SIEM, des améliorations de performance, et bien d’autres choses
    encore.
* [Version 9 of Angular Now Available — Project Ivy has arrived!](https://blog.angular.io/version-9-of-angular-now-available-project-ivy-has-arrived-23c97b63cfa3)
  — le pipeline de compilation et de rendu _Ivy_ est désormais activé par défaut.
* [OpenSSH 8.2 Released With FIDO/U2F Support](https://www.phoronix.com/scan.php?page=news_item&px=OpenSSH-8.2-Released)
  — support FIDO/U2F, dépréciation de ssh-rsa, support de `Include`.

## Articles
* [Where is this coming from?](https://techblog.bozho.net/where-is-this-coming-from/)
  — [KISS](https://fr.wikipedia.org/wiki/Principe_KISS).
* [Why I’m not fan of uuid datatype](https://www.depesz.com/2020/02/19/why-im-not-fan-of-uuid-datatype/)
  — un point de vue intéressant sur l’utilisation de clés primaires de type UUID.
* [Mon estimation la moins chère](https://www.arolla.fr/blog/2020/02/mon-estimation-la-moins-chere/)
  — un retour d’expérience sympa sur les estimations.
* [20 most significant programming languages in history](https://anarc.at/blog/2020-02-02-most-significant-programming-languages-history/)
  — concis et digeste.
* [Comprendre WebAssembly en 5 minutes](https://www.jesuisundev.com/comprendre-webassembly-en-5-minutes/)
  — c’est gagné !
* [Mise en perspective des impacts écologiques du numérique - la suite](https://www.raphael-lemaire.com/2020/02/02/mise-en-perspective-suite/)
  — toujours aussi intéressant !

## Découvertes
* [Overview of OpenJDK distributions](https://rafael.codes/openjdk/)
  — pour s’y retrouver dans cette pléthore de distributions.
* [sshuttle](https://github.com/sshuttle/sshuttle)
  — une alternative au VPN pas si pauvre que cela.
* [Passbolt, une solution pour gérer les secrets au sein de votre équipe](https://blog.octo.com/passbolt-une-solution-pour-gerer-les-secrets-au-sein-de-votre-equipe/)
  — enfin un gestionnaire de mots de passe open source qui permet de gérer facilement le partage
    de mots de passe. L'[épisode NoLimitSecu#244]((https://www.nolimitsecu.fr/passbolt/)), consacré
    à [passbolt](https://www.passbolt.com/), est lui aussi très intéressant.

That’s all folks !

*[BGP]: Border Gateway Protocol
*[CWE]: Common Weakness Enumeration
*[KISS]: Keep It Simple, Stupid
*[SIEM]: Security Information Management System
*[UUID]: Universal Unique IDentifier
