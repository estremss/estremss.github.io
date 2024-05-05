---
title: Processeur RISC-V
publishDate: 2020-03-04 00:00:00
img: /assets/processeur.png
img_alt: Illustration de mon processeur Digital
description: |
  Développement d'un processeur sur Digital dans le cadre de ma L2 Informatique
tags:
  - Architecture des Ordinateurs
  - Risc-V
  - CPU
---

## Processeur RISC-V 32 bits

Au cours du premier semestre de ma L2 Informatique, nous avons commencé à construire ce processeur sur Digital. C'est dans le cours Architecture des Ordinateurs que notre professeur nous a introduit les portes logiques et circuits logiques.

> From the scratch

C'est en partant de zéro que nous avons commencé à construire notre processeur. D'abord sur papier en créant des automates à états finis, des tables de vérité et des équations. Ensuite nous avons débuté sur Digital avec :
- un additionneur 1-bit (puis 4-bits)
- un circuit AND
- un banc de registres 8-bits (puis 32-bits)
- un décaleur 4-bits
- une structure conditionnelle B-Type (spécifique à RISC-V)

Jusqu'à arriver à une unité arithmétique et logique (UAL), puis en ayant relié ces composants petit à petit et en ajoutant à la fin la structure conditionnelle B-TYPE, nous sommes arrivés au résultat final.

> RISC-V

Nous avons évolué avec la spécification RISC-V 32-bits qui est open source. C'est une architecture  basée sur un ensemble d'instructions réduit (RISC) et conçue pour être simple, modulaire et adaptable.

> Digital

Notre professeur a choisi de nous faire évoluer sur Digital, un logiciel de simulation de circuit qui reprend la plupart des fonctionnalités de Logisim, mais qui résout des problèmes architecturaux qui sont présents sur Logisim.