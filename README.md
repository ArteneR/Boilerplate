# Boilerplate
Boilerplate webapp with Laravel + Angular

-----------------------------------------


Resources:
    - https://scotch.io/tutorials/create-a-laravel-and-angular-single-page-comment-application


-----------------------------------------

Steps for setting up the project:


Install Composer:


cd into folder you want to initialize laravel-app

php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"

php -r "if (hash_file('sha384', 'composer-setup.php') === 'e0012edf3e80b6978849f5eff0d4b4e4c79ff1609dd1e613307e16318854d24ae64f26d17af3ef0bf7cfb710ca74755a') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"

php composer-setup.php

php -r "unlink('composer-setup.php');"


---

Download Laravel installer (via Composer):

composer global require laravel/installer

(OR if you installed composer only in that folder (composer.phar) -> php composer.phar global require laravel/installer)

[ 
    If problem with ext-zip extenstion:

    sudo apt install php-zip 
]



