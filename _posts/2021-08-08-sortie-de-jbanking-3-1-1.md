---
layout: post
title: Sortie de jbanking 3.1.1
category: développement
---

La version 3.1.1 de [jbanking](https://github.com/marcwrobel/jbanking) est sortie. Cette nouvelle version corrige quelques problèmes de validation du check
digit pour les IBAN et les identifiants créanciers (CI).

Pour la liste exhaustive des modifications vous pouvez consulter les
[notes de version](https://github.com/marcwrobel/jbanking/releases/tag/v3.1.1).

Pour utiliser cette nouvelle version rien de plus simple : téléchargez-la
depuis [Maven Central](https://search.maven.org/artifact/fr.marcwrobel/jbanking/3.1.1/jar) ou, plus simplement, déclarez une nouvelle dépendance dans votre POM
de la manière suivante :

    <dependency>
        <groupId>fr.marcwrobel</groupId>
        <artifactId>jbanking</artifactId>
        <version>3.1.1</version>
    </dependency>

*[CI]: Creditor Identifier
*[IBAN]: International Bank Account Number
*[POM]: Project Object Model
