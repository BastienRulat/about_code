---
title: "Installer Hugo"
date: 2019-11-17T18:49:34+01:00
draft: false
---

Pour installer Hugo sous WIndows 10, nous allons passer par le gestionnaire de paquet scoop.

Ouvrons un terminal (comme `cmder`) muni d'un interpréteur PowerShell ou PowerShell Core et récupérons scoop :

```
PS > iwr -useb get.scoop.sh | iex
```

Ensuite, on utilise scoop pour installer hugo

```
PS > scoop install hugo
```

Vérifions que hugo a bien été installé par scoop :

```
PS > hugo version
```