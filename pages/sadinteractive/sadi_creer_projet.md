---
title: Créer un projet
keywords: sample
summary: "Le module projet vous permet de calculer une zone isochrone grâce à l'API Google Maps"
sidebar: sadinteractive_sidebar
permalink: sadi_creer_projet.html
folder: sadinteractive
---

## Initialiser le projet
Il existe deux méthodes pour initialiser votre projet (choisir son point de départ):

### Méthode 1 : en recherchant une adresse
Vous pouvez assigner le point de départ de votre projet en recherchant une adresse dans le champ de recherche en haut à droite de l'interface : 

![Projet par recherche d'adresse](images\sadi_creer_projet\projet_recherche_adresse.gif)

### Méthode 2 : en zoomant et en cliquant
Si vous ne connaissez pas l'adresse de votre projet, il est également possible de simplement zoomer jusqu'à sa localisation et en faisant un clic droit d'assigner le point de départ

![Projet par zoom et clic](images\sadi_creer_projet\projet_zoom_clic.gif)

## Générer la zone
Une fois le projet initialisé, il vous suffit de cliquer sur **Calculer une zone de chalandise**. 
Un menu contextuel va s'ouvrir avec plusieurs éléments :
* Le nom du projet qui est généré automatiquement avec le nom de la ville et la date
* Un rappel de l'adresse du site qui n'est pas modifiable
* Le choix des temps de trajet. Des choix de zones sont disponibles par défaut mais il est possible d'adapter le nombre et la durée du temps de trajet en fonction de vos besoins
* Le choix du moyen de transport
{% include warning.html content="Actuellement, le mode *transport en commun* ne renvoie des résultats que pour Paris" %}

![Formulaire projet](images\sadi_creer_projet\formulaire_projet.png)

Une fois que vos paramètres validés, il vous suffit de cliquer sur **Calculer** et la zone isochrone sera générée :

![Projet généré](images\sadi_creer_projet\resultat_generation_projet.png)

Il est temps désormais de [modifier votre projet](\guide\sadi_modifier_projet.html)

{% include links.html %}
