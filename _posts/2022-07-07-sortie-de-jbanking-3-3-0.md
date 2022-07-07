---
layout: post
title: Sortie de jbanking 3.3.0
category: développement
---

La version 3.3.0 de [jbanking](https://github.com/marcwrobel/jbanking) est sortie. Cette nouvelle version inclue :

- le support officiel de Java 17 et 18,
- de nombreuses améliorations de la javadoc (cf. [javadoc.io](https://javadoc.io/doc/fr.marcwrobel/jbanking/)),
- diverses améliorations et corrections mineures.

De nombreux travaux ont aussi été effectués dans le cadre de
l'[OpenSSF Best Practices Badge Program](https://bestpractices.coreinfrastructure.org/en/projects/6217) et
dans le cadre du projet [Open Source Insights](https://deps.dev/maven/fr.marcwrobel%3Ajbanking) pour
améliorer la sécurité et la maintenabilité du projet.

Pour la liste exhaustive des modifications, vous pouvez consulter les
[notes de version](https://github.com/marcwrobel/jbanking/releases/tag/v3.3.0).

Pour utiliser cette nouvelle version rien de plus simple : téléchargez-la
depuis [Maven Central](https://search.maven.org/artifact/fr.marcwrobel/jbanking/3.3.0/jar) ou,
plus simplement, déclarez une nouvelle dépendance dans votre POM de la manière suivante :

```xml
<dependency>
  <groupId>fr.marcwrobel</groupId>
  <artifactId>jbanking</artifactId>
  <version>3.3.0</version>
</dependency>
```

<!-- prettier-ignore-start -->
*[POM]: Project Object Model
<!-- prettier-ignore-end -->
