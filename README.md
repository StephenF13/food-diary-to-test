food-diary (OpenClassrooms)
==========

Test fonctionnel avec Symfony
 
Installation
============
 
First of all you need to run the `$ composer install`.
 
 This application requires a MySQL database. You need to configure the following parameters in the app/config/parameters.yml
 file :
 
     database_host
     database_port
     database_name
     database_user
     database_password
Then run the following commands in your favorite command line tool :

`$ bin/console doctrine:database:create`
`$ bin/console doctrine:schema:create`
