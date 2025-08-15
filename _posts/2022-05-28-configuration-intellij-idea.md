---
layout: post
title: Configuration d’IntelliJ IDEA
category: développement
seo:
  date_modified: 2025-08-15
---

Quelques notes sur ma configuration d’[IntelliJ IDEA](https://www.jetbrains.com/idea/) (et autre IDE JetBrains).

Tout d'abord installer [JetBrains Toolbox](https://www.jetbrains.com/toolbox-app/) :
cela facilite grandement les choses tant pour l'installation que pour les mises à jour.

Puis, avant d’ouvrir le moindre projet, installer ou activez les plugins suivants depuis l'onglet _Plugins_ de l'écran de démarrage :

- [.env files](https://plugins.jetbrains.com/plugin/9525--env-files),
- [.ignore](https://plugins.jetbrains.com/plugin/7495--ignore),
- [Developer Tools](https://plugins.jetbrains.com/plugin/21904-developer-tools),
- [GitHub Copilot](https://plugins.jetbrains.com/plugin/17718-github-copilot),
- [Makefile Language](https://plugins.jetbrains.com/plugin/9333-makefile-language)
- [Python Community Edition](https://plugins.jetbrains.com/plugin/7322-python-community-edition),
- [SonarQube for IDE](https://plugins.jetbrains.com/plugin/7973-sonarlint).

Puis configurer le comportement par défaut depuis l'onglet  _Customize_ (lien _All Settings_) de l'écran de démarrage :

- décocher l'option _Reopen projects on startup_ dans _File \| Settings \| Appearance & Behavior \| System Settings_,
- cocher l’option _Enable annotation processing_ dans _File \| Settings \| Build, Execution, Deployment \| Compiler \| Annotation Processors_,
- cocher _Add unambiguous import on the fly_ et _Optimize import on the fly_ dans _File \| Settings \| Editor \| General \| Auto Import_,
- cocher _Ensure every saved file ends with a line break_ et _Remove trailing blank lines at the end of saved files_ dans _File \| Settings \| Editor \| General_,
- cocher _Change font size with Control+Mouse Wheel in_ dans _File \| Settings \| Editor \| General_,
- cocher _Transparent native-to-ascii conversion_ dans _File \| Settings \| Editor \| File Encodings_,
- ajouter _Français_ à la liste des langages dans _File \| Settings \| Editor \| Natural Languages_.

Il faudra ensuite ouvrir un projet pour pouvoir configurer les SDK depuis _File \| Project Structure_.
