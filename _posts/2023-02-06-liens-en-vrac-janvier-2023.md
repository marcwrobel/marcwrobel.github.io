---
layout: post
title: Liens en vrac — Janvier 2023
category: liens
seo:
  date_modified: 2023-02-06
---

Nouvelles, articles, podcasts, vidéos et découvertes intéressantes du mois de janvier 2023.

## Nouvelles

- [Hackers Can Abuse Visual Studio Marketplace to Target Developers with Malicious Extensions](https://thehackernews.com/2023/01/hackers-distributing-malicious-visual.html)
  — rien de vraiment étonnant, le risque est similaire peu importe le système de plug-ins ou de
  paquets. Mais j’ai l’impression que le manque de fonctionnalités intégrées de base dans VS Code
  (que ce soit en natif ou via des plug-ins "officiels") rend cet IDE plus sensible à ce genre
  d’attaques.
- [Java’s Plans for 2023 (vidéo)](https://inside.java/2023/01/19/newscast-40/)
  — un rapide tour d’horizon de ce qui s’est passé en 2022 et de ce qui devrait se passer 2023.
- [Mockito 5 Supports Mocking Constructors, Static Methods and Final Classes out of the Box](https://www.infoq.com/news/2023/01/mockito-5/)
  — le support des `varargs` a été grandement amélioré, par contre Java 8 n’est plus supporté.
- [What’s new in Angular 15.1?](https://blog.ninja-squad.com/2023/01/11/what-is-new-angular-15.1/) et
  [What’s new in Angular CLI 15.1?](https://blog.ninja-squad.com/2023/01/11/angular-cli-15.1/)
  — on peut enfin écrire `<my-component />` !
- [Add more social links to your GitHub user profile](https://github.blog/changelog/2023-02-02-add-more-social-links-to-your-user-profile/)
  — ça n’est pas grand-chose, mais ça manquait.
- [Oracle’s New Pricing Model Is Like Cold Coffee – Send It Back](https://www.azul.com/blog/oracles-new-pricing-model-is-like-cold-coffee-send-it-back/)
  — vraiment étrange cette nouvelle tarification "à l’employé" qui fait fortement monter les prix.
  Mais bon, je ne pense pas que ce soit un gros problème étant donné [l’offre pléthorique autour
  d’OpenJDK](https://whichjdk.com/ "Which Version of JDK Should I Use?").
- [GitHub is Sued, and We May Learn Something About Creative Commons Licensing](https://scholarlykitchen.sspnet.org/2023/01/05/github-is-sued-and-we-may-learn-something-about-creative-commons-licensing/)
  — les débuts d’une bataille judiciaire qui sera passionnante à suivre. Le verdict pourrait changer
  pas mal la donne sur le modèle commercial des sociétés telles
  qu’[OpenAI LP](https://openai.com/blog/openai-lp/).
- [Clever Cloud and Scaleway join forces to unveil a sovereign, European, PaaS offering](https://www.clever-cloud.com/blog/press/2023/01/17/clever-cloud-and-scaleway-join-forces-to-unveil-a-sovereign-european-paas-offering/),
  [Very Tech Trip, l’aventure ne fait que commencer !](https://blog.ovhcloud.com/very-tech-trip-laventure-ne-fait-que-commencer/)
  — plein d’annonces et de nouveautés chez les fournisseurs d’informatique en nuage français, cool !

## Articles, podcasts et vidéos

- [You Want Modules, Not Microservices](https://blogs.newardassociates.com/blog/2023/you-want-modules-not-microservices.html)
  — un des meilleurs articles que j’ai pu lire sur le sujet.
- [Stop trying to be so DRY, instead Write Everything Twice (WET)](https://dev.to/wuz/stop-trying-to-be-so-dry-instead-write-everything-twice-wet-5g33)
  — WET, un très bon principe pour ceux qui ont tendance à vouloir généraliser les choses trop tôt.
- [Database branching (just like with git) in PostgreSQL](https://filip-prochazka.com/blog/database-branching-in-postgresql)
  — Autre possibilité qui est plus simple quand vous avez la possibilité de la mettre en œuvre :
  utiliser des snapshots ou des clones ZFS. Mais bon, ce serait bien qu’il y ait nativement des
  [fonctionnalités de ce genre](https://postgres.fm/episodes/database-branching "Postgres FM - Database branching (podcast)")
  dans les bases de données.
- [20 Things I’ve Learned in my 20 Years as a Software Engineer](https://www.simplethread.com/20-things-ive-learned-in-my-20-years-as-a-software-engineer/)
  — plus on apprend, plus on se rend compte qu’on ne sait pas grand-chose et qu’[on est loin de tout
  bien faire](https://airhacks.fm/#episode_224 "airhacks.fm - What does it mean to be a professional
  programmer? (podcast)").
- [What is the Great Firewall of China and how does it work?](https://protonvpn.com/blog/great-firewalll-china/)
  — intéressant !
- [Simple retry until with WGet](https://rmannibucau.metawerx.net/simple-retry-with-wget.html)
  — tl;dr : `wget --no-check-certificate --read-timeout=30 --timeout=30 --retry-connrefused --waitretry=5 --tries=60 "https://$MY_SERVICE_HOST:$MY_SERVICE_PORT/some/resource"`.
- [Les listes : mise en page et forme](https://www.scribbr.fr/elements-linguistiques/les-listes/)
  — si vous aussi vous galérez avec la ponctuation dans les listes, cet article peut aider.

## Découvertes

- [just - Command Line toolkit for developing Spring Boot applications](https://just.maciejwalkowiak.com/)
  — je n’ai pas testé, mais ça m’a l’air pratique.
- [Slidev - Presentation Slides for Developers](https://sli.dev/)
  — désormais il y a aussi le _slide as code_ !
- [MerciApp - Le meilleur correcteur d’orthographe francophone](https://www.merci-app.com/)
  — je ne sais pas si c’est le meilleur, mais il fonctionne très bien. Ils ont en plus une offre
  gratuite (qui nécessite de s’inscrire).
- [DeepL Translator - AI translation that sounds human](https://www.deepl.com/translator)
  — j’ai l’impression que ça fonctionne mieux que Google Traduction.
- [Expédition dactylo](https://www.edclub.com/library/expedition-dactylo)
  — un très bon cours de dactylographie en ligne. Il n'est jamais trop tard pour s’y mettre !

[That’s all folks](https://www.youtube.com/watch?v=Uavys_AN9K8 "Sarah McCoy - Boogieman"){:target="_blank"} !

<!-- prettier-ignore-start -->
*[CLI]: Command Line Interface
*[DRY]: Don’t Repeat Yourself
*[IDE]: Integrated Development Environment
*[tl;dr]: too long; didn’t read
*[WET]: Write Everything Twice
*[ZFS]: Z File System
<!-- prettier-ignore-end -->
