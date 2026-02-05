# Utiliser l'image officielle MariaDB
FROM mariadb:latest

# Définir des variables d'environnement par défaut
ENV MARIADB_ROOT_PASSWORD=123456
ENV MARIADB_DATABASE=tasksdb

#Copier le fichier init 
COPY init.sql /docker-entrypoint-initdb.d/

# Exposer le port par défaut de MariaDB
EXPOSE 3306