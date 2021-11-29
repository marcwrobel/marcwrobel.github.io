---
layout: post
title: PGP, GPG et SSH
category: administration
tags: administration linux debian
---

De nombreuses opérations nécessitent l’utilisation d’une clé SSH ou d’une clé GPG.

Pour faciliter la gestion de ces clés il est possible de centraliser l’ensemble dans une clé GPG.

Pour cela on utilisera une clé GPG, une sous-clé GPG avec l'option authenticate en guise de clé SSH, et le gpg-agent
--enable-ssh-support.


*[GPG]: GNU Privacy Guard
*[PGP]: Pretty Good Privacy
*[SSH]: Secure SHell
