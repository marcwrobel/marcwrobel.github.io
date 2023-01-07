---
layout: post
title: Sortie de jbanking 4.1.0
description: La version 4.1.0 de jbanking est sortie avec le support la génération aléatoire d'IBAN (ISO 13616) et de grosses améliorations de performances.
category: développement
seo:
  date_modified: 2023-01-07
---

La version 4.1.0 de [jbanking](https://github.com/marcwrobel/jbanking) est sortie. Les modifications
suivantes sont incluses dans cette version :

- Dépréciation du kuna croate (HRK) suite à l'adoption par la Croatie de l’euro (EUR) comme monnaie
  unique (cf. [ISO 4217 Currency Code Service - Amendment number 174](https://www.six-group.com/dam/download/financial-information/data-center/iso-currrency/amendments/dl-currency-iso-amendment-174.pdf)).
- Ajout du 08/05/2023 (couronnement du roi Charles III) à la liste des jours fériés du calendrier
  prédéfini `LONDON`.

Quelques modifications d'ordre technique ont aussi été réalisées :

- La construction de jbanking est désormais [reproductible](https://reproducible-builds.org/). Cela
  signifie qu'il est dorénavant possible de vérifier facilement que le code ayant servi à construire
  une version donnée de jbanking est bien celui publié [sur GitHub](https://github.com/marcwrobel/jbanking/).
- jbanking publie désormais un SBOM au format [CycloneDX](https://cyclonedx.org/) sur Maven Central.
  Un SBOM permet de documenter, de manière structurée, les dépendances utilisées dans un projet.
  jbanking n'a aucune dépendance, mais ça ne fait pas de mal de le déclarer ;).

Pour utiliser cette nouvelle version rien de plus simple : téléchargez-la
depuis [Maven Central](https://search.maven.org/artifact/fr.marcwrobel/jbanking/4.1.0/jar) ou,
plus simplement, déclarez une nouvelle dépendance dans votre POM de la manière suivante :

```xml
<dependency>
  <groupId>fr.marcwrobel</groupId>
  <artifactId>jbanking</artifactId>
  <version>4.1.0</version>
</dependency>
```

Et si vous avez des questions, [rendez-vous sur GitHub](https://github.com/marcwrobel/jbanking/discussions/282) !

<!-- prettier-ignore-start -->
*[POM]: Project Object Model
*[SBOM]: Software Bill Of Materials
<!-- prettier-ignore-end -->
