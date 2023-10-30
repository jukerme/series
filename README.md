# Projet Symfony Series

## Démarrer le projet

Installer les dépendances avec Composer :

```shell
composer install
```

Ouvrir le projet en utilisant Apache ou bien avec le serveur interne de PHP :

```shell
php -S localhost:8000 -t .\public
```

## Création du projet

Si besoin, configurer le proxy :

```shell
set http_proxy=10.35.0.248:8080
```

Se positionner dans le dossier C:\wamp64\www puis installer le projet Symfony :

```shell
composer create-project symfony/skeleton:"^5.4" my_project_directory
```

Ouvrir le projet dans PHPStorm et **activer le plugin Symfony**.

Ajouter le dossier `.idea` dans le .gitignore.

Initialiser le repo Git et synchroniser avec repo GitHub.

Optionnellement, installer webapp (Doctrine, Twig, Forms...) :

```shell
cd my_project_directory
composer require webapp
```
