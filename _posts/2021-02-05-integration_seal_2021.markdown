---
layout: post
title: "Semaine d'intégration SEAL"
img: integration_seal_2021/integration_seal_2021.jpg # Add image post (optional)
date: 2021-02-05 08:00:00 +0100
description: Parcours d'étudiants
categories: [Lab]
tags: [Lab life, Education, Ground Robot]
--- 


# Semaine d'intégration des nouveaux étudiants SEAL

Pendant toute la semaine, nous avons **accueillis** 🤗 les **nouveaux étudiants** pour les **former** et les faire monter en **compétences**. Il a fallu faire avec un **emploi du temps** 🗓 un peu **chargé** cette année car en raison du couvre-feu, une partie des **évaluations** prévues dans les semaines précédentes ont glissé ➿ jusque là. 

> On a démarré par la *formation Arduino* qui s'est déroulée en distanciel, avec notre kit 🧰 et le *skillbook* 📘 associé. 

Cette formation permet d'appréhender, entre autres, les **entrées/sorties** d'un **micro-contrôleur**, leurs types, la gestion de l'**alimentation**, l'utilisation de **LEDs**, de **résistances** fixes et variables, de **boutons** poussoirs ou interrupteurs et de **servo-moteurs**.

> Puis nous avons lancé l'*atelier Ardupilot Flash Car*, en présentiel.

L'objectif était dans un premier temps de monter la **carte mère** utilisée par tous nos robots recherche sur la [**plateforme pédagogique** roulante]({% post_url 2019-09-05-evaluation_voir_2019 %}) 🚙, de réaliser tous les **branchements** 🔌 des moteurs et de l'alimentation correctement puis de **paramétrer** et **flasher** notre version d'[Ardupilot sur l'ESP32]({% post_url 2020-12-16-flying_esp32_12_2020 %}). Enfin, il fallait prendre le **contrôle** de la voiture via **QGroundControl** installé sur téléphone et la **piloter** 🎮 dans le lab et les couloirs alentours. 



{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/integration_seal_2021/ardupilot_flash_car_01.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/integration_seal_2021/ardupilot_flash_car_02.jpg){: style="width:49%;"}<br/>
***Atelier Ardupilot Flash Car* : ça branche, ça compile, ça flash et ça roule ! Enfin, ça, c'est la théorie... 😇**
{: refdef}


> Sur le second jour, on s'est attaqué aux Raspberry Pi via la *formation Headless Pi* en distanciel avec kit 🧰 et *skillbook* 📘, suivi de la mise en pratique en conditions via le *Pi Ground Challenge*.   


L'idée est d'apprendre à utiliser les **Pi** sans le confort du labo : nous n'avons pas toujours d'**écran** 🖥, de **souris** 🖱 et de **clavier** ⌨️ à portée de main, encore moins de **WiFi** 📶. Il faut donc être capable de travailler avec juste le **PC portable** et la **Pi** pour pouvoir **installer l'image**, la **configurer**, **lancer** les actions et **vérifier** qu'elles se sont bien déroulées. Après l'**entrainement** du matin, le tout est mis en pratique en **milieu extérieur** 🌲🌳. 

> La mission était d'acquérir 📸 des jeux d'images 🏞 pour l'auto-calibration d'une piCam.     


{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/integration_seal_2021/headless_pi_01.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/integration_seal_2021/headless_pi_02.jpg){: style="width:49%;"}<br/>
**Entrainement au chaud, puis mise en pratique terrain. Mais non, il ne fait pas froid 🥶, c'est dans la tête 😜 (on avait prévenu de bien se couvrir 😙).**
{: refdef}


> Le troisième jour, on lance la *formation ROS*, qui s'est déroulée en distanciel et en trois parties jusqu'à la fin de la semaine. 


ROS est un **interlogiciel** qui permet d'architecturer le code de l'unité haut-niveau de manière **fiable** et **robuste**&nbsp;: chaque méta-tâche est lancée de manière **autonome** sous la forme d'un **noeud**, la **communication** entre noeuds est native et un noeud maître **orchestre** l'ensemble 🌐 et relance les noeuds qui ont **crashés** sans que cela n'impacte le fonctionnement des autres (ROS 1).

> On a enchaîné l'après-midi sur un *atelier d'intelligence coopérative* sur l'état de l'art scientifique 🎓. 

Cet atelier avait un **double objectif** : d'une part mieux comprendre **à quoi sert un état de l'art** et **comment s'y prendre** pour le réaliser 📚📑 et d'autre part **découvrir des outils de *design thinking*** permettant un travail en groupe efficace. 
 

