# Frontend de l'Application Web de Gestion de Produits

Ce projet constitue le frontend de notre application web de gestion de produits. Il s'agit d'une interface utilisateur développée avec Vue.js qui communique avec le backend pour afficher et gérer les produits.

## Prérequis

Avant de commencer, assurez-vous d'avoir Node.js installé sur votre système.

## Installation
Installez les dépendances nécessaires :
```
npm install
```

## Configuration

1. Assurez-vous que le backend de l'application est en cours d'exécution et qu'il est accessible à l'adresse spécifiée `localhost:5000`.

## Démarrage du serveur de développement

Une fois les dépendances installées et le backend configuré, vous pouvez démarrer le serveur de développement en exécutant la commande suivante :
```
npm run serve
```

Le serveur de développement démarrera et vous pourrez accéder à l'application dans votre navigateur à l'adresse suivante : `http://localhost:8080`.





# Backend de l'Application Web de Gestion de Produits

Ce projet constitue le backend de notre application web de gestion de produits. Il s'agit d'une API construite avec Express.js qui communique avec une base de données MongoDB pour gérer les opérations CRUD (Create, Read, Update, Delete) sur les produits.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé Node.js et MongoDB sur votre système.

## Installation

1. Installez les dépendances nécessaires :
    ```
    npm install
    ```

2. Configurez votre base de données MongoDB :
    - Assurez-vous que MongoDB est en cours d'exécution sur votre machine et d'avoir chargé les données nécessaires à l'aide du fichier `products_data.json`.
    - Vous pouvez modifier l'URL de connexion à MongoDB dans le fichier `server.js` si nécessaire.

## Démarrage du serveur

Une fois les dépendances installées et la base de données configurée, vous pouvez démarrer le serveur en exécutant la commande suivante :
```
npx nodemon 
```

Le serveur démarrera sur le port par défaut 5000. Vous pouvez accéder à l'API à l'adresse suivante : `http://localhost:5000`.