---
layout: post
title: Sortie de jbanking 3.0.0
category: développement
---

La version 3.0.0 de [jbanking](https://github.com/marcwrobel/jbanking) est sortie. Cette nouvelle version inclue :

- un alignement des définitions d’IBAN (ISO 13616) avec IBAN Registry Release 88 (septembre 2020),
- une revue et une amélioration de la Javadoc des enumerations `IsoCountry` (ISO 3166) et `IsoCurrency` (ISO 4217),
- des améliorations de l’API `Calendar` (nouvelles méthodes, CompositeCalendar),
- quelques corrections des définitions de devises,
- des modifications pour rendre jbanking _serializable-friendly_.

Cette nouvelle version majeure a aussi été l’occasion d’introduire des changements non-compatibles avec les versions
précédentes. Ainsi :

- les méthodes dépréciées dans les versions précédentes ont été supprimées,
- les entrées des enums `IsoCountry` et `IsoCurrency` ont été renommées d’après leur code alphabétique,
- certaines signatures des méthodes de `IsoCurrency` et de `Calendar` ont été modifiées,
- la visibilité de l’énumération `BbanStructure` a été modifiée à _package-private_ plutôt que _public_.

Pour la liste exhaustive des modifications, vous pouvez consulter les
[notes de version](https://github.com/marcwrobel/jbanking/releases/tag/v3.0.0).

Pour utiliser cette nouvelle version rien de plus simple : téléchargez-la
depuis [Maven Central](https://search.maven.org/artifact/fr.marcwrobel/jbanking/3.0.0/jar) ou, plus simplement, déclarez
une nouvelle dépendance dans votre POM de la manière suivante :

    <dependency>
        <groupId>fr.marcwrobel</groupId>
        <artifactId>jbanking</artifactId>
        <version>3.0.0</version>
    </dependency>

*[API]: Application Programming Interface
*[IBAN]: International Bank Account Number
*[ISO]: International Organization for Standardization
*[POM]: Project Object Model
