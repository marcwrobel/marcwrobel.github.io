---
layout: post
title: Liens en vrac — Mars 2022
category: liens
youtube_video_id: yfLlZHGfMdo
youtube_video_title: TOTORRO - Gérard Blast
---

## Nouvelles

- [The Arrival of Java 18!](https://inside.java/2022/03/22/the-arrival-of-java18/)
  — faites attention : UTF-8 devient l’encodage par défaut sur toutes les plateformes. Pensez aussi à jeter un coup
  d’œil aux [JDK 18 Security Enhancements](https://seanjmullan.org/blog/2022/03/23/jdk18).
- [Hibernate 6.0 Final](https://in.relation.to/2022/03/31/orm-60-final/)
  — après 7 ans d’Hibernate 5, Hibernate 6 sort avec énormément d’améliorations.
  Une [migration](https://docs.jboss.org/hibernate/orm/6.0/migration-guide/migration-guide.html) sera néanmoins à
  prévoir.
- [GitLab 14.9 released with epic to epic linking and integrated security training](https://about.gitlab.com/releases/2022/03/22/gitlab-14-9-released/)
  — pas mal de petites améliorations, mais rien qui sorte du lot ce mois-ci.
- [Announcing TypeScript 4.6](https://devblogs.microsoft.com/typescript/announcing-typescript-4-6/)
  — le compilateur s’améliorer, quelques contraintes sont relâchées et la cible _es2022_ fait son apparition.
- [What's new in Angular 13.3?](https://blog.ninja-squad.com/2022/03/16/what-is-new-angular-13.3/)
  — le support de TypeScript 4.6, ainsi qu’une légère réduction de la taille du code compilé.
- [Chrome 100 Released With APIs For Multi-Screen Window Placement, Digital Goods](https://www.phoronix.com/scan.php?page=news_item&px=Google-Chrome-100)
  — le passage à un numéro de version à trois chiffres n’aura finalement pas été problématique, espérons qu’il en soit
  de même pour Firefox.
- [Keycloak release plans for 2022](https://www.keycloak.org/2022/03/releases)
  — une année bien chargée.
- [Waiting for PostgreSQL 15 – Add support for MERGE SQL command](https://www.depesz.com/2022/03/31/waiting-for-postgresql-15-add-support-for-merge-sql-command/)
  — en voilà une bonne nouvelle !
- [Un cas rigolo d'oubli d'un nom de domaine](https://www.bortzmeyer.org/attaque-sous-domaine-caisse-epargne.html)
  — pensez à supprimer vos domaines / sous-domaines inutilisés ;).
- [Conti Ransomware Group Diaries](https://krebsonsecurity.com/2022/03/conti-ransomware-group-diaries-part-iv-cryptocrime/)
  — une série d’articles qui analyse les discussions internes du groupe de cybercriminels Conti.
- [Spring Framework RCE, Early Announcement](https://spring.io/blog/2022/03/31/spring-framework-rce-early-announcement),
  [Researchers Warn of Linux Kernel 'Dirty Pipe' Arbitrary File Overwrite Vulnerability](https://thehackernews.com/2022/03/researchers-warn-of-linux-kernel-dirty.html)
  — pensez à vous mettre à jour au plus vite.
- [Popular NPM Package Updated to Wipe Russia, Belarus Systems to Protest Ukraine Invasion](https://thehackernews.com/2022/03/popular-npm-package-updated-to-wipe.html)
  — à mon sens ce type de protestation fait plus de mal que de bien…
- [A new year, a new MDN](https://hacks.mozilla.org/2022/03/a-new-year-a-new-mdn/)
  — le résultat est joli !

## Articles, podcasts et vidéos

- [Stop overloading JWTs with permission claims](https://sdoxsee.github.io/blog/2020/01/06/stop-overloading-jwts-with-permission-claims)
  — une réflexion intéressante sur ce qui devrait ou non être stocké dans un token JWT.
- [Design Patterns and Principles That Support Large Scale Systems](https://medium.com/everything-full-stack/design-patterns-and-principles-that-support-large-scale-systems-f3c9adf89ad)
  — liste et défini (de manière concise) les patterns à connaitre lorsqu’on veut développer des systèmes distribués.
- [New Browser-in-the Browser (BITB) Attack Makes Phishing Nearly Undetectable](https://thehackernews.com/2022/03/new-browser-in-browser-bitb-attack.html)
  — bon à savoir, mais étonnant que ce soit si nouveau.
- [DevSecOps - Sécurisez, Auditez, Automatisez vos bases de données PostgreSQL](https://blog.ippon.fr/2022/03/28/securisez-auditez-automatisez-vos-bases-postgresql-4/)
  — une bonne série d’articles sur la mise en place de PostgreSQL. Pas mal de points sont valables pour d’autres moteurs
  de base de données.
- [CUPID — for joyful coding](https://dannorth.net/2022/02/10/cupid-for-joyful-coding/)
  — [Dan North](https://dannorth.net/about/) propose une alternative aux principes
  [SOLID](https://wikipedia.org/wiki/SOLID).
- [The Code Review Pyramid](https://www.morling.dev/blog/the-code-review-pyramid/)
  — on aime beaucoup les pyramides en informatique !
- [The Ultimate Guide on Composite IDs in JPA Entities](https://www.jpa-buddy.com/blog/the-ultimate-guide-on-composite-ids-in-jpa-entities/)
  — tout, tout, tout, vous saurez tout sur les _composite IDs_.
- [Git Commit Messages: Best Practices & Guidelines](https://initialcommit.com/blog/git-commit-messages-best-practices)
  — un très bon article sur le sujet.
- [Why Vaccine Cards Are So Easily Forged](https://www.schneier.com/blog/archives/2022/03/why-vaccine-cards-are-so-easily-forged.html)
  — trop de sécurité tue la sécurité.
- [+UseContainerSupport to the Rescue](https://www.atamanroman.dev/development/2019/09/11/usecontainersupport-to-the-rescue.html)
  — pensez à augmenter `-XX:MaxRAMPercentage` si votre application Java est conteneurisée.
- [How do you limit non-heap size on Open JDK 11](https://stackoverflow.com/q/65195369)
  — tl;dr : ça n'est pas possible.
- [How to protect GitLab-connected SSH key with Yubikey](https://about.gitlab.com/blog/2022/03/03/how-to-protect-gitlab-connected-ssh-key-with-yubikey/)*
  — il faudra que je teste ça.
- [Extended Diagnostics](https://blog.angular.io/angular-extended-diagnostics-53e2fa19ece9)
  — une nouvelle fonctionnalité Angular qui améliore la vérification des _templates_ : cool !
- [Java records & compact constructors](https://mikemybytes.com/2022/02/16/java-records-and-compact-constructors/)
  — un très bon article sur les `record`s.
- [Lessons learned from previous projects](https://blog.frankel.ch/lessons-learned-previous-projects/)
  — les retours d’expérience de développeurs chevronnés sont toujours intéressants à lire.
- [Maven "versions" plugin - how to exclude alpha/beta versions from response?](https://stackoverflow.com/q/10230903)
  — tl;dr : utiliser un fichier de règles à ignorer avec
  `<ignoreVersion type="regex">.*[-_\.](alpha|Alpha|ALPHA|b|beta|Beta|BETA|rc|RC|M|EA)[-_\.]?[0-9]*</ignoreVersion>`.
- [Azure Devops yml pipeline if else condition with variables](https://stackoverflow.com/q/69652609/374236)
  — ou comment simuler un _ternary operator_ dans un pipeline Azure DevOps.

## Découvertes

- [jless](https://pauljuliusmartinez.github.io/)
  — _a command-line JSON viewer_.
- [How to get the SQL query from JPQL or JPA Criteria?](https://vladmihalcea.com/get-sql-from-jpql-or-criteria/)
  — `SQLExtractor` c'est vraiment très pratique !
- [NewReleases](https://newreleases.io/)
  — une alternative à [libraries.io](https://libraries.io) (qui visiblement ne permet plus d’ajouter de nouvelles
  souscriptions).

That’s all folks !

*[APIs]: Application Programming Interfaces
*[BITB]: Browser-In-The-Browser
*[CUPID]: Composable, Unix philosophy, Predictable, Idiomatic, Domain-based
*[es2022]: ECMAScript 2020
*[JDK]: Java Development Kit
*[IDs]: Identifiers
*[JPA]: Java Persistence API
*[JPQL]: Java Persistence Query Language
*[JSON]: JavaScript Object Notation
*[JWT]: JSON Web Token
*[JWTs]: JSON Web Tokens
*[NPM]: Node Package Manager
*[MDN]: Mozilla Developer Network
*[SOLID]: Single responsibility principle, Open/closed principle, Liskov substitution principle, Interface segregation principle, Dependency inversion principle
*[RCE]: Remote Code Execution
*[SQL]: Structured Query Language
*[SSH]: Secure SHell
*[tl;dr]: too long; didn’t read
*[UTF-8]: Universal Character Set Transformation Format - 8 bits
