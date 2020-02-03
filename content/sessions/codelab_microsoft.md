---
key: codelab_microsoft
title: 'Microsoft : Envoyez la Nitro, construisez une API serverless avec Nest.js à toute vitesse !'
format: Codelab
tags:
  - discovery
level: beginner
speakers:
  - wassim_chegham
  - yohan_lasorsa

---

Faire une API en TypeScript ? La déployer en toute confiance, sans Docker, Kubernetes etc ? Et à moindre coût ?

Et oui on n’est plus en 2009, c’est possible de faire un backend Node.js qui tient la route aujourd’hui !

Découvrons ensemble Nest.js, le framework à base de TypeScript et inspiré d’Angular qui monte à toute vitesse grâce à
sa simplicité, sa rapidité et sa robustesse. Pour cela, nous allons construire une API REST complète qui sera enrichie
au fur et à mesure : connection d'une base de données, upload de fichiers et authentification, tout cela deployé dans
le cloud et sans toucher à un seul serveur.

Prérequis (pour gagner du temps au démarrage) :

Pour suivre cet atelier, vous aurez besoin des outils suivants :

* Un laptop avec connexion internet
* Un environment [Node.js](https://nodejs.org/) fonctionnel (dernière version LTS recommandée)
* La [CLI Azure](https://docs.microsoft.com/cli/azure/install-azure-cli?view=azure-cli-latest?WT.mc_id=nitro-workshop-yolasors) pour créer des resources sur Azure. Si vous ne souhaitez pas l’installer en local, il est possible d’utiliser [shell.azure.com](https://shell.azure.com/?WT.mc_id=nitro-workshop-yolasors)
* Les [Azure Functions Core Tools](https://docs.microsoft.com/azure/azure-functions/functions-run-local#v2?WT.mc_id=nitro-workshop-yolasors) pour tester vos fonctions en local
* Un éditeur de code de votre choix. Si vous n'en avez pas, vous pouvez installer [Visual Studio Code](https://code.visualstudio.com/?WT.mc_id=nitro-workshop-yolasors)

Un compte Azure est aussi nécessaire pour créer les resources et déployer votre application.

Des pass seront distribué pendant l’atelier pour créer un compte incluant du crédit préchargé.

Si vous le souhaitez, vous pouvez aussi [en créer un ici](https://azure.microsoft.com/free/?WT.mc_id=nitro-workshop-yolasors) qui comprend des crédits offerts (bien plus que nécessaire pour l’atelier).
