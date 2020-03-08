# Installation de Laravel

Pour installer Laravel, vous devez posséder Composer sur votre machine. 

[Installer Composer](https://getcomposer.org/) 

Par la suite, tapez la commande suivant dans votre terminal (dans le dossier de votre choix).

`composer create-project --prefer-dist laravel/laravel monprojet`

### Utilisation du server intégré

Pour utiliser le serveur intégré utilisez la commande 

`php artisan serve`

# Configuration 

1. **Fichiers de configuration**

Configurez votre fichier .env en fonction de vos besoins (serveur SMTP, base de données etc.) 

**L'ensemble des configurations sont utilisées dans le dossier `config/`**

# Structure des dossiers

- Le dossier `app`

Le dossier `app` contient la majorité du code de notre application web.

- Le dossier `bootstrap`

Ce dossier contient le fichier `app.php` qui sert à amorcer le framework. 
Le dossier `bootstrap/cache` quand à lui, sert à enregistrer les fichiers générés par le framework et améliorer les performances. 

- Le dossier `config`

Il contient toute la configuration et les options du framework

- Le dossier `database`

Le dossier databasecontient tout ce qui a un lien avec la base de données **migrations** , **model** , **factories** et **seeds** 

- Le dossier `public`

Le dossier public contient le fichier `index.php` qui est le point d'entrée de l'application. Ce dossier contient également les fichiers assets compilés (`css, js`). 

- Le dossier `resources`

Le dossier resources contient les vues ainsi que les ressources non compilées `LESS, SASS, JavaScript`. 

- Le dossier `routes`

Le dossier routes contient la définition des routes de l'application. 

___

Lire la suite <routing.md>
