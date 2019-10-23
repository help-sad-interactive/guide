---
title: Module Créer une carte
keywords: sample
summary: "Le module créer une carte permet de projeter vos propres données !"
sidebar: sadinteractive_sidebar
permalink: sadi_creer_une_carte.html
folder: sadinteractive
---

Si vous disposez de données associées à un code commune (code Insee) ou à un code Iris il est possible de créer votre propre carte ! En cliquant sur créer une carte, une interface avec plusierus options apparaitra : 
- Le titre de la carte
- Le choix des couleurs utilisées pour la carte
- La découpe utilisée : Commune (5 chiffres) ou Iris (9 chiffres)
- La méthode de création de la carte : les quantiles répartiront équitablement les effectifs dans chaque classe de la légende. Jenks est un algorithme qui identifie les effets de seuil au sein de votre effectif. Il n'y a pas de bonne ou mauvaise solution. Nous vous conseillons de générer les deux cartes pour choisir celle qui vous convient le mieux
- Les données : c'est ici qu'il faut copier vos données, depuis un Excel par exemple, avec en première colonne le code géographique et en seconde colonne la donnée que vous souhaitez représenter.

![Interface Créer une carte](images\sadi_creer_carte\interface_creer_carte.png)

Une fois tous les paramètres entrés, vous pouvez générer votre carte : 

![Interface Créer une carte](images\sadi_creer_carte\creer_carte.gif)

{% include links.html %}
