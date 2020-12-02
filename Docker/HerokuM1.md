# RAPPEL DOCKER DU MD DOCKER
 
 #### Conteneur docker
 
 > "Un conteneur Docker est une instance exécutable d’une image. En utilisant l’API ou la CLI de Docker, nous pouvons créer, démarrer, arrêter, déplacer ou supprimer un conteneur. De manière avantageuse, nous pouvons connecter un conteneur à un ou plusieurs réseaux, y attacher de la mémoire ou créer une nouvelle image sur la base de son état actuel. De plus, il consiste en une image Docker, un environnement d’exécution et un ensemble d’instructions standard."

> "Si on applique le concept de l’orienté objet. Si une image est une classe, un conteneur est une instance d’une classe, c’est-à-dire un objet d’exécution. Nous pouvons également dire que les conteneurs sont en quelque sorte la raison pour laquelle vous utilisez Docker car ils constituent des encapsulations légères et portables d’un environnement permettant d’exécuter des applications."

C'est avec Docker que leur utilisation est simplifiée.

#### Conteneurisation

* Conteneurisation = utilisation de conteneurs pour déployer des applications 

La conteneurisation est très populaire car : flexible, léger, portable, etc.

#### Conteneurs et machines virtuelles

Un conteneur tourne de manière native sur Linux et partage le même noyau que celui de la machine hôte, avec les autres conteneurs. Il tourne discrètement, car léger, et ne nécessitant que très peu de ressources (en terme de RAM).

A l'inverse, les machines virtuelles sont plus gourmandes en RAM __ET__ en espace sur le disque dur. 

// Heroku avec Docker : https://devcenter.heroku.com/categories/deploying-with-docker
// Pour commencer : https://devcenter.heroku.com/articles/container-registry-and-runtime

# Heroku

* Heroku Container Registry (= Registre des conteneurs Heroku) permet de déployer des images Docker avec Heroku. Il est néanmoins possible de créer des images Docker avec Heroku (heroku.yml)

#### Bien commencer

 * Pour commencer, il faut avoir préalablement installé Docker, et être connecté à Heroku (heroku login)
 
 Se connecter au Container Registry avec la commande suivante :
> heroku container:login

