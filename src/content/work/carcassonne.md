---
title: Carcassonne en C
publishDate: 2024-10-10 00:00:00
img: /assets/carcassonne.jpg
img_alt: Logo Carcassone
description: |
  Projet de Programmation du jeu de société Carcassonne en Langage C. En collaboration avec Assalas ARAB.
tags:
  - C Language
  - Game Coding
  - Pair Programming
---

[Lien GitHub du Projet](https://github.com/estremss/Carcassonne)

## Le jeu Carcassonne

Dans ce jeu jouable de 2 à 5 joueurs, vous avez pour tâche de développer la région avoisinant Carcassonne.
Chaque participant tire une tuile à son tour parmi les 72 disponibles, puis la place sur la grille de jeu. Chaque tuile présente 4 côtés et un centre, représentant divers éléments du paysage tels que des routes, des villes, des abbayes et des champs. Les joueurs ont l'opportunité de positionner leurs pions sur les tuiles pour accumuler des points. Si vous souhaitez l'emporter, vous devez faire le meilleur placement possible de vos pions.

La version du jeu que nous avons programmé comprend les règles de base : possibilité de poser les pions sur les villes, abbayes et routes.                  


## Notre approche du projet  

> Un client pingouin       

Le projet Carcassonne a été développé pour un client Linux, il fonctionne donc uniquement sous ce système.        


> Une représentation fidèle pour un rendu fidèle

Dans notre approche pour coder le jeu, nous avons privilégié une représentation fidèle du jeu en créant des structures ressemblantes à celle du jeu. Telles que les structures Tuile, Joueur, etc...

Cela nous a permis de pouvoir mettre facilement notre code en lien avec le jeu de société.


> Un affichage dans le terminal

Nous avons choisi dans la simplicité et l'efficacité en optant pour un affichage terminal en utilisant l'UTF-8 et ses symboles pour représenter les pions. Et les couleurs d'arrière plan pour représenter les différentes parties d'une tuile avec un certain code couleur.

## Utiliser notre projet

> GitHub

Vous pouvez télécharger [notre projet](https://github.com/estremss/Carcassonne) via GitHub pour le découvrir et même faire une partie avec vos amis !