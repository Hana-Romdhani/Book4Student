# Book4Student

# Project Microservice Architecture

Ce projet démontre une architecture de microservices implémentée en utilisant Spring MVC, Node.js et AngularJS. L'application utilise différentes bases de données, y compris SQL, H2 et MongoDB, et est déployée à l'aide de Docker.

## Table des Matières
1. [Introduction](#introduction)
2. [Architecture](#architecture)
3. [Technologies](#technologies)
4. [Installation et Configuration](#installation-et-configuration)
8. [Déploiement avec Docker](#déploiement-avec-docker)
9. [Exécution de l'Application](#exécution-de-lapplication)
10. [Contributeurs](#contribuer)
11. [Licence](#licence)



## Introduction

Ce projet est un exemple d'architecture de microservices intégrant différentes technologies et bases de données. L'objectif est de montrer comment les microservices peuvent être utilisés pour construire une application évolutive et maintenable. Nous allons réaliser ce projet sur une période de 7 semaines, en mettant en œuvre les meilleures pratiques de développement logiciel et en explorant les avantages de l'approche des microservices.



## Architecture
L'architecture du projet comprend plusieurs microservices communiquant entre eux. Chaque microservice est responsable d'une fonctionnalité spécifique et interagit avec sa propre base de données. Les services sont :

- **Service Spring MVC** : Gère la logique métier avec Spring Boot et interagit avec les bases de données SQL et H2.
- **Service Node.js** : Gère d'autres parties de la logique de l'application avec Node.js et interagit avec MongoDB.
- **Frontend AngularJS** : Fournit l'interface utilisateur et interagit avec les services backend.

## Technologies
- **Spring MVC / Spring Boot** : Pour construire des microservices en Java.
- **Node.js** : Pour construire des microservices en JavaScript.
- **AngularJS** : Pour construire le frontend.
- **SQL** : Base de données relationnelle traditionnelle.
- **H2** : Base de données en mémoire pour le développement et les tests.
- **MongoDB** : Base de données NoSQL pour les données non structurées.
- **Docker** : Pour containeriser et déployer l'application.
- **Docker Hub** : Pour stocker et partager les images Docker.

## Installation et Configuration

### Prérequis
- Java 11+
- Node.js 14+
- Angular CLI
- Docker
## Déploiement avec Docker
docker-compose build
docker-compose push
## Exécution de l'Application
docker-compose up
## Contributeurs 
- [amenibensaada](https://github.com/amenibensaada/) (@amenibensaada) 
- [GhassenChamakh](https://github.com/GhassenChamakh) (GhassenChamakh) 
- [OumaimaAy](https://github.com/OumaimaAy) (@OumaimaAy) 
- [azizbg1](https://github.com/azizbg1) (@azizbg1)
## Licence
Ce projet est sous licence MIT. Voir le fichier [LICENSE](./LICENSE) pour plus de détails.

### Cloner le Répertoire
```sh
git clone https://github.com/Hana-Romdhani/Book4Student.git 
cd microservice-project
