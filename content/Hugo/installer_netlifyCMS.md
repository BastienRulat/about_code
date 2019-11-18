---
title: "Installer Netlify CMS"
date: 2019-11-18T01:48:52+01:00
weight: 5
draft: false
---

Pour gérer le contenu de notre site, nous allons utiliser l'approche des CMS headless. ici nous utiliserons netlify CMS. 
Pour installer Netlify CMS, il suffit de créer un répertoire admin à la racine de notre site et d'y mettre deux fichiers :
- index.html
```
<!doctype html>
<html>
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Content Manager</title>
</head>
<body>
  <!-- Include the script that builds the page and powers Netlify CMS -->
  <script src="https://unpkg.com/netlify-cms@^2.0.0/dist/netlify-cms.js"></script>
</body>
</html>
```
- config.yml
```

```