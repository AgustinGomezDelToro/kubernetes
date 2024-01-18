# Titre du Projet : Implémentation de l'Infrastructure et de la Sécurité dans un Cluster GKE

## Description
Ce projet implique la mise en place de plusieurs composants dans un cluster Google Kubernetes Engine (GKE) en utilisant Terraform. Voici un résumé des tâches accomplies et celles en attente :

### Tâches Accomplies :
1. Un déploiement d'une base de données PostgreSQL dans le cluster GKE.
2. Un déploiement d'un nœud Ethereum dans le cluster GKE.
3. Configuration d'un cluster GKE pour exécuter un serveur Nginx et un module Grafana pour surveiller le cluster.
4. Un déploiement d'une CloudFunction activée par un planificateur pour s'exécuter quotidiennement à 7 heures du matin (en attente de l'exécution d'une commande CURL).

### Tâches en Attente :
1. Implémentation de la CloudFunction pour exécuter une commande CURL sur la page d'index de Nginx.
2. Sécurisation de la CloudFunction en utilisant un compte de service dédié.
3. Création d'un réseau nommé "MyNetwork" avec un MTU de 1500 et le déploiement d'une machine virtuelle (VM) à l'intérieur.
4. Installation de Docker sur la VM et exécution d'un conteneur du serveur Apache (httpd), exposé sur le port 4000 de la machine hôte.
5. Création d'une règle de pare-feu pour autoriser l'accès au serveur Apache depuis Internet.

Les services Grafana et Nginx ont été déployés à l'aide de Terraform, et des fichiers YAML ont été préparés pour exécuter les tâches restantes.


## Auteur
- Gomez Del Toro Agustin

