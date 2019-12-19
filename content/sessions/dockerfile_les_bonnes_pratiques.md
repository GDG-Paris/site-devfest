---
key: dockerfile_les_bonnes_pratiques
title: "Dockerfile - Les bonnes pratiques"
id: ZKVz0OFf19i9AwN2GFq7
language: french
format: Conference
tags:
  - 'devops'

level: beginner
speakers:
  - j_r_mie_drouet
  - guillaume_lours

---

A partir d’un Dockerfile pris “au hasard” sur Github, comme un bon vieux monolithe, nous allons, en appliquant les bonnes pratiques, transformer cette application en un ensemble de microservices réutilisables et compréhensibles 

On commencera par externaliser les services utilisés par notre application en utilisant des images existantes et les associant dans un fichier Compose.

Nous allons optimiser notre premier jet en vidant les caches et en supprimant les layers inutiles générés lors du build de notre application.

On découpera les différentes étapes de build pour ne pas avoir à conserver les dépendances de développement dans l’image finale

Nous améliorerons la maintenabilité en utilisant des images officielles plutôt qu’en installant à la main nos dépendances.

Nous allons voir comment éviter de faire tourner notre application en tant que root.