> Le quatrième jour, on passe sur l'*atelier Ardupilot Explore*. 

Cette fois-ci on est sur le **robot roulant** 🚙 utilisé en recherche, Mabouya 🦎, qui est équipé d'un GPS 📍. L'objectif était de **familiariser** les étudiants avec l'**utilisation** et l'**opération** des robots du labo : checks, branchements & démarrage, utilisation de QGroundControl pour planifier les trajectoires à réaliser, procédures d'arrêt d'urgence, ... 


{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/integration_seal_2021/ardupilot_explore_02.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/integration_seal_2021/ardupilot_explore_01.jpg){: style="width:49%;"}<br/>
**Prise en main de la bête 🦎🤨: on se rassure, elle ne mort pas (trop) 😇**
{: refdef}


> Le scénario du challenge : on est sur une base martienne, le robot est un *rover* et une première équipe a découvert par satellite 🛰 une zone d'intérêt pour prélever des échantillons, mais on ne dispose pas d'assez de détails pour définir un parcours pour s'y rendre avec le *rover*. 


À l'aide des **images satellites**, on a pu identifier 🗺 **4 passages** possiblement **praticables**. Cependant, on ne sait pas s'ils permettront d'arriver à la **zone cible**. On établit donc des **checkpoints** à mi-parcours et chaque équipe essaye d'y envoyer le robot (euh... le *rover*) pour obtenir des **informations** sur la suite du chemin. Le *rover* ramène ensuite ces données à la base et la **carte** est complétée 🧩. 

> Le terrain connu est matérialisé par des plots jaunes 🔸 pour les checkpoints 📍 et rouges 🔻 pour les rochers ⛰ qui bloquent le chemin. 

Les données sont **partagées** entre les équipes et chacune d'entre-elles peut **programmer** de **nouvelles trajectoires** en prenant en compte les **observations** déjà réalisées. Les **essais** s'enchainent jusqu'à trouver 🧭 un chemin praticable qui mène à la zone cible 🎯 (pratiquer c'est répéter plusieurs fois une action jusqu'à ce qu'elle passe en routine 😋). 

 
 
{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/integration_seal_2021/ardupilot_explore_03.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/integration_seal_2021/ardupilot_explore_04.png){: style="width:49%;"}<br/>
**Élaboration des trajectoires, et c'est parti pour l'aventure 🤠: explorons cette zone mystérieuse et inconnue&nbsp;! Les plots ♟ matérialisent les repères géologiques découverts.**
{: refdef}
 
> Cinquième jour : pour clore la semaine, on termine sur un serious game sur la démarche scientifique


C'est le **tout nouveau serious game** que nous avons développé depuis le [Haggle Robotique]({% post_url 2020-01-22-recrutement_seal %}). Tellement nouveau que la conception n'est **pas terminée** : nous n'avons pas pu faire un test complet au préalable et la quantification (temps, quantité des éléments, etc.) n'est pas réglée. Les étudiants ont donc pu, tout en y participant, découvrir l'**envers du décors** et voir comment se passe la **création d'un jeu** (naan, on ne les a pas utilisés en cobayes 👩‍🔬😙).

> Ce serious game est inspiré du jeu [Éleusis+Nobel](https://fr.wikipedia.org/wiki/%C3%89leusis_(jeu) "Lien vers une description du jeu").  

L'objectif est de leur faire découvrir les **mécanismes** et **leviers** de la **démarche scientifique** (♻️ observations - hypothèses - tests ♻️) ainsi que la manière dont fonctionne le **monde scientifique** (🎙 partages & communautés, 💰 financements, etc.). 


{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/integration_seal_2021/serious_game_01.jpg){: style="width:33%;"}
![image]({{site.baseurl}}/assets/img/integration_seal_2021/serious_game_05.jpg){: style="width:33%;"}
![image]({{site.baseurl}}/assets/img/integration_seal_2021/serious_game_03.jpg){: style="width:33%;"}<br/>
**Les labos, un plateau d'expérimentations et les participants en pleine conférence annuelle**
{: refdef}



Et hop, ça y est, c'est terminé 😢. Voilà nos étudiants **intégrés** 🥳👍 et surtout mieux armés 🛡🛠🧢 pour attaquer les **challenges** dont le premier *round* démarre dès la semaine prochaine 😜: c'est parti ! ***Welcome to SEAL Research Team*** 😁🤝!



*&#x21E6; Revoir la composition de* [l'équipe étudiante SEAL 2021]({% post_url 2021-01-18-nouvelle_equipe_etudiante_2021 %})







