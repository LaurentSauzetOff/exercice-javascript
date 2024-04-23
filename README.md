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

## Attendus et problématique

Voilà le problème à laquelle le script global doit répondre. Je dois envoyer les données analytics de ma chaine youtube à une personne qui gère les relations avec les créateurs de contenus au sein de Playstation France. L'objectif est de récupérer chaque mois ces données, les transformer en classeur excel avec différentes feuilles et envoyer ce classeur en pièce-jointe d'un mail qui sera généré par le script ET envoyé via un compte gmail. Pour plus d'infos contactes-moi si besoin

## Étapes du TP

### Étape 1: Configuration de l'Environnement

1. Cloner ce répertoire.
2. Installer les dépendances avec `npm install`.

### Étape 2: Authentification à l'API YouTube Data

1. Lire la documentation sur l'authentification OAuth 2.0.
2. Comprendre comment Configurer un projet et obtenir vos identifiants sur la console Google Cloud (lire ici https://cloud.google.com/resource-manager/docs/creating-managing-projects?hl=fr)
3. M'envoyer un message pour que je te donnes les données d'authentification liées à cet exercice une fois que tu auras comprises la théorie.

### Etape 2.5 : Rédiger toute la logique en pseudo-code

A ce stade tu devrais avoir les infos nécessaires pour créer la logique complète du script en pseudo-code. Il faut vraiment y aller étape par étape, détailler correctement toute ta logique et
ne pas coder mais plutot écrire genre :
fonction recuperer-données () {
SI () ALORS ...
}

Tu sais que tu as trois grandes parties : récupération des données, transformation des données puis enfin création et envoi du mail. Sers-t'en comme structure de ta logique en pseudo code.
A ce stade il est important que tu mette à jour le dépot git au fur et à me sure pour que je comprenne comment tu avances et à quels endroits tu peux etre bloquée.

### Étape 3: Récupération des Données Analytics

1. Explorer la documentation de l'API YouTube Analytics (doc ici https://developers.google.com/youtube/analytics?hl=fr et ici https://developers.google.com/youtube/v3/docs?hl=fr)
2. Écrire la fonction pour récupérer les statistiques désirées de la chaîne YouTube.

### Étape 4: Création d'un Fichier Excel

1. Apprendre à utiliser la bibliothèque `xlsx`.
2. Créer et formater un fichier Excel avec les données récupérées.

### Étape 5: Envoi des Données par Email

1. Configurer `nodemailer` avec votre serveur SMTP.
2. Écrire une fonction pour envoyer le fichier Excel en pièce jointe.

### Étape 6: Automatisation

Pas la peine, sauf si tu veux que je te montre comment te servir de aws.

## Ressources

- [Documentation API YouTube Data](https://developers.google.com/youtube/v3)
- [Documentation `xlsx`](https://github.com/SheetJS/sheetjs)
- [Documentation `nodemailer`](https://nodemailer.com/about/)



## Licence

[MIT](
