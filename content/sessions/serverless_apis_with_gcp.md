---
key: serverless_apis_with_gcp
title: 'Serverless APIs with GCP'
id: rD8nxmpgtVgv48f6o53N
language: french
format: Codelab
tags:
  - 'cloud'

level: advanced
speakers:
  - seifeddin_mansri

---

Et si on avait la possibilité de créer une API 100% serverless, qui couvrirait à la fois la spécification et les environnements d'exécution?

A travers ce Codelab, nous vous proposo la mise en oeuvre de cette architecture à travers la Google Cloud Platform (GCP) en utilisant des produits serverless et entièrement gérés par la plateforme.

Dans un premier temps, nous commencerons par le déploiement de la spécification en OpenApi de notre API dans Cloud Endpoints.

Ensuite nous allons déployer trois backends complètements différents (Langage, Environnement d'exécution...) :
- Backend-1 en Go sur Cloud Run (Solution CaaS).
- Backend-2 en Java sur Cloud Functions (Solution FaaS).
- Backend-3 en Python sur AppEngine Standard (Solution PaaS).

Nous terminerons par la mise en place des fonctionnalités avancées comme :
- La restriction des accès aux différents environnements d'exécutions pour qu'ils soient appelés uniquement à travers notre API.
- La mise en place de l'authentification pour sécuriser les appels externes.
- La définition de quotas pour se prémunir des sollicitations excessives des différents endpoints.
- La génération d'un portail développeur.

