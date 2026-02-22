# Laboratoire 5 - Microservices, SOA, SBA, API Gateway, Rate Limit & Timeout  
**Table des matières**
1. Introduction, description des fichiers et définition.
2. Réponse aux question.
3. Ajout pour la cohérence et la grille d'evaluation

## 1. Introduction, description des fichiers et définitions.

### Context et introduction ###
**Veuillez noter que que mon compte GitHub scolaire, celui avec inscrit à l'adresse benjamin.tardif.1@ens.etsmtl.ca n'est pas disponible pour l'instant. Mon compter a été hacké cet été et GitHub m'a bloqué l'accès. Les démarches ont été entreprises pour retrouver les droits d'accès. Conséquemment, le repertoire de GitHUb Classroom a été recopié de manière locale afin de pouvoir produire les demandes de laboratoire.**

Ce laboratoire est le cinquième d'une suite de laboratoires donnés dans le cadre du cour LOG430 - architecture logiciel. Il a pour objectif d'apprendre à l'étudiant le fonctionnement des microservices,

### Objectifs du laboratoire ###
Tel que décrit dans l'énoncé du laboratoire. 
* Apprendre à communiquer avec un microservice déjà existant
* Apprendre à configurer et utiliser KrakenD, un API Gateway
* Découvrir les configurations de timeout (limitation du temps de réponse) et rate limiting (limitation du nombre de requêtes) dans KrakenD

### Definitions et principes ###
* Microservice: logiciel indépendant ayant un but/intention unique.
* SOA: (Service-oriented Architecture) Ancètre du microservice, combinent des services réutilisables qui communiquent entre eux.
* SBA: (Service-Based Architecture) Architecture qui combine des principes d'architecture monolithique et micro-services. 
* API Gateway: Couche de transfert de données en utilisant l'API Rest. L'APIGateway est un microservice en tant que tel.

