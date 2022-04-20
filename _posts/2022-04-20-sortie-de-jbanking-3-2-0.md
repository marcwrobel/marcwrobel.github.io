---
layout: post
title: Sortie de jbanking 3.2.0
category: développement
---

La version 3.2.0 de [jbanking](https://github.com/marcwrobel/jbanking) est sortie. Cette nouvelle version inclue :

- l'ajout des codes devise VED/926 et SLE/925 introduits par les amendements ISO-4217 n°170 et n°171,
- diverses corrections dans la documentation.

Pour la liste exhaustive des modifications, vous pouvez consulter les
[notes de version](https://github.com/marcwrobel/jbanking/releases/tag/v3.2.0).

Pour utiliser cette nouvelle version rien de plus simple : téléchargez-la
depuis [Maven Central](https://search.maven.org/artifact/fr.marcwrobel/jbanking/3.2.0/jar) ou, plus simplement, déclarez
une nouvelle dépendance dans votre POM de la manière suivante :

    <dependency>
        <groupId>fr.marcwrobel</groupId>
        <artifactId>jbanking</artifactId>
        <version>3.2.0</version>
    </dependency>

*[POM]: Project Object Model
