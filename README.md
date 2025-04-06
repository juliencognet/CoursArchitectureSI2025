# Cours Architecture de Systèmes d’Information
**Travaux Dirigés 2025 - Julien COGNET**


> 💬 Votre travail va remplir une grande partie de votre vie, et la seule façon d'être vraiment satisfait est de faire ce que vous croyez être un grand travail. Et la seule façon de faire un grand travail est d'aimer ce que vous faites.
>
> **Steve Jobs**

🔻

## A1 - Quizz "Faisons connaissance"

https://forms.office.com/r/WPzrYSc7VU

🔻

## A2 - Découverte d’un référentiel d’architecture d’entreprise
### Objectifs du TD
*	Comprendre le concept et l’intérêt des vues
*	Mettre du concret sur tous les concepts abordés en début de cours
*	Découvrir un référentiel d’EA

### Description de l’activité
* Cette activité se fait en groupe et se déroule en 2 parties. 
* Ouvrir l'exemple issu de l'outil de capitalisation d'architecture d'entreprise EssentialViewer open source disponible à l'adresse suivante https://essentialviewer.com
* Nous allons nous intéresser au domaine de la collecte de données d'énergie en europe (Collect Meter Data - EU). Pour explorer ce processus métier, vous pouvez vous diriger vers la vue "Business Process Summary".
   * A quelle capacité métier est reliée ce processus métier ?
   * Quelles sont les 3 applications qui implémentent ce procesuss métier ?
* Grâce à la vue "Application Strategic Radar", déterminez le statut de chacune des applications impliquées dans ce processus métier. L'une d'entre elle est actuellement dans la phase "Prototype". Nous allons nous intéresser à cette application.
* Parcourez la vue "Application Summary" pour en savoir plus sur cette application. Qui en est le responsable métier ? Qui en est le responsable IT. 
* Grâce à la vue "Application Footprint Comparison", comparez l'empreinte fonctionnelle de cette application en prototype avec les autres applications implémentant le processus métier. Que pouvez-vous constater ?
* Grâce à la vue "Business Process RTO/RPO Mapping", retrouvez quel est le Recovery Time Objective et le Recovery Point Objective associé au processus métier "Collect Meter Data - EU". Quel est le statut des 3 applications qui implémentent le processus métier ? Que pouvez-vous en déduire sur la nécessité de finaliser le prototype ?
* Grâce à la vue "Application Rationalisation Analysis", déterminez le gain en coût annuel après rationalisation des 3 applications candidates pour remplacement par l'application analysée. Vous devrez aussi utiliser la vue "Application Cost Summary" pour obtenir une décomposition des coûts annuels totaux de l'application en prototype.
* Grâce à la vue "Application Dependency", déterminez de qui / quoi dépend l'application actuellement en prototype. Combien de projets d'intégration sont-ils nécessaire pour réussir le projet ?
* Grâce à la vue "Application Technology Strategy Alignment", déterminez l'architecture technique logique de l'application étudiée (en prototype). Quelles problèmes potentiels identifiez-vous ?
  
🔻

## Choix des sujets d'étude 

* E1 - **Système de gestion de flotte de véhicules** : Concevoir une architecture pour suivre et gérer une flotte de véhicules en temps réel, incluant la géolocalisation, la maintenance prédictive et l'optimisation des itinéraires.
* E2 - **Plateforme de e-commerce** : Développer une architecture pour une plateforme de vente en ligne, incluant la gestion des produits, des commandes, des paiements et des recommandations personnalisées.
* E3 - **Système de gestion hospitalière** : Créer une architecture pour un système de gestion des dossiers médicaux, des rendez-vous, et des prescriptions, avec des fonctionnalités de télémédecine.
* E4 - **Application de réseau social** : Concevoir une architecture pour une application de réseau social, incluant la gestion des profils, des publications, des commentaires et des notifications en temps réel.
* E5 - **Système de gestion de l'énergie** : Élaborer une architecture pour un système de gestion de l'énergie dans les bâtiments, incluant la collecte de données des capteurs, l'analyse et l'optimisation de la consommation énergétique.
* E6 - **Plateforme de streaming vidéo** : Développer une architecture pour une plateforme de streaming vidéo, incluant la gestion des contenus, la diffusion en direct, et les recommandations basées sur les préférences des utilisateurs.
* E7 - **Système de gestion des ressources humaines** : Créer une architecture pour un système de gestion des ressources humaines, incluant la gestion des employés, des salaires, des performances et des formations.
* E8 - **Système de gestion de la chaîne d'approvisionnement** : Concevoir une architecture pour un système de gestion de la chaîne d'approvisionnement, incluant la gestion des stocks, des commandes, et des livraisons.
* E9 - **Application de santé et bien-être** : Élaborer une architecture pour une application de suivi de la santé et du bien-être, incluant la collecte de données des utilisateurs, l'analyse et les recommandations personnalisées.
* E10 - **Système de gestion de l'éducation** : Développer une architecture pour un système de gestion de l'éducation, incluant la gestion des cours, des étudiants, des évaluations et des ressources pédagogiques.

🔻

## A3 - Business Motivation Model
### Objectifs du TD
*	Découvrir le langage de modélisation Archimate
*	Comprendre les rudiments de l’architecture des motivations
*	S’entraîner au questionnement à base de questions ouvertes et à l’écoute active
*	Prendre de la hauteur de vue par rapport à un problème
### Description de l’activité
* Donnez un nom à l'entreprise qui veut implémenter le sujet que vous avez choisi
*	Ouvrir https://app.diagrams.net/
*	Créez un nouveau diagramme à partir du modèle « Business Motivation Model Sample.drawio » grâce à l’entrée de menu File > Open from … > Device
* Définissez quelle est la vision, quelles sont les missions de l'entreprise qui implémente le projet que vous avez choisi et les objectifs qu'elle pourrait se fixer

🔻

## A4 – Analyse et choix des principes d’architecture les plus appropriés à notre cas fil rouge
### Description de l’activité
*	Parcourir le catalogue de principes d’architecture proposé en annexe du support de cours
*	Choisir 3 principes d’architecture qui s’appliquent particulièrement à votre projet
*	Expliquez pourquoi vous avez choisi ce principe d’architecture

🔻

## A5 – Architecture de données - Concevoir le modèle logique de données relationnelles
### Objectifs du TD
*	Apprendre à réaliser une modélisation de base de données
### Description de l’activité
* Déterminer quelles sont les 5 à 10 entités du domaine que vous étudiez. 
* Modéliser les entités de votre domaine avec https://www.drawdb.app/editor 
* Modélisez aussi les liens entre ces entités en suivant les règles apprises en cours




