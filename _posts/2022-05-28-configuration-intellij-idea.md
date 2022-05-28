---
layout: post
title: Configuration d’IntelliJ IDEA
category: développement
---

Quelques notes sur la configuration d’[IntelliJ IDEA](https://www.jetbrains.com/idea/).

## Plugins à installer

- [SonarLint](https://plugins.jetbrains.com/plugin/7973-sonarlint) pour l’intégration de l’outil d'analyse de code
  [SonarQube](https://www.sonarqube.org/).
- [String Manipulation](https://plugins.jetbrains.com/plugin/2162-string-manipulation) pour avoir sous la main de
  nombreuses routines de manipulation de chaines de caractères.

## Configuration

Avant d’ouvrir le moindre projet, configurer au préalable le comportement par défaut.

Pour cela dans _Configure_ → _Settings_ :

- cocher l’option _Enable annotation processing_ dans _File | Settings | Build, Execution, Deployment | Compiler |
  Annotation Processors_,
- cocher _Add unambiguous import on the fly_ dans _File | Settings | Editor | General | Auto Import_ (pour Java / JSP /
  TypeScript...),
- cocher _Optimize import on the fly_ dans _File | Settings | Editor | General | Auto Import_ (pour Java / JSP /
  TypeScript...),
- cocher _Ensure every saved file ends with a line break_ dans _File | Settings | Editor | General_,
- cocher _Transparent native-to-ascii conversion_ dans _File | Settings | Editor | File Encodings_,
- ajouter _Français_ à la liste des langages dans _File | Settings | Editor | Natural Languages_.

L'installation et la configuration des JDK se fait depuis _File | Project Structure | Platform Settings | SDKs_.
