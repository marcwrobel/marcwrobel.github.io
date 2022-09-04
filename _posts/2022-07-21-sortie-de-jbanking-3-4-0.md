---
layout: post
title: Sortie de jbanking 3.4.0
category: développement
---

La version 3.4.0 de [jbanking](https://github.com/marcwrobel/jbanking) est sortie. Cette nouvelle version inclue :

- l’ajout du support des IBANs Burundais (BI), Djiboutien (DJ), Russe (RU) et Soudanais (SD),
- encore des améliorations liées à la documentation,
  notamment [la javadoc](https://javadoc.io/doc/fr.marcwrobel/jbanking/),
- l’ajout des méthodes `Bic#getCountry()`, `Iban#getCountry()` et `CreditorIdentifier#getCountry()` que retournent
  directement un `IsoCountry` (en complément des méthodes `getCountryCode()`).

Pour la liste exhaustive des modifications, vous pouvez consulter les
[notes de version](https://github.com/marcwrobel/jbanking/releases/tag/v3.4.0).

Pour utiliser cette nouvelle version rien de plus simple : téléchargez-la
depuis [Maven Central](https://search.maven.org/artifact/fr.marcwrobel/jbanking/3.4.0/jar) ou,
plus simplement, déclarez une nouvelle dépendance dans votre POM de la manière suivante :

```xml

<dependency>
  <groupId>fr.marcwrobel</groupId>
  <artifactId>jbanking</artifactId>
  <version>3.4.0</version>
</dependency>
```

<!-- prettier-ignore-start -->
*[POM]: Project Object Model
<!-- prettier-ignore-end -->
