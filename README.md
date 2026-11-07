# RestoSAF

Application web de gestion de restaurant, réalisée comme projet de fin d'études (2023) : site vitrine avec réservation de table et espace interne pour le personnel.

## Fonctionnalités

### Site public
- Page d'accueil
- Menu du restaurant, organisé par catégories
- Réservation de table en ligne

### Espace interne (/office)
- Connexion sécurisée du personnel
- Tableau de bord
- Gestion des employés : création, modification, suppression, activation et désactivation
- Gestion des rôles
- Gestion des catégories du menu

## Technologies

- Backend : PHP 8, Laravel 9
- Frontend : Blade, JavaScript (Vite, axios), HTML5, CSS3
- Base de données : migrations Laravel
- Outils : Git, GitHub, Composer, npm

## Installation

```
git clone https://github.com/MoussaKallamouSENE/restoSAF.git
cd restoSAF
composer install
cp .env.example .env
php artisan key:generate
```

Configurez ensuite la base de données dans le fichier `.env`, puis :

```
php artisan migrate
npm install
npm run dev
php artisan serve
```

## Auteur

Moussa SENE, développeur et administrateur d'applications.
GitHub : https://github.com/MoussaKallamouSENE
