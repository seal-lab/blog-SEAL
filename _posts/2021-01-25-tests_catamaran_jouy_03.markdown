---
layout: post
title: "Tests du catamaran"
img: Jouy_01_2021/test_jouy_01_2021.jpg # Add image post (optional)
date: 2021-01-25 08:00:00 +0100
description: Test du catamaran avec les stagiaires
categories: [Recherche]
tags: [Surface robot, Research]
--- 


# Test du catamaran avec les stagiaires


Confinement levé, petite fenêtre météo disponible : c'est parti pour reprendre les **tests terrains** ! 
Après une tentative ratée il y a deux semaines (lac gelé), nous retentons notre chance avec nos **stagiaires** pour aller tester le catamaran.  

{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/Jouy_01_2021/lac_gele.jpg){: style="width:70%;"}<br/>
**Lors de la première tentative, les canards 🦆 faisaient de la patinoire ⛸ sur notre zone de test 😅**
{: refdef}

La veille, on valide le **check météo** et les **observations** de 3 lacs près de nos habitations respectives nous donnent des **probabilités favorables** ! On arrive en avance de phase sur zone pour **valider** la tenue du test : il y a de la neige ❄️, il fait froid 🌡, mais le lac est bien liquide 👌. Cette fois-ci on est bon 😎, on envoit le feu vert ✅ aux autres participants : Alexandre, Charles, Kévin, Quentin, Tanzim et Tony.   


{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/Jouy_01_2021/test_cata_01.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/Jouy_01_2021/test_cata_02.jpg){: style="width:49%;"}<br/>
**Charles nous rejoint : déblayage ⛄️ et déballage du matériel en attendant l'arrivée des stagiaires**
{: refdef}


L'objectif du test est de **former** les étudiants au **terrain** et à la **manipulation** du catamaran. On souhaite également évaluer nos changements apportés sur la **méthode de communication** avec le robot. 
À l'origine, les **données du contrôle manuel** du robot, qui sont composées d'ordres courts (avancer, gauche, droite, etc.) à forte cadence, et les **données de télémétries** qui comprennent l'ensemble des données brutes de tous les capteurs du robot ainsi que les paramètres des algorithmes de trajectoires du contrôleur, partageaient un **flux unique**. 

> Mais cela pouvait entrainer du lag sur le contrôle qui est pourtant plus critique que la télémétrie.

Nous les avons donc séparés en **deux flux distincts**. De plus, nous disposons de **nouvelles antennes** qui devraient nous permettre d'augmenter la **portée** et la **qualité** de transmission pour éviter les quelques coupures qui persistaient dans nos derniers essais. Et enfin, pour terminer la séance, on a prévu de **régler les PID** grâce à la procédure et aux outils d'analyse élaborés par Tanzim et Charles.  


{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/Jouy_01_2021/test_cata_03.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/Jouy_01_2021/test_cata_04.jpg){: style="width:49%;"}<br/>
**On ne touche plus à rien, ce sont les stagiaires qui font tout en suivant nos explications 📃 : ☑️ checks, ☑️ branchement et ☑️ démarrage du robot, ☑️ contrôle du fonctionnement de la communication et ☑️ des moteurs, ...**
{: refdef}

Les **champs électromagnétiques* dépendent beaucoup du lieu ou l'on se trouve, on doit donc procéder sur zone à l'**étalonnage** de la **boussole** afin de limiter les **dérives** du Nord. On en profite pour ré-étalonner au passage l'**accéléromètre** au cas où une pièce du caisson aurait bougé pendant le transport. Au cours de cette procédure, il faut faire bouger le robot sur un certain nombre de ses **axes** et ce dans **plusieurs orientations**. Il en résulte une petite danse bien étrange... 


<center>
<iframe src="https://www.youtube.com/embed/IVwfbCVXK4A" style="width: 70%; min-height:350px; border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true" allowFullScreen="true" allow="accelerometer; gyroscope;"></iframe>
<br/><strong>On se gardera bien de commenter 😙🤣</strong>
</center>

<br/>


{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/Jouy_01_2021/test_cata_05.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/Jouy_01_2021/test_cata_06.jpg){: style="width:49%;"}<br/>
**Allez hop, à l'eau 💦! Le catamaran hein, pas les étudiants 😇**
{: refdef}

Une fois que tout est **configuré** comme il faut et que les **trajectoires** sont prêtes sur la **station au sol**, les étudiants procèdent à la **mise à l'eau** (sans glisser s'il vous plait 🛷😅!) et se relaient à la gestion du câble d'accroche 🎣, aux commandes 🎮 et à la station au sol 💻. Ils commencent par finir les **checks** : on verifie à nouveau la **communication** et le **contrôle des moteurs** dans l'eau cette fois-ci.



