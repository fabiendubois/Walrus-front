# Walrus Front

Spécifications de l'application : https://github.com/poutsjr/mentimaster-doc/blob/master/src/main/asciidoc/index.adoc


## Docker & Base de données
Mise en place du Docker MariaDB
- Se déplacer dans le dossier docker.
- Executer la commande `docker-compose up -d`.
- Vérifier le bon fonctionnement du docker avec : `docker ps -a`.
- Connexion au container : `docker exec -it <ID CONTAINER> bash`.
- *Dans le container :* `mysql -p` pour se connecter à la base.

Afin de faciliter l'utilisation de la base de données vous pouvez utiliser SQL Electron : https://sqlectron.github.io