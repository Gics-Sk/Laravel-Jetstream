## JETSTREAM DE LARAVEL
Laravel Jetstream est un kit de démarrage d'application magnifiquement conçu pour laravel et constitue le point de départ idéal pour votre prochaine application Laravel. Jetstream fournit l'implémentation de la connexion , de l'enregistrement , de la vérification des e-mails, de l'authentification à deux facteurs, de la gestion des sessions, de l'API via Laravel Sanctum et des fonctionnalités faculatives de gestion d'équipe de votre application.

Jetstream est conçu à l'aide de Tailwind css et offre votre choix d'echaffaudages Livewire ou Inertia.

## Installation de Jetstream
vous pouvez utiliser composer pour instaler Jetstream dans votre projet Laravel:

```` php
composer create-project laravel/laravel example-app

cd example-app

composer require laravel/jetstream

````
Après avoir installé le package Jetstream, vous pouvez exécuter la `jetstream:install` commande Artisan.Cette commande accepte le nom de la pile que vous préférez(`livewire` ou `Inertia`).De plus , vous pouvez utiliser le `--teams` commutateur pour activer le support d'équipe.

La `jetstream:install` commande installera également une suite de tests de << fonctionnalités >> qui fournissent une courverture de test pour les fonctionnalités fournies par Jetstream.

il est fortement recommandé de lire l'intégralité de la documentation de Livewire ou d'Inertia avant de commencer votre projet Jetstream.

Installer Jetstream avec livewire 

```` php
php artisan jetstream:install livewire

````
si vous souhaitez un support <<équipes>>, vous pouvez fournir la `--teams`directive à la commande d'installation:

```` php
php artisan jetstream:install livewire --teams

````

Ou, installez Jetstream avec Inertia
```` php
php artisan jetstream:install inertia
````
Si vous souhaitez une prise en charge des « équipes » avec la pile Inertia, fournissez la --teamsdirective à la commande d'installation :

```` php
php artisan jetstream:install inertia --teams

````
La pile Inertia peut également être installée avec le support SSR :

```` php
php artisan jetstream:install inertia --ssr
````
