---
title: "Ajouter un thème"
date: 2019-11-18T00:21:05+01:00
weight: 4
draft: false
---

Pour ajouter un thème, nous allons utiliser la notion de module de git est par la même occasion initialiser notre git dans le projet.

Pour installer git, nous utilisons une fois de plus scoop.

```
PS > scoop install git

PS > cd $HOME/un_site_avec_hugo

PS > git init .

PS > git submodule add https://github.com/matcornic/hugo-theme-learn.git themes/hugo-theme-learn
```

Ensuite, il nous faut éditer le fichier de configuration du projet qui peut-être dans différent format (YAML, TOML, JSON), dans mon cas c'est du TOML.
Renseignons le thème à utiliser dans config.toml.
```
# Edit config.toml
theme = "hugo-theme-learn"
```
Et c'est tout !

Il ne reste plus qu'à démarrer un serveur en local pour voir votre siteweb dans votre navigateur `localhost:1313` par défaut !
```
PS > hugo serve
```

Allez, après avoir :
- Initialiser le site avec hugo `new site un_site_avac_hugo`
- Initialiser git
- Installer le thème `hugo-theme-learn`comme un git sous-module.
- Paramétrer le config.toml
- Démarrer le serveur Hugo avec `hugo serve`

On va se faire une petite sauvegarde.
```
PS > git status
PS > git add --all
PS > git commit -m "Initial comit run hugo-theme-learn"
```