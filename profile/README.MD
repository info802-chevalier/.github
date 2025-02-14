Chevalier Clément - M1 INFO

# Organisation du Projet

Ce projet est divisé en deux parties distinctes : un front-end et un back-end. Chaque partie a son propre dépôt GitHub, mais elles fonctionnent ensemble pour offrir une solution complète.

### Résumé du Projet

Le projet vise à offrir une application web moderne et interactive, qui se connecte à une API back-end pour récupérer des données en temps réel. Le front-end est conçu avec des technologies modernes (JavaScript, Webpack, Babel) et se connecte à l'API via des appels HTTP. Le back-end, construit avec **Flask** et **Flask-RESTful**, expose des points d'entrée RESTful permettant de récupérer et manipuler les données nécessaires à l'application.

L'objectif est de fournir une interface utilisateur fluide, avec des données dynamiques alimentées par le serveur, tout en permettant une gestion flexible des ressources via l'API.

---

### Déploiement

#### Front-End

- **URL de l'application front-end** : [https://frontend-three-nu-27.vercel.app/](https://frontend-three-nu-27.vercel.app/)

Le front-end est une application web responsive qui se connecte à l'API back-end pour afficher des données dynamiques. Il utilise **React** (ou une autre bibliothèque/technologie selon le cas) et **Webpack** pour le bundling et la gestion du code.

#### Back-End

- **URL de l'API back-end** : [https://backend-tau-plum.vercel.app/api](https://backend-tau-plum.vercel.app/api)

Le back-end est une API RESTful construite avec **Flask** et **Flask-RESTful**. Elle fournit des points d'entrée permettant d'interagir avec les données, gérer des ressources et effectuer des opérations côté serveur. La documentation de l'API est accessible via l'URL ci-dessus.

---

### Structure du Projet

Le projet est composé de deux repos distincts, chacun responsable d'une partie du système :

1. **Front-End** : 
   - Projet du côté client, responsable de l'interface utilisateur et de l'interaction avec l'utilisateur.
   - Déployé sur Vercel, accessible à l'adresse [https://frontend-three-nu-27.vercel.app/](https://frontend-three-nu-27.vercel.app/).

2. **Back-End** : 
   - API construite avec Flask, exposant des points d'entrée RESTful pour la gestion des données et des opérations côté serveur.
   - Déployé sur Vercel, avec la documentation accessible à l'adresse [https://backend-tau-plum.vercel.app/api](https://backend-tau-plum.vercel.app/api).

---

### Fonctionnalités Principales

- **Front-End** :
  - Interface utilisateur moderne et responsive.
  - Consommation des données via l'API RESTful.
  - Affichage dynamique des informations récupérées du back-end.

- **Back-End** :
  - API RESTful construite avec **Flask** et **Flask-RESTful**.
  - Points d'entrée sécurisés pour interagir avec les données.
  - Documentation de l'API générée automatiquement pour une utilisation facile.
