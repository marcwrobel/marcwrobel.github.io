---
layout: post
title: Liens en vrac - Novembre 2018
category: liens
tags: amazon corretto jdk sepa epc typescript elastic apm tls sécurité password mot passe 2fa u2f pass yubikey hibernate pwa amp ansible ansible-pull 
---

## News

* [Amazon now has its own version of Java: Corretto](https://www.infoworld.com/article/3324492/amazon-now-has-its-own-version-of-java-corretto.html)
  – et encore une !
* [Extension of the geographical scope of SEPA schemes in March 2019](https://www.europeanpaymentscouncil.eu/news-insights/news/extension-geographical-scope-sepa-schemes-march-2019)
  – La principauté d'Andorre et l'État de la Cité du Vatican rejoignent la zone SEPA.
* [Publication of the 2019 EPC SEPA scheme rulebooks](https://www.europeanpaymentscouncil.eu/news-insights/news/publication-2019-epc-sepa-scheme-rulebooks)
  – Techniquement pas grand-chose de neuf.
* [Announcing TypeScript 3.2](https://devblogs.microsoft.com/typescript/announcing-typescript-3-2/)
  – pas mal d'améliorations dont notamment : des contrôles plus stricts pour `bind` / `call` / `apply`, l'héritage de configuration via les packages
  `node_modules`, ou encore le support `BigInt` (`esnext`).
* [Elastic APM Java Agent is Generally Available](https://www.elastic.co/fr/blog/elastic-apm-java-agent-is-generally-available)
  – j'ai hâte d'avoir l'occasion de jouer avec !
* [SSL Labs Grade Change for TLS 1.0 and TLS 1.1 Protocols](https://blog.qualys.com/ssllabs/2018/11/19/grade-change-for-tls-1-0-and-tls-1-1-protocols)
  – il va falloir penser à migrer vers TLS 1.2+.
* [La Suite Elastic 6.5.0 est arrivée](https://www.elastic.co/fr/blog/elastic-stack-6-5-0-released)
  – pas mal de nouvelles fonctionnalités, consultez l'article pour plus d'informations.

## Articles

* [Passwords Evolved: Authentication Guidance for the Modern Era](https://www.troyhunt.com/passwords-evolved-authentication-guidance-for-the-modern-era/)
  – super intéressant ! Après vous pouvez lire
  aussi [Here's Why 'Insert Thing Here' Is Not a Password Killer](https://www.troyhunt.com/heres-why-insert-thing-here-is-not-a-password-killer/).
* [Beyond Passwords: 2FA, U2F and Google Advanced Protection](https://www.troyhunt.com/beyond-passwords-2fa-u2f-and-google-advanced-protection/)
  – _adding a second step to authentication should not be seen as an excuse to weaken the first step_.
* [The perfect password manager](https://www.palkeo.com/sys/perfect-password-manager.html)
  – [Yubikey](https://www.yubico.com/) + [pass](https://www.passwordstore.org/).
* [Ultimate Guide to Implementing equals() and hashCode() with Hibernate](https://thoughts-on-java.org/ultimate-guide-to-implementing-equals-and-hashcode-with-hibernate/)
  – _you only need to override Object’s default implementations, if you work with multiple Hibernate Sessions or with detached entities. For all other
  applications, the default implementation works perfectly fine._
* [You need neither PWA nor AMP to make your website load fast](https://tonsky.me/blog/pwa/)
  – une petite dose de pragmatisme ça ne fait pas de mal.
* [SSL Handshake Failures](https://www.baeldung.com/java-ssl-handshake-failures)
  – car ce type d'erreurs n'est vraiment pas explicite.
* [L’inversion du modèle de connexion d’Ansible avec Ansible-pull : killer feature ?](https://blog.octo.com/ansible-pull-killer-feature/)
  – pas vraiment on dirait.

That's all folks !

*[2FA]: Two-Factor Authentication
*[AMP]: Accelerated Mobile Pages
*[APM]: Application Performance Management
*[EPC]: European Payments Council
*[PWA]: Progressive Web Application
*[SEPA]: Single Euro Payments Area
*[SSL]: Secure Sockets Layers
*[TLS]: Transport Layer Security
*[U2F]: Universal 2nd Factor
