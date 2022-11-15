---
layout: post
title: Sortie de jbanking 1.0
description: La version 1.0 de jbanking est sortie avec le support des codes BIC (ISO 9362), IBAN (ISO 13616), pays (ISO 3166-1) et devises (ISO 4217).
category: développement
---

La version 1.0 de [jbanking](https://github.com/marcwrobel/jbanking) est sortie. Cette version initiale du projet
inclue :

- le support des codes BIC ([ISO 9362](https://fr.wikipedia.org/wiki/ISO_9362)),
- le support des IBAN ([ISO 13616](https://fr.wikipedia.org/wiki/ISO_13616)),
- le support des codes pays ([ISO 3166-1-alpha-2](https://fr.wikipedia.org/wiki/ISO_3166)),
- le support des codes devise ([ISO 4217](https://fr.wikipedia.org/wiki/ISO_4217)).

Pour plus d’informations vous pouvez consulter
les [notes de version](https://github.com/marcwrobel/jbanking/releases/tag/jbanking-1.0).

Pour utiliser cette version rien de plus simple : téléchargez-la
depuis [Maven Central](https://search.maven.org/artifact/fr.marcwrobel/jbanking/1.0/jar)
ou, plus simplement, déclarez une nouvelle dépendance dans votre POM de la manière suivante :

```xml
<dependency>
  <groupId>fr.marcwrobel</groupId>
  <artifactId>jbanking</artifactId>
  <version>1.0</version>
</dependency>
```

Toute aide est la bienvenue ! Si vous souhaitez contribuer rendez-vous
sur [le dépôt GitHub de jbanking](https://github.com/marcwrobel/jbanking).

<!-- prettier-ignore-start -->
*[BIC]: Bank Identifier Code
*[IBAN]: International Bank Account Number
*[ISO]: International Organization for Standardization
*[POM]: Project Object Model
<!-- prettier-ignore-end -->
