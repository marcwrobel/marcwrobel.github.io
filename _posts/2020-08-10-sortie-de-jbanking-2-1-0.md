---
layout: post
title: Sortie de jbanking 2.1.0
category: développement
---

La version 2.1.0 de [jbanking](https://github.com/marcwrobel/jbanking) est sortie. Cette nouvelle
version inclue :
- un alignement des définitions d’IBAN (ISO 13616) avec [IBAN Registry Release 87](https://www.iso13616.org/) (mai 2020),
- des améliorations autour de l’enum IsoCountry :
  - ajout des codes ISO 3166-1 alpha-3,
  - ajout des codes numériques ISO 3166-1,
  - ajout du statut des pays (independent ou dépendent),
  - ajout de la participation des pays à certains accords : Single Euro Payments Area (SEPA), Union
    Européenne (UE), European Economic Area (EEA), SEPA COM Pacifique et European Free Trade
    Association (EFTA).
- le support configurable de calcul des jours ouvré avec quelques calendriers prédéfinis :
  - Quartiers d’affaires de Francfort, Londres, Paris et Sydney,
  - Federal Reserve Bank of New York (FED),
  - New York Stock Exchange (NYSE),
  - Trans-European Automated Real-time Gross Settlement Express Transfer System (TARGET).

Pour la liste exhaustive des modifications vous pouvez consulter les
[notes de version](https://github.com/marcwrobel/jbanking/releases/tag/v2.1.0).

Pour utiliser cette nouvelle version rien de plus simple : téléchargez-la depuis [Maven
Central](https://search.maven.org/artifact/fr.marcwrobel/jbanking/2.1.0/jar) ou, plus simplement,
déclarez une nouvelle dépendance dans votre POM de la manière suivante :

    <dependency>
        <groupId>fr.marcwrobel</groupId>
        <artifactId>jbanking</artifactId>
        <version>2.1.0</version>
    </dependency> 

Un grand merci à [Matthias Kay (@kayman-mk)](https://github.com/kayman-mk) pour son aide sur cette
version !

*[IBAN]: International Bank Account Number
*[ISO]: International Organization for Standardization
*[POM]: Project Object Model
