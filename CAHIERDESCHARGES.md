# Cahier des charges

## I) Introduction
Le but de plus-plus est de proposer un site open source pratique et modulable, utilisable sans souci. Ce projet a pour vocation de proposer un espace d'administration générale, un espace d'administration par établissement et une intéraction professeur-élève propre.

## II) Présentation des fonctionnalités clés du site :
- Pages de présentation et d'explications + page de login
- Panel admin pour chaque établissement avec un contrôle total 
- Panel "prof" pour les responsables de chaque classe
- Panel "examinateur" pour chaque examinateur
- Panel élèves

## III) Structure du frontend

### Panel présentation & misc
- Page de présentation du projet
- Pages d'aide et d'explications
- Page de login pour les utilisateurs

### Panel d'administration général
- Possibilité de créer/supprimer des établissement et de nommer des administrateurs dans ceux-ci
- Possiblité de voir des stats globales (a définir précisément)
  
### Panel d'administration par établissement
- Possibilité d'ajouter/supprimer des élèves
- Possibilité de gérer les profs
- Possibilité d'assigner des élèves/profs à des classes
- Possibilité de voir des stats globales par rapport à l'établissement
=> TODO

### Panel "prof"
- Si prof "principal", possibilité de gérer la programmation des examens
- Possibilité de rajouter des notes de devoirs
=> TODO

### Panel "examinateur"
- Possibilité d'entrer les notes des étudiants
- Possibilité de visualiser les prochains examens (date/heure/salle...)
=> TODO : compléter selon les besoins

### Panel étudiant 
- Panel pour changer/visualiser diverses informations reliées à un compte utilisateur
- Pages pour visualiser des notes 
- Pages pour visualiser les examens oraux à venir

## IV) Structure du Backend 

### Présentation du backend
API REST utilisant spring boot et connectée à la database, permettant de gérer toutes les interactions front-database et les login.

=> TODO

## V) Structure (tables) de la base de données
=> TODO

