---
layout: post
title: Sortie de jbanking 4.2.0
description: Support de Java 21, génération aléatoire de BIC et amélioration de la génération aléatoire d'IBAN.
category: développement
seo:
  date_modified: 2023-11-27
---

La version 4.2.0 de [jbanking](https://github.com/marcwrobel/jbanking) est sortie. Les modifications
suivantes sont incluses dans cette version :

- Support officiel de Java 21.
- Ajout de la possibilité de générer aléatoirement des BIC.
- Amélioration de la génération aléatoire d’IBAN.

Pour utiliser cette nouvelle version rien de plus simple : téléchargez-la
depuis [Maven Central](https://central.sonatype.com/artifact/fr.marcwrobel/jbanking/4.2.0) ou,
plus simplement, déclarez une nouvelle dépendance dans votre POM de la manière suivante :

```xml
<dependency>
  <groupId>fr.marcwrobel</groupId>
  <artifactId>jbanking</artifactId>
  <version>4.2.0</version>
</dependency>
```

Et si vous avez des questions, [rendez-vous sur GitHub](https://github.com/marcwrobel/jbanking/discussions/372) !

<!-- prettier-ignore-start -->
*[POM]: Project Object Model
*[SBOM]: Software Bill Of Materials
<!-- prettier-ignore-end -->
