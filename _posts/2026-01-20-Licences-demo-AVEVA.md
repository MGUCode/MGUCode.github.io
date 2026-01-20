---
layout: post
title: "Changement de politique sur les licences de démo AVEVA"
date: 2026-01-20
categories: [Informations]
tags: [AVEVA, Licences, Intouch HMI, System Plateform]
---

***Si comme moi vous êtes utilisateur de la licence de démo des produits AVEVA, prenez note des changements (déjà en vigueur) lié à l’utilisation de cette dernière !***
 
## Changement de politique

Depuis ce 1er janvier, AVEVA a changé sa politique de mise à disposition de la licence de démo « .loc » (pour les versions d’Intouch / System Plateform à partir de 2020). Cette décision affecte particulièrement les développeurs 
qui l'utilisait afin d'accéder rapidement aux environnements de développement, sans avoir besoin de procéder à des activations laborieuses.

**Concrètement, la licence .loc n’existe tout simplement plus.** Il faut maintenant utiliser la licence ".xml" (qui a toujours été disponible), trouvable avec les autres licences de démo sur le portail de Factory Software (nécessite un compte). 

Le processus d'activation est similaire à une licence normale. Pour rappel, il existe 2 modes d'activation :
- en mode offline, l’activation se fait avec les fichiers "send "et "receive".
- en mode online, avec internet.
Comme la licence « .loc », elle expire le 31 de chaque mois. Il faudra donc répéter cette opération tous les mois.

Il est important de préciser qu'il n'y a pas de changement de politique sur les licences perpétuelles, qui continuent de fonctionner normalement.


## Impact sur les développeurs

Pour nous, développeurs, cela signifie des temps d'interventions plus long. En effet, sur les architectures non connectées à internet, il faut procéder à l'activation de notre licence de développement (à travers les fichiers "send "et "receive") puis à sa désactivation à la fin de l'intervention (toujours à travers les fichiers). Ce qui n'était qu'un simple fichier à copier/coller/supprimer se transforme en vrai parcours du combattant.


## Impact sur les clients finaux

Les clients finaux, souvent, ne possèdent pas de licence de développement car elles peuvent représenter un certain coût. Leurs architectures étant rarement connectées à internet (ce qui permettrai une activation plus rapide), attendez-vous à ce que votre prestataire ne commence pas immédiatement son intervention (le temps pour lui de copier les fichiers send/receive et de scanner 36 fois sa clé USB à l'antivirus à chaque transfert). 

Si vous avez déjà une licence de développement, votre prestataire vous en remerciera !
 

## Solutions

Pour les développeurs d’Intouch HMI seul, une option consiste à upgrader vos applications vers la version 2023 R2 P01. A partir de cette version, la partie développement d’Intouch HMI (WindowMaker) ne nécessite plus de licence de développement.

Pour les utilisateurs de la System Plateform qui ne souhaitent pas activer la licence à chaque intervention, il faudra songer à passer à la caisse...


*Article rédigé à l'aide de l'IA.*