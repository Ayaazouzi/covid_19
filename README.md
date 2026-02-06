# Covid_19 (Symfony)

Application web Symfony pour gérer et visualiser des données COVID-19.

## Description

Ce projet est développé avec Symfony et permet la gestion et la visualisation des données liées au COVID-19.  
Il inclut un backend structuré avec Controllers, Entities, et une interface avec Twig pour afficher les données.

## Fonctionnalités

- CRUD des données COVID-19 (ajouter, modifier, supprimer)  
- Visualisation des statistiques  
- API backend pour récupérer les données  
- Tests unitaires avec PHPUnit

## Technologies

- PHP / Symfony  
- MySQL  
- Twig pour le frontend  
- PHPUnit pour les tests

## Structure du projet

covid_19/
├─ config/ # Configuration routes, services
├─ src/ # Controllers, Entities, Services
├─ templates/ # Fichiers Twig
├─ public/ # Point d’entrée index.php
├─ var/ # Cache, logs
├─ vendor/ # Packages Composer
└─ .env # Variables d’environnement


## Installation

### Prérequis
- PHP >= 8
- Composer
- MySQL
- Symfony CLI (optionnel)

### Étapes
```bash
git clone https://github.com/Ayaazouzi/covid_19.git
cd covid_19
composer install
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
symfony server:start
Ouvrir dans le navigateur : http://localhost:8000

Auteur
Aya Azouzi
