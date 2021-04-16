---
layout: post
title: Sortie de jbanking 2.0.0
category: développement
tags: jbanking iso-3166 iso-4217 iban sepa iso-13616 pays devise
---

La version 2.0.0 de [jbanking](https://github.com/marcwrobel/jbanking) est (enfin !) sortie. Cette
nouvelle version inclue :
* une revue de la liste des codes pays ([ISO 3166-1-alpha-2](https://fr.wikipedia.org/wiki/ISO_3166)),
* une revue / correction de la liste des codes devise ([ISO 4217](https://fr.wikipedia.org/wiki/ISO_4217)),
* un alignement des définitions d’IBAN (ISO 13616) avec
  [IBAN Registry Release 86](https://www.iso13616.org/),
* le support des SEPA [Creditor Identifiers](https://www.europeanpaymentscouncil.eu/document-library/guidance-documents/creditor-identifier-overview),
* une modernisation du code et des pratiques de développement (support de Java, adoption de
  [SemVer](https://semver.org), mises à jour de dépendances…).

Pour la liste exhaustive des modifications vous pouvez consulter les
[notes de version](https://github.com/marcwrobel/jbanking/releases/tag/v2.0.0).

Pour utiliser cette nouvelle version rien de plus simple : téléchargez-la depuis [Maven
Central](https://search.maven.org/artifact/fr.marcwrobel/jbanking/2.0.0/jar) ou, plus simplement,
déclarez une nouvelle dépendance dans votre POM de la manière suivante :

    <dependency>
        <groupId>fr.marcwrobel</groupId>
        <artifactId>jbanking</artifactId>
        <version>2.0.0</version>
    </dependency> 

Un grand merci à [Charles Kayser (@ckayser)](https://github.com/ckayser), à [@opeti](https://github.com/opeti)
et à [Adrian Sutton (@ajsutton)](https://github.com/ajsutton) pour leur aide sur cette version !

*[IBAN]: International Bank Account Number
*[ISO]: International Organization for Standardization
*[SEPA]: Single Euro Payments Area
