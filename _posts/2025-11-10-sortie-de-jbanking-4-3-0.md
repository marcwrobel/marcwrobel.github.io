---
layout: post
title: Sortie de jbanking 4.3.0
description: Support de ISO 9362:2022, ajout des devises XAD et ZWG.
category: développement
seo:
  date_modified: 2025-11-10
---

La version 4.3.0 de [jbanking](https://github.com/marcwrobel/jbanking) est sortie. Les modifications
suivantes sont incluses dans cette version :

- Support des caractères numeriques dans les _institution codes_ des codes BIC,
  conformément à la norme [ISO 9362:2022](https://cdn.standards.iteh.ai/samples/84108/21078408ed25469391d0cf6c5d1b6ca9/ISO-9362-2022.pdf),
- Modification de `IsoCurrency` suite aux amendements numéro 175 / 177 /178 / 179 de la norme ISO 4217 :
  - Support des devises [XAD (Dinar comptable arabe)](https://fr.wikipedia.org/wiki/Dinar_arabe)
    et [ZWG (or du Zimbabwe)](https://fr.wikipedia.org/wiki/Or_du_Zimbabwe),
  - Dépreciation des devises [CUC (peso cubain convertible)](https://fr.wikipedia.org/wiki/Peso_cubain_convertible),
    [ZWL (Dollar du Zimbabwe)](https://fr.wikipedia.org/wiki/Dollar_du_Zimbabwe) et
    [SLL (leone)](https://fr.wikipedia.org/wiki/Leone_(monnaie)).

Pour utiliser cette nouvelle version rien de plus simple : téléchargez-la
depuis [Maven Central](https://central.sonatype.com/artifact/fr.marcwrobel/jbanking/4.3.0) ou,
plus simplement, déclarez une nouvelle dépendance dans votre POM de la manière suivante :

```xml
<dependency>
  <groupId>fr.marcwrobel</groupId>
  <artifactId>jbanking</artifactId>
  <version>4.3.0</version>
</dependency>
```

Et si vous avez des questions, [rendez-vous sur GitHub](https://github.com/marcwrobel/jbanking/discussions/507) !

<!-- prettier-ignore-start -->
*[BIC]: Bank Identifier Code
*[ISO]: International Organization for Standardization
<!-- prettier-ignore-end -->
