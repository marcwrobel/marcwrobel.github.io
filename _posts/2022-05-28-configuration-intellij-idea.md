---
layout: post
title: Configuration d’IntelliJ IDEA
category: développement
---

Quelques notes sur la configuration d’[IntelliJ IDEA](https://www.jetbrains.com/idea/).

Avant d’ouvrir le moindre projet, installer les plugins suivants depuis l'onglet _Plugins_ de l'écran de démarrage :

- [SonarLint](https://plugins.jetbrains.com/plugin/7973-sonarlint) pour l’intégration de l’outil d'analyse de code
  [SonarQube](https://www.sonarqube.org/).
- [String Manipulation](https://plugins.jetbrains.com/plugin/2162-string-manipulation) pour avoir sous la main de
  nombreuses routines de manipulation de chaines de caractères.

Puis configurer le comportement par défaut depuis l'onglet  _Customize_ (lien _All Settings_) de l'écran de démarrage :

- cocher l’option _Enable annotation processing_ dans _File > Settings > Build, Execution, Deployment > Compiler >
  Annotation Processors_,
- cocher _Add unambiguous import on the fly_ dans _File > Settings > Editor > General > Auto Import_ (pour Java /
  Kotlin...),
- cocher _Optimize import on the fly_ dans _File > Settings > Editor > General > Auto Import_ (pour Java / Kotlin...),
- cocher _Ensure every saved file ends with a line break_ dans _File > Settings > Editor > General_,
- cocher _Change font size with Control+Mouse Wheel in_ dans _File | Settings | Editor | General_,
- cocher _Transparent native-to-ascii conversion_ dans _File > Settings > Editor > File Encodings_,
- ajouter _Français_ à la liste des langages dans _File > Settings > Editor > Natural Languages_.

Il faudra ensuite ouvrir un projet pour pouvoir :

- configurer les SDK depuis _File > Project Structure > Platform Settings > SDKs_,
- créer un raccourci de bureau grâce au menu _Tools / Create Desktop Entry_,
- créer un script de démarrage en ligne de commande grâce au menu _Tools / Create Command-Line Launcher_.
