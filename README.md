# Projet Architecture Logicielle

Vous allez faire un projet d'application Ruby On Rails en utilisant les différents éléments d'architecture vus en cours.

# Sujet

## Application

L'application devra être une application web qui remplit un besoin spécifique de votre choix. Cela devra être décrit en quelques lignes dans un fichier README et accompagné d'un diagramme décrivant les différentes tables et relations entre chacune.

## La base

Votre application devra implémenter par défaut un CRUD (Create, Read, Update, Delete).
Elle contiendra au minimum trois modèles interagissant ensemble (dont User) dont au moins un imbriqué.
Lors du développement de l'application, vous devrez créer un minimum de fichiers et de lignes de code pour implémenter le CRUD.

## Authentification/Autorisation
Vous devez implémenter un système d'authentification et d'autorisation pour votre application pour les actions du CRUD les plus sensibles.

## Services
Afin de respecter le Principe de Responsabilité Unique, vous devez créer des services pour effectuer les fonctionnalités spécifiques.

## Jobs
Vous devez implémenter au moins un job sur votre application qui permettra d'effectuer une tâche en arrière plan.

## Recherche (filtre)
Vous devrez inclure dans votre application une recherche générique sous la forme suivante: http://xxxxx/restaurants?address=Paris

## Gems
Vous pouvez utiliser des gems existantes en décrivant en commentaire dans le Gemfile la fonctionnalité rendue par la gem.

## Seed
Vous devez implémenter une seed afin qu'un jeu de données soit facile à générer pour tester votre application.

## Base de données
Vous devez utiliser Postgresql combiné à Active Record

## Hébergement
Votre projet devra être hébergé sur Heroku.

## Gem (bonus)
Vous pouvez développer une gem contenant du code utile réutilisable dont vous vous servez dans votre projet en l'appelant directement dans le Gemfile

## Tests (bonus)
Un projet de test unitaire et test systems pourra être réalisé pour votre application.

## Design (bonus)
Designez votre application en utilisant css et javascript pour la rendre plus attractive.

# Groupes et fonctionnement

Le projet est à développer en groupe de 2 personnes.
Tous les groupes seront définis en cours, sous la supervision de l'enseignant. Les groupes s'enregistrent avec un nom de groupe ainsi que les noms de leurs membres.

Toute inscription est définitive.  Les étudiants ne sont pas autorisés, par la suite, à changer de groupe.

Au sein d'un groupe, les étudiants se répartiront les tâches pour le projet, de façon équitable.  Il est explicitement exigé que chaque membre consacre au moins 50% de son travail à du développement technique. Du code de test est acceptable, tant qu'il ne constitue pas l'intégralité de la réalisation technique du membre du groupe.

Les étudiants sont encouragés (mais pas obligés) à mettre en place un système de contrôle des sources de type Git ou équivalent, afin d'affecter et partager efficacement les fichiers de codes et autres composants numériques du projet (fichiers sources, descripteurs de déploiement, documents de recherche, cas d'utilisation, suites de tests, etc.).

# Soutenance et rendu

La soutenance aura lieu le vendredi 29 janvier 2021.
La soutenance se déroulera sur Teams, chaque membre devra mettre sa caméra et son micro afin de participer.
Les horaires de passage seront définis pour chaque groupe.
Toute absence à la soutenance entrainera un 0 (ZERO) pour le membre du groupe.

Les rendus doivent figurer sur un seul compte par groupe.
Le rendu s'effectuera via un repos GIT. L'adresse du rendu est envoyé par mail.
Le mail de rendu est thibaud.maurel@ynov.com
Les fichiers rendus doivent contenir
  - L'arborescence du projet, immédiatement exploitable après création des bases de données, exécution des migrations et de la seed.
  - En cas de développement d'une GEM, l'arborescence de la gem.
  - Un fichier README expliquant en quelques lignes ce que fait l'application.
  - Un diagramme présentant les différentes tables ainsi que les liens entre celles ci.
  - Un AUTHORS.TXT listant les membres du groupe (prénom, nom), à raison d'un par ligne.  Il liste ensuite les responsabilités effectives de chacun dans le groupe.
Le sujet du mail doit contenir votre section ainsi que le nom du projet.
Les fichiers rendus peuvent aussi comprendre:
  - Des documents de recherche créés pour le projet et fournissant plus de détails pour l'enseignant.
Pour tout autre type de fichier, veuillez demander à l'enseignant si son inclusion est appropriée.
La soutenance dure 20 minutes durant lesquelles les membres présentent leur travail. Un échange de questions peut se faire entre le professeur et les membres du groupe.

# Groupes
- Pierre VILLIERS & Jean RAGUENEAU
- Adrien LEIB & Hugo-Jean EGU
- Gauthier LECOUFFE & Antoine HALLER
- Maxence DUBUCHE & Guillaume FITAMANT
- Zahir MENDACI & Ylane TURAM-ULIEN
- Ihcen BORJI & Younes AZIZE
- Zakaria MOUBARAK & Ndeye Awa DIOP
- Anthony KHELIL & Sarujan RAJARATNAM
- Saleh DASSOUKHI & Clément PALAU
