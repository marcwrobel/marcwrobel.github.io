---
layout: post
title: Maven
category: développement
tags: développement java maven
---

## Configuration projet
Dans les projets, ajouter un répertoire .mvn contenant les fichiers suivants :

.mvn/maven.config :
```bash
--errors # Produce execution error messages
--strict-checksums # Error if checksums don't match
--show-version # Display version information WITHOUT stopping build
```

.mvn/jvm.config :
```bash
-Xmx128m
-Dorg.slf4j.simpleLogger.log.org.apache.maven.cli.transfer.Slf4jMavenTransferListener=WARN # only effective in batch mode - https://stackoverflow.com/questions/21638697/disable-maven-download-progress-indication
-Dorg.slf4j.simpleLogger.showDateTime=true # turn on the default timestamps (milliseconds since start)
-Djava.awt.headless=true # no GUI
```

Et éventuellement un .mvn/settings.xml pour la CI.

## Liens
Quelques liens intéressants :
* [10 Maven Security Best Practices](https://snyk.io/blog/10-maven-security-best-practices/)
