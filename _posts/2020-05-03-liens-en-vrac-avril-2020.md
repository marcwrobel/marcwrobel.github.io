---
layout: post
title: Liens en vrac — Avril 2020
category: liens
---

## Nouvelles
* [GitLab 12.10 released with Requirements Management and Autoscaling CI on AWS Fargate](https://about.gitlab.com/releases/2020/04/22/gitlab-12-10-released/)
  — et bien d’autres choses encore.
* [Node.js 14.0 Improves Diagnostics and Internationalization, Adds Web Assembly System Interface](https://www.infoq.com/news/2020/04/node-js-14-release/)
  — tout est dans le titre.
* [jQuery 3.5 Released, Fixes XSS Vulnerability](https://www.infoq.com/news/2020/04/jquery-35-xss-vulnerability-fix/)
  — mettez-vous à jour au plus vite si vous êtes concernés !
* [Bootstrap 5.0 ne supportera pas Internet Explorer 11](https://www.programmez.com/actualites/bootstrap-50-ne-supportera-pas-internet-explorer-11-30444)
  — et c’est plutôt [une bonne chose](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/the-perils-of-using-internet-explorer-as-your-default-browser/ba-p/331732)
    à mon avis. 
* [Project Leyden addresses Java pain points](https://www.infoworld.com/article/3540709/project-leyden-addresses-java-pain-points.html)
  — pour réduire le temps de démarrage et l’empreinte mémoire des applications Java,
    [Mark Reinhold](https://twitter.com/mreinhold) propose l’introduction d’images statiques dans la
    plate-forme Java (dans la lignée de ce que l’on peut déjà voir avec [GraalVM](https://www.graalvm.org/)).
* [Updates to Spring Versions](https://spring.io/blog/2020/04/30/updates-to-spring-versions)
  — Spring passe à [CalVer](https://calver.org/) pour les [release trains](https://en.wikipedia.org/wiki/Software_versioning#Release_train),
    et à [SemVer](https://semver.org/) pour les projets.
* [Another one-line npm package breaks the JavaScript ecosystem](https://www.zdnet.com/article/another-one-line-npm-package-breaks-the-javascript-ecosystem/)
  — ce genre de problème semble avoir moins d’impacts dans d’autres languages car l’utilisation de
    versions [non-fixes](https://docs.npmjs.com/about-semantic-versioning#using-semantic-versioning-to-specify-update-types-your-package-can-accept)
    est, heureusement, moins répandue.
* [Announcing the Compose Specification](https://www.docker.com/blog/announcing-the-compose-specification/)
  — une initiative appréciable.
* [GitHub is now free for teams](https://github.blog/2020-04-14-github-is-now-free-for-teams/)
  — en voilà une bonne nouvelle !

## Articles, podcasts et vidéos
* [15 Git tips to improve your workflow](https://about.gitlab.com/blog/2020/04/07/15-git-tips-improve-workflow/)
  — GitLab partage quelques astuces à connaitre à l’occasion des 15 ans de Git.
* [Spring Boot - Comparing Liquibase and Flyway](https://4lex.nz/2020/04/spring-boot-database-migrations)
  — tout comme l’auteur de cet article, je pense aussi que Flyway est la solution la plus simple à
    mettre en place et à utiliser.
* [When should I write an Architecture Decision Record?](https://labs.spotify.com/2020/04/14/when-should-i-write-an-architecture-decision-record/)
  — tl;dr Have you made a significant decision that impacts how engineers write software? Write an
    ADR!
* [Package by Feature](https://phauer.com/2020/package-by-feature/)
  — _package by layer_ is dead !
* [Simple Systems Have Less Downtime](https://www.gkogan.co/blog/simple-systems/?r=0)
  — il est toujours bon de le rappeler.
* [STOP!! You don’t need Microservices.](https://medium.com/swlh/stop-you-dont-need-microservices-dc732d70b3e0)
  — à lire après avoir lu l’article précédent.
* [Beware of computation in static initializer](https://pangin.pro/posts/computation-in-static-initializer)
  — étonnant !
* [Programmation défensive en bash](https://blog.seboss666.info/2020/04/programmation-defensive-en-bash/)
  — un joli recueil de bonnes pratiques.
* [Open banking: EBICS versus API](https://www.ebicsblog.com/2020/04/open-banking-ebics-versus-api.html)
  — EBICS essaie de se placer.
* [Can cash survive coronavirus?](https://www.thersa.org/discover/publications-and-articles/rsa-blogs/2020/04/cash-survive-coronavirus)
  — il se pourrait bien que non.

## Découvertes
* [git-prompt.sh](https://github.com/git/git/blob/master/contrib/completion/git-prompt.sh)
  — et c’est installé avec le paquet `git` de Debian (`/etc/bash_completion.d/git-prompt`).
* [Use The Index, Luke!](https://use-the-index-luke.com/)
  — un site sur les indexes SQL à destination des développeurs.
* [Learn Kubernetes. From Experts. For Free.](https://kube.academy/)
  — une bonne ressource pour démarrer avec Kubernetes.

That’s all folks !

*[ADR]: Architecture Decision Record
*[API]: Application Programming Interface
*[AWS]: Amazon Web Services
*[CalVer]: Calendar Versioning
*[CI]: Continuous Integration
*[EBICS]: Electronic Banking Internet Communication Standard
*[npm]: Node Package Manager
*[SemVer]: Semantic Versioning
*[SQL]: Structured Query Language
*[tl;dr]: too long; didn’t read
*[XSS]: CROSS-Site Scripting
