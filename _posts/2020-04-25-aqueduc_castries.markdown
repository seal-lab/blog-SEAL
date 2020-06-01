---
layout: post
title: "Aqueduc de Castries"
img:  aqueduc_castries_2018_2020/aqueduc_castries.jpg # Add image post (optional)
date: 2020-04-25 10:00:00 +0100
description: Reconstruction en 3D de l'aqueduc de Castries 
categories: [Recherche]
tags: [Aerial robot, Research, 3D Reconstruction, Education]
--- 


# Reconstruction en 3D de l'aqueduc de Castries

Nous formons nos étudiants aux principes de la **reconstruction 3D**, et nous profitons de l'occasion pour les faire travailler sur des parties de **jeux de données** qui n'ont pas encore été exploitées. C'est le cas du jeu concernant l'**aqueduc de Castries** acquis lors d'une mission terrain en **octobre 2018** dans la région de **Montpellier**. 

👉 *Retour sur cette mission d'acquisition aérienne* 

> 🎬 Donc nous voilà le 16 octobre 2018, en déplacement à Montpellier pour participer aux Journées Nationales de l'Enseignement de Robotique qui se déroulent en fin de semaine au LIRMM. 

Comme souvent à ces dates 🗓 on est tributaire de la **météo** (les déplacements sont prévus bien à l'avance, eux) et avec notre chance habituelle, ça ne loupe pas : on arrive en plein sur l'approche de la **tempête** post-tropicale Leslie 🌀 (surnommée l'ouragan zombie avant d'être reclassée, car il a erré plus de deux mois dans l'Atlantique), qui a provoqué un **épisode méditerrannéen** responsable de terribles **innondations** (vous vous souvenez, l'Aude et particulièrement le secteur de Trèbes ? Les voies SNCF ont été totalement noyées 😧 le train 🚅 ne pouvait pas aller plus loin que Montpellier...).

{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/aqueduc_castries_2018_2020/episodes_mediterraneens_2018_01.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/aqueduc_castries_2018_2020/episodes_mediterraneens_2018_02.jpg){: style="width:49%;"}<br/>
**Petit aperçu du débordement du barrage de Belbezet et de l'Hérault transformé en torrent furieux**
{: refdef}

Les **acquisitions** qui étaient prévues en **mer** et en **grotte** sont compromises 🌊 (au final les premières ont été annulées, les secondes partiellement réalisées car le niveau d'eau a pu baisser un peu). 
Et concernant l'**acquisition aérienne** ✈️ que l'on avait prévue sur l'**aqueduc de Castries**, on a réussi à chopper un créneau entre deux gouttes ! On a réalisé cette mission avec Charles, l'un de nos étudiants que l'on avait placé en **stage** chez nos collègues du **LIRMM** 🙂

{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/aqueduc_castries_2018_2020/mission_aqueduc_castries_01.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/aqueduc_castries_2018_2020/mission_aqueduc_castries_02.jpg){: style="width:49%;"}<br/>
**Équipe au complet avec "la mama" 👌**
{: refdef}


> L'Aqueduc de Castries a été construit entre 1670 et 1676 par Pierre Paul Riquet (le Canal du Midi, c'est lui !) pour amener l'eau au Parc du Château de Castries sur demande de Le Nôtre. Un petit bijou d'ingénierie : 6822 mètres de long avec une déclivité de seulement 3 mètres 😮! 

On installe la **station sol** avec la base **DGPS** 🚩à l'endroit où l'aqueduc passe de la partie aérienne avec ses immenses arceaux à une partie tunnel. Puis on **équipe** le terrain avec nos **mires** dont on mesure 📏précisément la **position absolue** pour établir une **réalité terrain** (*Ground Control Points* ou GCP) qui permettra de contrôler par la suite la précision des modèles créés.  

{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/aqueduc_castries_2018_2020/mission_aqueduc_castries_03.jpg){: style="width:33%;"}
![image]({{site.baseurl}}/assets/img/aqueduc_castries_2018_2020/mission_aqueduc_castries_04.jpg){: style="width:33%;"}
![image]({{site.baseurl}}/assets/img/aqueduc_castries_2018_2020/mission_aqueduc_castries_05.jpg){: style="width:33%;"}<br/>
**Installation de la station, équipement du terrain et mesures des GCP 📍**
{: refdef}

Et c'est parti pour deux vols avec un **quadricoptère** pour couvrir 📸une partie de la portion aérienne de l'aqueduc. La pluie 🌧nous contraint à achever l'acquisition et plier le matériel. De toute façon, la **luminosité** ayant drastiquement baissée avec le renforcement de la **couverture nuageuse**, les dernières images seront probablement difficilement utilisables (sombres et floues).

  
{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/aqueduc_castries_2018_2020/mission_aqueduc_castries_06.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/aqueduc_castries_2018_2020/mission_aqueduc_castries_07.jpg){: style="width:49%;"}<br/>
![image]({{site.baseurl}}/assets/img/aqueduc_castries_2018_2020/mission_aqueduc_castries_08.jpg){: style="width:49%;"}
![image]({{site.baseurl}}/assets/img/aqueduc_castries_2018_2020/mission_aqueduc_castries_09.jpg){: style="width:49%;"}<br/>
**Survol et exemple de photos prises depuis le drone**
{: refdef}


> 🎬 Voilà pour la mission d'acquisition ! Maintenant on dispose de tout un tas de photos 🏞 comme celles ci-dessus prises de points de vues différents que l'on va pouvoir exploiter pour reconstruire en 3D des portions de l'aqueduc.


Nos étudiants ont utilisé pour cela le **logiciel photogrammétrique** open-source [MicMac](https://micmac.ensg.eu/index.php/ "Liens vers MicMac") développé par nos collègues de l'**IGN** (chez qui ont est chercheurs associés 😉) qui utilise les techniques **multi-vues** (un point projeté est issu de plus de deux images).
 
{:refdef: style="text-align: center;"}
![image]({{site.baseurl}}/assets/img/aqueduc_castries_2018_2020/aqueduc_castries_reco_3D.jpg){: style="width:70%;"}<br/>
**Aperçu du nuage de points 3D dense créé avec MicMac 🙂**
{: refdef}


> Il reste encore du travail 🖌: reconstruction complète de toute la portion survolée, contrôle de la précision du nuage produit, etc. 

<center>
<iframe style="width: 90%; min-height:400px;" src="https://www.youtube.com/embed/wcCOdZV8DaE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br/><strong>Un petit résumé en vidéo ?</strong>
</center>

  

















