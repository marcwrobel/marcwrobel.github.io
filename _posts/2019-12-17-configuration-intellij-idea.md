---
layout: post
title: Configuration d'IntelliJ IDEA
category: développement
tags: développement outil ide intellij-idea
---

Quelques notes sur la configuration d’[IntelliJ IDEA](https://www.jetbrains.com/idea/).

## Plugins à installer
- [Lombok](https://plugins.jetbrains.com/plugin/6317-lombok-plugin)
- [GMavenPlus](https://plugins.jetbrains.com/plugin/7442-gmavenplus-intellij-plugin)
- [google-java-format](https://plugins.jetbrains.com/plugin/8527-google-java-format)
- [SonarLint](https://www.sonarlint.org/intellij/)
- [Zero Width Characters locator 2](https://plugins.jetbrains.com/plugin/12735-zero-width-characters-locator-2/)
- [Grazie](https://plugins.jetbrains.com/plugin/12175-grazie/)

## Configuration
Avant d'ouvrir le moindre projet, configurer au préalable le comportement par défaut.

Pour cela dans _Configure_ → _Settings_ :
- cocher _Build, Execution, Deployment_ → _Compiler_ → _Annotation Processors_ → _Enable annotation
  processing_,
- cocher _Editor_ → _General_ → _Auto Import_ → _Add unambiguous import on the fly_ (pour Java / JSP
  / TypeScript),
- cocher _Editor_ → _General_ → _Auto Import_ → _Optimize import on the fly_,
- cocher _Editor_ → _General_ → _Ensure line feed at file end on Save_,
- cocher _Editor_ → _File Encodings_ → _Transparent native-to-ascii conversion_,
- ajouter _French_ à la liste dans _Tools_ → _Grazie_ → _Languages_,
- cocher _Tools_ → _Grazie_ → _Enable Grazie Spellchecker_,
- cocher _Other Settings_ → _google-java-format Settings_ → _Enable google-java-format_,
- configurer [intellij-java-google-style.xml](https://raw.githubusercontent.com/google/styleguide/gh-pages/intellij-java-google-style.xml)
  dans _Editor_ → _Code Style_ (cf. [Gerrit Code Review - IntelliJ IDEA Setup](https://gerrit-review.googlesource.com/Documentation/dev-intellij.html#_code_style)).

Enfin configurer les JDK ainsi que le JDK à utiliser par défaut dans _Configure_ → _Structure for
new projects_.
