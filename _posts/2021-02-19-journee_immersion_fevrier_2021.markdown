---
layout: post
title: "Journées d'immersion 2021"
img: journee_immersion_fevrier_2021/journee_immersion_fevrier_2021.png # Add image post (optional)
date: 2021-02-19 08:00:00 +0100
description: Atelier de découverte des métiers des sciences du numérique
categories: [Education]
tags: [Education, Ground robot, Lab life]
--- 


# Test de la nouvelle méca des robots araignées

Aujourd'hui on accueille des lycéens pour leur faire **découvrir** 👀 les différents **domaines** des **sciences du numérique** de manière plus concrète 🙌 via des **ateliers**. Au programme de ces **journées d'immersion** de février : des ateliers de programmation, d'IA mais aussi de **robotique** avec nos petites **araignées** 🕷! 

> Mais cette fois-ci, ce n'est pas un atelier comme les autres pour nous, car on inaugure la nouvelle structure mécanique de notre araignée ! 


{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/journee_immersion_fevrier_2021/spider_new_meca.jpg){: style="width:60%;"}<br/>
**La nouvelle méca, pré-assemblée à la sortie de l'imprimante 3D**
{: refdef}


La structure initiale présentait des points de **faiblesse** entrainant la **casse** prématurée de certaines pièces ou des servos-moteurs. Et la forme des pattes, qui se terminaient en pointes, provoquait un **glissement** sur certains sols ou en fonction de certains mouvements. De plus, par la complexité des pièces, le **montage** était **très long** ⏳, ce qui n'est pas le but de l'exercice pédagogique qui se concentre sur la **programmation** du robot. Cette complexité se retrouve aussi dans le packaging et la logistique des **kits**, qui demandent énormément de temps pour le tri, la maintenance et la réparation.

> Ce sont tous ces points que vise à améliorer la nouvelle mécanique sur laquelle ont principalement travaillé Alice puis Quentin. 


{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/journee_immersion_fevrier_2021/spider_plastique.png){: style="width:33%;"}
![image]({{site.baseurl}}/assets/img/journee_immersion_fevrier_2021/spider_bois.png){: style="width:33%;"}
![image]({{site.baseurl}}/assets/img/journee_immersion_fevrier_2021/spider_seal_new_meca.png){: style="width:33%;"}<br/>
**▶ Premier modèle en acrylique (pièces cassantes qu'on avait dû remplacer par des pièces imprimée en 3D) <br/> ▶ Deuxième modèle en bois (plus solide sur la structure mais pas du côté des servo-moteurs) <br/> ▶ Troisième modèle fait maison imprimé en 3D**
{: refdef}

Toutes les pièces sont entièrement codées sur **OpenSCAD** pour faciliter les **modifications futures**. Quentin et Tony ont effectué pendant leur stage une première **restructuration du code** 💻, passant d'un code monolithe simple à une structure objet plus modulaire. Cela permet de mieux séparer les parties utiles à la pédagogie par rapport au code plus bas niveau.  Mais il reste encore beaucoup de boulot sur ce point. Idem du côté de l'**électronique** que nous envisageons de changer prochainement pour fiabiliser l'**interrupteur** et pour offrir la possibilité d'ajouter facilement des **capteurs**. 



{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/journee_immersion_fevrier_2021/journee_immersion_02.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/journee_immersion_fevrier_2021/journee_immersion_01.jpg){: style="width:49%;"}<br/>
**L'instant de vérité sur le montage : quelques vis à la taille non adaptée, quelques pièces qui cassent (on va devoir changer les paramètres d'impression 3D et passer à un remplissage de 100% pour certaines parties !), un tuto pas encore bien ficelé... Mais rien de bien méchant, ça passe ✌️!**
{: refdef}


Les **étudiants SEAL** sont sur le pont ⛑ pour nous seconder et s'assurer que tout se déroule bien ! En tout cas, les petites araignées V2 ont bien tenu le choc ! Et même si elles ont encore besoin d'**ajustements** 🛠, elles ont totalement rempli l'**objectif** d'accélération du temps de montage 👌. 


<center>
<iframe style="width: 90%; min-height:400px;" src="https://www.youtube.com/embed/qWB483XOjBY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br/><strong><em>La nouvelle méca des araignées en mouvement 😎 : les lycéens se sont même amusés à les faire danser 💃🕺</em></strong>
</center>

<br/>


*&#x21E6; Revoir :* le post sur la journée [EPITA Inside]({% post_url 2020-03-07-epita_inside %}) en Mars 2020<br/>
*&#x21E6; Revoir :* le post sur l'[Escape Game]({% post_url 2020-02-18-escape_game %}) de Février 2020
  
 







