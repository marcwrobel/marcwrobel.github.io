---
layout: post
title: Sortie de jbanking 3.1.0
category: développement
---

La version 3.1.0 de [jbanking](https://github.com/marcwrobel/jbanking) est sortie. Cette nouvelle version inclue :

- une catégorisation des devises ISO pour permettre un filtrage des devises en fonction du domaine d’utilisation :
  - `NATIONAL` : devises nationales ou supranationales, telles que _EUR_ ou _USD_,
  - `BOND` : unités de marché obligataire, telles que [XBB](https://wikipedia.org/wiki/European_Unit_of_Account),
  - `FUND` : fonds, tels
    que [USN](https://en.wikipedia.org/wiki/ISO_4217#USD/USS/USN,_three_currency_codes_belonging_to_the_US),
  - `METAL` : métaux précieux, tels que [XAU](https://wikipedia.org/wiki/Gold_as_an_investment),
  - `OTHER` : devises non catégorisées, telles que XUA, XXX, XDR.
- l’ajout d’un calendrier prédéfini pour le quartier d’affaires de Tokyo,
- la modification du calendrier prédéfini pour le quartier d’affaires de Londres pour y supporter
  le [platinum jubilee](https://www.bbc.com/news/uk-54911550),
- des améliorations de l’API Calendar (nouvelles méthodes, ajout de `BridgedHoliday`),
- l’ajout de la
  devise [UYW (Unidad Previsional)](https://www.currency-iso.org/en/shared/amendments/iso-4217-amendment.html) à la
  liste des devises supportées.

Pour la liste exhaustive des modifications, vous pouvez consulter les
[notes de version](https://github.com/marcwrobel/jbanking/releases/tag/v3.1.0).

Pour utiliser cette nouvelle version rien de plus simple : téléchargez-la
depuis [Maven Central](https://search.maven.org/artifact/fr.marcwrobel/jbanking/3.1.0/jar) ou, plus simplement, déclarez
une nouvelle dépendance dans votre POM de la manière suivante :

```xml
<dependency>
  <groupId>fr.marcwrobel</groupId>
  <artifactId>jbanking</artifactId>
  <version>3.1.0</version>
</dependency>
```

<!-- prettier-ignore-start -->
*[API]: Application Programming Interface
*[ISO]: International Organization for Standardization
*[POM]: Project Object Model
<!-- prettier-ignore-end -->
