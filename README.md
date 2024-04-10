# TP: Automatisation des Données YouTube Analytics avec JavaScript

Ce TP vise à enseigner les bases de l'automatisation en JavaScript en utilisant l'API YouTube Data pour récupérer les données Analytics d'une chaîne YouTube et les envoyer par e-mail sous forme de fichier Excel.

## Objectifs d'apprentissage

À la fin de ce TP, vous serez capable de :
- Interagir avec l'API YouTube Data.
- Manipuler des données et créer des fichiers Excel avec JavaScript.
- Envoyer des e-mails programmés avec des pièces jointes via Node.js.
- Automatiser des tâches périodiques avec `node-cron`.

## Prérequis

- Node.js et npm installés => ok
- Connaissances de base en JavaScript.
- Un compte Google avec accès à l'API YouTube Data.
- Un serveur SMTP pour l'envoi d'e-mails (comme Gmail).

## Étapes du TP

### Étape 1: Configuration de l'Environnement

1. Cloner ce répertoire.
2. Installer les dépendances avec `npm install`.

### Étape 2: Authentification à l'API YouTube Data

1. Lire la documentation sur l'authentification OAuth 2.0.
2. Configurer un projet et obtenir vos identifiants sur la console Google Cloud.
3. Écrire le script d'authentification.

### Étape 3: Récupération des Données Analytics

1. Explorer la documentation de l'API YouTube Analytics.
2. Écrire la fonction pour récupérer les statistiques désirées de votre chaîne YouTube.

### Étape 4: Création d'un Fichier Excel

1. Apprendre à utiliser la bibliothèque `xlsx`.
2. Créer et formater un fichier Excel avec les données récupérées.

### Étape 5: Envoi des Données par Email

1. Configurer `nodemailer` avec votre serveur SMTP.
2. Écrire une fonction pour envoyer le fichier Excel en pièce jointe.

### Étape 6: Automatisation

1. Programmer l'exécution du script à l'aide de `node-cron`.

## Ressources

- [Documentation API YouTube Data](https://developers.google.com/youtube/v3)
- [Documentation `xlsx`](https://github.com/SheetJS/sheetjs)
- [Documentation `nodemailer`](https://nodemailer.com/about/)
- [Documentation `node-cron`](https://www.npmjs.com/package/node-cron)

## Consignes de travail

Suivez les instructions détaillées dans le dossier `instructions` où chaque étape est expliquée en détail avec des exemples de code et des exercices.

## Évaluation

Vous serez évalué sur :
- La qualité et la clarté de votre code.
- Votre compréhension des concepts mis en œuvre.
- La réussite de l'automatisation de la tâche finale.

## Contribution

Si vous avez des questions ou des suggestions, n'hésitez pas à ouvrir une "issue" ou à soumettre un "pull request".

## Licence

[MIT](
