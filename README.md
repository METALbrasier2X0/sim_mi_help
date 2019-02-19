# HELP

## Git veut que je commit .env (du projet symfony) !

* Dupliquer le ficher .env en .env.local
* Remplir les infos de la base de donnée
* "Discard" les changements de .env

## Docker ne veut pas se connecter après docker-compose !

https://docs.docker.com/install/linux/linux-postinstall/

## On a fait des changements dans la base de données et les autres machines plantent !

`docker-compose exec php php bin/console doctrine:schema:update --force`