{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/Jouy_01_2021/test_cata_07.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/Jouy_01_2021/test_cata_08.jpg){: style="width:49%;"}<br/>
**Parés, en poste ! La neige a bien fondue, mais ça congèle 🥶 toujours autant (surtout avec le vent), même si on est bien couverts 🧣🧤**
{: refdef}


Et là, **problème** avec l'un des deux **moteurs** ‼️ Et oui, on concocte tout dans les détails pour cette phase d'apprentissage pour nos étudiants : comme ça ils voient bien que les événéments piochés lors de notre [serious game]({% post_url 2020-01-22-recrutement_seal %}), ce n'était pas pour rigoler ! 

> Plus sérieusement, l'un des deux moteurs s'**arrête** instantanément lorsqu'il rentre dans l'eau. 


C'est le moteur qui avait un peu **forcé** dans la houle de la [tempête à Nice]({% post_url 2020-10-01-mission_nice_2020_03 %}). N'ayant plus temporairement de **bassin de test** à l'école le temps que des travaux se terminent, nous n'avons pas pu procéder à des **tests en eau** depuis le retour de mission. Et dans l'air, le moteur qui rencontre beaucoup moins de résistance dans ce milieu n'avait évidémment **rien laissé paraître** de son état 😒.   

> Mais bon, ce n'est pas ce genre de petit "**inconvénient**" qui va nous empêcher d'avancer 😤. 

On tente un **rodage** du moteur pour récupérer un minimum de mouvement de sa part dans l'eau et on modifie les **trim** pour **équilibrer** la puissance entre les deux moteurs et pouvoir avancer sans dévier ! Ok, ça ne permettra pas de faire le réglage des PID, mais au moins, on peut faire les tests de portée 📡.

{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/Jouy_01_2021/test_cata_10.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/Jouy_01_2021/test_cata_09.jpg){: style="width:49%;"}<br/>
**Rodage du moteur en toute délicatesse ⚙️🛠 et youpi ! On retrouve un certain contrôle de Kraken 🦑! Même s'il est à vitesse très réduite 🐌...**
{: refdef}


L'**apprentissage** se poursuit 🎓: comment faire pour ne pas **emmêler** le câble 🧶 en gérant l'enroulage/déroulage, le sens des virages et l'amplitude des virages, comment faire un arrêt d'urgence sans avoir à réfléchir où sont les commandes, etc. 

> Pour ce qui est des tests de **portées**, ils s'avèrent très **probants**. 

Il ne semble pas y avoir de **lag** (même si le catamaran avance à vitesse d'escargot avec son moteur sous triple pontage) et la **qualité** de la communication reste très **bonne** même au bout du bout du lac (environ 80m) : plus de 3 barres, alors qu'on tombait à une barre à peine lors des derniers tests pour la même distance.

> On essaye plusieurs antennes : toutes ont une portée à peu près équivalente, mais certaines se dégagent sur leur praticabilité terrain (facilité à les faire tenir droite et à les orienter).   

Pendant que les étudiants poursuivent les tests et leur formation, on en profite avec Charles pour **tourner** une **scène** dont on aura besoin pour monter les **vidéos pédagogiques** qui présenteront les **enjeux** sociétaux de la **robotique** à nos étudiants en **classes préparatoires**. Nos stagiaires qui ne sont pas à la manoeuvre à ce moment s'improvisent **régisseurs** : travail d'équipe 😉!
 

{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/Jouy_01_2021/tournage_01.png){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/Jouy_01_2021/tournage_02.png){: style="width:49%;"}<br/>
**🎥 Moteur, ça tourne, action 🎬! Euh, on va peut-être couper là, non 😜?**
{: refdef}


On arrive à la **fin** des tests que l'on pouvait faire dans ces conditions : il est temps de plier et de retourner se réchauffer en intérieur ! Le **réglage des PID**, ça sera au prochain épisode, avec un moteur tout neuf et dès que la **météo** nous le permettra à nouveau. 


{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/Jouy_01_2021/test_cata_11.jpg){: style="width:49%;"}<br/>
**🔔 Fin du test 🔜 retour au chaud 🔥😭!**
{: refdef}


*&#x21E6; Revoir :* [le post précédent sur les tests du catamaran à Jouy-en-Josas]({% post_url 2020-09-11-tests_catamaran_jouy_02 %})







