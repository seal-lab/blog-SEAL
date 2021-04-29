---
layout: post
title: "Inventaire & QR codes"
img: qr_codes_inventory_launch/qr_codes_inventory_launch.jpg # Add image post (optional)
date: 2021-03-12 08:00:00 +0100
description: Application du labo
categories: [Lab]
tags: [Lab life]
--- 


# Gestion du matériel pédagogique robotique par QR codes

Le **côté cool** et **séduisant** de la **robotique** en pédagogie, c'est l'aspet **concret** 😏. Mais l'envers du décors, le **côté obscur**, c'est la **gestion du matériel** 😱😱. 

> Recherche des références/fournisseurs 💻, commandes 🛒, notes de frais 🧮🧾, suivi des colis 📦, réclamation ☝️, réception 📬, dépackaging ✂️, étiquettage 🏷, packaging 🎁, stockage 📥, déstockage 📤, récupération 📥, relance 📣, vérification 🔍, réparation 🛠, inventaire 📋, re-recherche de références/fournisseurs 💻, re-commandes 🛒, re-notes de frais 🧮🧾... 🌀🌀

Et ce qui **complexifie** encore plus la gestion, c'est que certains matériels sont **partagés** entre plusieurs activités (cours, projets de fin d'étude ou encore projets labo par exemple) et donc il faut viser juste sur les périodes de **mobilisation** 🤹 et ne pas s'emmêler les pinceaux. 

Concrètement jusque là, on **étiquetait** 🔖 chaque unité avec un numéro unique. Et le tout était dûment **répertorié** 📝 dans un **tableur** aux multiples onglets. Quand un matériel était fourni à un étudiant (ou mis dans un kit), on recherchait son onglet, son type et son numéro et on **inscrivait** le nom de l'étudiant (ou du kit) dans la cellule correspondante. Lorsqu'il était rendu, on effectuait les mêmes étapes pour repasser le matériel en **stock**. 


Bon **en réalité**, ça c'est le fonctionnement quand tout va bien. Sauf que dans la **vraie vie** 🧐, les étudiants ne rendent pas tous le matériel **dans les temps**. Et sauf que dans la **vraie vie** 😓, il y a aussi des périodes de **rush** (souvent) (trop souvent) qui se **cumulent** aux périodes de rush des étudiants : combien de fois, déjà enlisés dans plusieurs tâches à réaliser en simultané, n'avons-nous pas pu prendre le temps d'attraper l'**ordinateur** pour noter dans le tableur (en se disant qu'on oubliera pas 🤣... 😭) tout le matériel demandé en **urgence** par plusieurs groupes d'étudiants car l'**évaluation** tombait le **lendemain** ?


> Tu sais où est passée la Pi n°35 ? Ils ont fini par ramener le matériel, le groupe 4 ? Et la Arduino 57, elle a été rendue ? La caméra 22 ? ah, elle est affectée au Kit Vision pour le projet Car... 🧩 Regarde combien on a de câbles disponibles, ça ira pour le nombre de kits qu'on doit fournir pour le cours à la fin du mois ?  🤯


Pour nous **simplifier la vie** 🥺 et gagner un peu de temps ⏱, on passe enfin à une **vraie base de données** et surtout à un système de **scan** par **QR Code**. On rentre le matériel dans la base lors de l'**inventaire**, on **génère** les QR codes pour chaque objets à la taille voulue, on **imprime** et on **étiquette**. Ensuite, il n'y a plus qu'à **scanner** le code pour retrouver la **fiche** de l'objet (un téléphone connecté suffit), puis scanner la **carte** de l'étudiant pour l'**attribuer** (ou demander une remise en stock lors du retour du matériel).


{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/qr_codes_inventory_launch/qr_codes_inventory_launch_01.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/qr_codes_inventory_launch/qr_codes_inventory_launch_02.jpg){: style="width:49%;"}<br/>
**Planche de QR codes pour une série d'étiquettage et kit Arduino à scanner (les éléments qui le composent sont déjà scannés et attribués au kit) et à attribuer grâce au scan de la carte étudiante**
{: refdef}

Le **développement** de ce service a été réalisé par **Eliaz** pendant son **stage** au labo lors du second semestre 2020. Aujourd'hui, après avoir fait **une partie** de l'inventaire du matériel et collé des QR codes partout 🤪, on le **met à l'essai**. Et pour l'instant, on en est plutôt **contents**  et le **gain de temps logistique** est perceptible 👍! En tout cas, c'est **prometteur** et on a déjà des idées d'amélioration 😁.




