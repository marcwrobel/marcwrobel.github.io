---
layout: post
title: Sortie de jbanking 4.0.0
description: La version 4.0.0 de jbanking est sortie avec le support la génération aléatoire d'IBAN (ISO 13616) et de grosses améliorations de performances.
category: développement
---

La version 4.0.0 de [jbanking](https://github.com/marcwrobel/jbanking) est sortie. Cette nouvelle version apporte de
[nombreuses améliorations](https://github.com/marcwrobel/jbanking/releases/tag/v4.0.0), dont notamment :

- l'ajout de la génération aléatoire d'IBAN avec la classe `RandomIban`,
- l’ajout des méthodes `getBankIdentifier()`, `getBranchIdentifier()`, `getAccountNumber()`, `getNationalCheckDigit()`
  à la classe `Iban`,
- de [grosses améliorations des performances](https://github.com/marcwrobel/jbanking/tree/main/benchmarks),
- et encore de nombreuses améliorations liées à la documentation.

Attention, cette version est une version majeure. Prenez le temps de consulter la liste exhaustive des
_breaking changes_ disponible dans les [notes de version](https://github.com/marcwrobel/jbanking/releases/tag/v4.0.0).

Pour utiliser cette nouvelle version rien de plus simple : téléchargez-la
depuis [Maven Central](https://search.maven.org/artifact/fr.marcwrobel/jbanking/4.0.0/jar) ou,
plus simplement, déclarez une nouvelle dépendance dans votre POM de la manière suivante :

```xml

<dependency>
  <groupId>fr.marcwrobel</groupId>
  <artifactId>jbanking</artifactId>
  <version>4.0.0</version>
</dependency>
```

Et si vous avez des questions, [rendez-vous sur GitHub](https://github.com/marcwrobel/jbanking/discussions) !

<!-- prettier-ignore-start -->
*[POM]: Project Object Model
<!-- prettier-ignore-end -->
