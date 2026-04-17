> Ce document est un exemple de `README.md` à utiliser pour les exercices et projets. 
> 
> A personnaliser selon l'exercice/projet


# Nom du Projet

- Version : 1.0.0
- Auteur(s): 
    - [Prénom NOM]
    - [Prénom NOM]

## Description des fonctionnalités

[Nom du Projet] est une application [Décrire l'application en quelques mots].

### Fonctionnalités principales

- Nom de la Fonctionnalité 1 : Description de la fonctionnalité 1.

- Nom de la Fonctionnalité 2 : Description de la fonctionnalité 2.

- Nom de la Fonctionnalité 3 : Description de la fonctionnalité 3.

- etc...

<div style="page-break-after:always;"></div>

## Stack Technique

> Liste des technos et langages utilisés pour **développer** l'application.

* **Frontend :** HTML 5, CSS 3, Javascript
    * **Frameworks :** VueJs 3.25
* **Backend :** PHP 8.4
    * **Frameworks :** Symfony 8.4
* **Base de données :** MariaDB 11.8.5

## Environnement d'exécution

> Liste des éléments nécessaires pour **exécuter** l'application.

Ce projet nécessite un environnement compatible avec les spécifications suivantes :

* **Serveur :** Apache 2.4
    - Module Rewrite activé
* **PHP :** 8.4
    - Module PDO_mysql activé
* **Base de données :** MariaDB 11.8.5

<div style="page-break-after:always;"></div>

## Installation & Démarrage

### Option 1 : Via Docker (Recommandé)

Ce projet est entièrement conteneurisé. Assurez-vous d'avoir Docker installé sur votre machine.

1. Clonez ce dépôt : `git clone [URL_DU_DEPOT]`
2. Accédez au dossier : `cd [NOM_DU_DOSSIER]`
3. Lancez l'environnement :
```bash
docker compose up -d
```

4. L'application sera accessible à l'adresse suivante : [http://localhost:PORT](http://localhost:PORT)

### Option 2 : Installation manuelle (Alternative)

*Si vous n'utilisez pas Docker, assurez-vous d'avoir un serveur local (type LAMP, WAMP ou MAMP) configuré avec les versions PHP et MariaDB indiquées ci-dessus.*

1. Importez le fichier SQL situé dans `./chemin/vers/db_init.sql` dans votre gestionnaire de base de données.
2. Configurez le fichier `./src/conf/.env` avec les identifiants de connexion à la base de données.
3. Accéder à l'application via un navigateur. L'adresse dépendra de votre configuration locale.
