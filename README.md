Cours de NoSQL sur Cassandra
============================

Ce dépôt contient du contenu déstiné à une utilisation pédagogique auprès des étudiants de seconde année du département informatique de l'IUT d'Amiens suivant le parcours orienté en bases de données.

Pré-requis
----------

Pour utiliser le contenu de ce dépôt, vous devez avoir un ordinateur équipé de :

- Docker 17.09.0+
- Docker Compose

Lancement de Docker
-------------------

Pour ce nouveau projet, nous allons de nouveau utiliser Docker avec l'utilitaire docker-compose. Notre infrastructure comporte deux conteneurs :
- Un conteneur cassandra en mode base de données,
- Un conteneur cassandra qui nous servira à avoir la ligne de commande.

Afin de démarrer notre infrastructure, nous allons éxécuter la commande suivante :

```
docker-compose up -d
```

Une fois l'infrastructure démarrée, vous pouvez vous pouvez ouvrir la ligne de commande avec la commande suivante :

```
docker-compose run cqlsh
```

En fin de séance, n'oubliez pas d'éteindre l'infrastructure avec la commande appropriée :

```
docker-compose down
```
