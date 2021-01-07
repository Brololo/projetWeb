Commandes faites :

composer create-project symfony/website-skeleton

composer require symfony/orm-pack

composer require --dev symfony/maker-bundle

cd .\website-skeleton\

symfony console doctrine:database:create

php bin/console make:user

symfony console make:migration

symfony console doctrine:migrations:migrate