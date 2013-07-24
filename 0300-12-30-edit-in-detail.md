---
layout: doc
title: Editing with JOSM
permalink: /fr/beginner/editing-with-josm
lang: fr
category: beginner
---

# Editer en détail

## Introduction

Dans ce chapitre, nous allons décrire les relations, les outils d'édition JOSM, et les techniques d'édition plus en détail.

> Bien que ce chapitre ne soit pas très avancé, il est plus difficile
> que les chapitres précédents. Si vous sentez que vous n'avez pas bien compris 
> les leçons précédentes, vous pouvez vous pratiquer un peu plus 
> avant de continuer.

Les sujets abordés dans ce chapitre:

- Outils d'édition: Outils, le plugin de construction, et les raccourcis

- Relations: Description et comment modifier et ajouter des attributs

- Techniques d'édition: Les **Fait** et **Ne fait pas**

## Outils d'édition JOSM

Il y a quelques façons d'accéder à des outils d'édition supplémentaires dans JOSM. Nous allons
examiner de plus près les outils par défaut, certains greffons, puis les raccourcis clavier d'édition.

### Outils de dessin

JOSM a des outils supplémentaires pour faciliter le tracage des lignes et des formes. Ces outils se trouvent dans le menu "Outils" au haut de JOSM.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image12.png)

Afin d'appliquer les fonctions de ce menu, vous devez d'abord sélectionner un
point, une ligne ou une forme dans la fenêtre Carte. Quelques unes des fonctions les plus utiles sont décrites ci-dessous:

1. Couper un chemin: Cela vous permet de diviser une ligne en deux lignes distinctes.
     Ceci est utile si vous souhaitez ajouter des attributs différents pour différents sections d'une route, comme un pont. Pour utiliser cette fonction, sélectionnez un
     point au milieu de la ligne que vous voulez partager, Sélectionnez **Couper le chemin** dans le menu Outils, et votre ligne sera scindée en deux.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image38.png)

2. Fusionner les chemins: Ceci fait le contraire de la fonction Couper un chemin. Pour combiner deux 
     lignes en une seule, elles doivent partager un seul point. Pour utiliser
     cette fonction, sélectionnez les deux lignes que vous souhaitez combiner. Vous pouvez
     sélectionner plus d'un objet en maintenant la touche MAJ de votre
     clavier et en cliquant sur chaque ligne. Lorsque vous avez sélectionné les deux
     lignes, sélectionnez **Fusionner les chemins** dans le menu Outils.
	 
    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image28.png)

    > Si vous tentez de fusionner des routes qui ont des directions différentes,
    > le message d'avertissement suivant s'affichera:

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image15.png)

    Si les routes sont connectées et vont dans la même direction, choisissez alors
    \<\<Reverse and Continue\>\>.

3.  Inverser le chemin: Cela va changer la direction de la ligne. Si la ligne ne représente pas correctement une rivière ou une route à sens unique, vous voudrez sans doute changer sa direction. A moins que quelqu'un aie délibérément créé un chemin avec attribut sens unique, vous n'avez généralement pas à vous soucier de modifier
     l'instruction parce que les chemins dans OSM peuvent par défaut aller dans dans les deux sens.
     ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image26.png)

4.  Simplifiez le chemin: Si votre ligne a trop de points et que vous souhaitez la simplifier, cela va enlever quelques-uns des points de la ligne.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image41.png)

5.  Créer un cercle OU aligner les nœuds en cercle: Si vous essayez de faire une forme circulaire, dessiner le cercle du mieux que vous pouvez, puis sélectionnez
     trois noeuds et la fonction. Elle aidera à organiser vos points dans un     cercle.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image04.png)

6.  Aligner les nœuds sur une ligne: Cette fonction permettra d'aligner une série de points
     dans une ligne droite. Avec de longues lignes, il est préférable de sélectionner les sections
     de la ligne à redresser. Soyez prudent car cela ne le
     tendance à déplacer la ligne un peu.
	 ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image17.png)

7.  Rendre une forme Orthogonale: Cette fonction est très utile pour dessiner des
     formes régulières comme les bâtiments. Après avoir dessiné une zone, cette
     fonction permet de la remodeler pour avoir des coins carrés. Cette fonction est
     plus utile pour d'autres fonctions de forme régulière, comme les tennis,
     tribunaux ou les zones d'utilisation du sol. (L'utilisation du greffon bâtiment, qui sera
     expliqué ci-dessous, peut être plus facile).

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image45.png)

8.  Décoller un chemin: Cet outil vous permet de détacher les nœuds qui sont
     connectées.
	 
    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image59.png)

    > La ligne et le noeud n'apparaîtront pas effectivement séparé comme la dernière  Capture d'écran l'implique.

### Greffons

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image25.png)

A.  Greffon Immeubles: Ce greffon est de loin l'un des plus utiles parmi les outils d'édition (numérisation). Cet outil vous permet de créer des formes
avec des angles à 90 degrés avec seulement trois clics. Tout d'abord, vous tracez le
bord de votre bâtiment, puis vous faites glisser sur la ligne d'en faire un
polygone.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image58.png)![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image19.png)

Vous pouvez également créer des bâtiments plus complexes à l'aide de l'option de fusion.
 Créez votre plan de construction, sélectionnez tous les polygones (appuyez sur MAJ pour tous les mettre en évidence) et ensuite MAJ + J pour fusionner les objets.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image03.png)

En outre, vous pouvez modifier les paramètres par défaut (taille et attributs) à partir du menu
\<\<Edit\>\>. Vous sélectionnez ensuite au bas du panneau “Définir la dimension de l'immeuble”.  

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image07.png)

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image11.png)

Si vous traitez une série d'immeubles de dimension similaire, vous pouvez modifier la taille des immeubles pour une certaine dimension, soit par exemple 5 x 6 mètres (l'unité est en mètres).  Encore plus, si vous cartographiez des infrastructures similaires, telles que des bungalows dans une même zone, vous pouver éditer les attributs pour être tous identiques à partir de l'onglet  \<\<Advanced\>\>.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image13.png)![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image64.png)

B. Utilsplugin2 (Plus d'outils):  Ce greffon a quelques fonctionnalités qui peuvent être utiles pour éditer.  

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image47.png)

Après l'installation du grefffon et le redémarrage de JOSM, l'onglet suivant sera ajouté :  \<\<More Tools\>\>:

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image24.png)

Ces outils se sont révélés être les plus utiles:

1. Ajout de nœuds aux intersections: Cet outil est très utile pour ajouter
     des nœuds manquants aux intersections de voies sélectionnées. Il est une bonne
     pratique que les routes et les rivières aient toujours des nœuds communs à leur intersection.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image43.png)

2. Copiez les attributs de la sélection précédente: Cette fonction facilite la copie des attributs. Si vous voulez créer plusieurs objets avec les mêmes attributs,
     dessinez d'abord les objets. Puis ajoutez les attributs à un objet. Cliquez ensuite sur un autre objet et appuyez sur Maj + R pour copier les balises de l'objet précédemment sélectionné. Vous pouvez le répéter pour tous les objets que
     que vous souhaitez marquer. Rappelez-vous que les attributs seront copiés à partir de l'objet sélectionné précédemment. Donc, si vous cliquez sur un objet sans attribut
     puis ensuite un autre objet sans attribut, vous ne serez pas en mesure de copier des attributs.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image05.png)

3. Ajouter un Attribut Source: Cet outil simplifie l'ajout d'un Attribut Source. Il
     se souvient de la source qui a été spécifiée en dernier et il ajoute cet attribut source à vos objets. Vous pouvez insérer la source 
	 avec un seul clic.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image63.png)

4. Remplacer la Géométrie: Cet outil est idéal si vous voulez redessiner un objet mal dessiné tout en conservant l'historique, les attributs le ID de l'objet. Par exemple, si vous apercevez un immeuble
     qui est compliqué et mal dessiné, alors au lieu de l'opération pénible de modifier chaque nœud, vous pouvez (2) juste dessiner à nouveau l'objet
     (3) Sélectionnez l'objet ancien et le nouveau (4) appuyez sur ¨Remplacer la géométrie¨ pour transférer tous les informations sur le nouvel objet.

C. Utilsplugin2 (Sélection):

Et vous avez accès à davantage de \<\<Selection\>\>
tool:![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image55.png)

Ces outils se sont révélés être les plus utiles:

1. Désélectionner les nœuds: Cet outil vous permet de désélectionner les nœuds, ce qui rend
     utile pour le marquage des objets sélectionnés. Cet outil est nécessaire si
     vous avez mappé plusieurs objets polygonaux avec des attributs similaires et
     tenez à modifier les attributs des objets sans ajouter ces attributs aux nœuds. Pour ce faire,
     sélectionnez tous les objets - des polygones, des chemins et des relations - dé-sélectionnez
     les nœuds et ajoutez ensuite les attributs de manière appropriée.
	 ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image50.png)

2. Sélectionnez les derniers nœuds modifiés: Cet outil vous permet de revenir aux
     nœuds qui vous avez récemment changé. C'est comme une opération Annuler: style de nœud.
     

Amusez-vous à les utiliser!

## Relations

Dans le Guide du débutant, nous avons appris qu'il y a trois types d'objets
qui peuvent être dessinés dans OpenStreetMap - des points (nœuds), des lignes (voies), et
des polygones. Les Lignes contiennent de nombreux points, et la ligne elle-même porte
les attributs qui définissent ce ces noeuds représentent. Les Polygones sont similaires aux
lignes, à l'exception que la ligne est tracée de façon à ce qu'elle se termine là ou elle a commencé, afin de
former une forme.

En fait, il y a un autre type d'objet dans OpenStreetMap, et celui-ci est appelé relation. De la même manière qu'une ligne comprend une série de points, une relation contient un groupe d'autres objets, qu'il s'agisse de points,
lignes ou des polygones. Si vous voulez développer des compétences d'édition avancée, il est important de comprendre les relations et de savoir les éditer.

Par exemple, imaginez que vous souhaitez dessiner un bâtiment qui a des cours, jardins dans le centre. Vous auriez besoin de dessiner un polygone à l'extérieur du
l'immeuble, et indiquer que les polygones autour des cours ne font pas partie de l'édifice. Ceci est un exemple où s'applique une relation. La relation devrait contenir plusieurs polygones - et les attributs de l'immeuble êtres fixés à la relation et non à chaque polygone.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image42.png)

Les relations sont utilisées pour représenter quoi que ce soit qui nécessite de définir une collection d'objets. D'autres relations peuvent être définies par exemple pour des lignes de bus (une collections de lignes), des objets longs et complexes (rivières ou routes), ou des polygones multiples qui font tous partie du même endroit (comme les bâtiments d'une université).

Il existe principalement quatre types de relations que vous rencontrerez dans OSM:
Multipolygones, Routes, Frontières, et restrictions (telles que, pas de virage à gauche). Dans cette section, nous allons passer en revue les multipolygones et Routes.

A. Éditer les Relations: Le multipolygone ci-dessus contient un polygone pour les
limites extérieures du bâtiment et deux autres pour marquer les cours intérieures.
Pour créer une relation avec ces trois polygones, vous devez:

1. Sélectionnez tous les polygones.

2. Aller à ¨Outils¨ et près du bas ¨multi-polygone¨
    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image49.png)

3. Les polygones doivent automatiquement être créé en tant que multi-polygone.

     ! [] ({{}} site.baseurl / images/intermediate/en_edit_in_detail_image14.png)

Vous verrez alors votre bâtiment représenté avec une surface solide et les polygones intérieurs représentés avec des vides. Les données sous-jacentes de la relation dans cet
exemple sont visibles sur OpenStreetMap:[http://www.openstreetmap.org/browse/relation/2435797](http://www.openstreetmap.org/browse/relation/2435797).
Le bâtiment est rendu par Mapnik comme sur cette image:

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image00.png)

[OSM Wiki: Relation:
MultiPolygon](http://wiki.openstreetmap.org/wiki/FR:Relation:multipolygon#Un_anneau_externe_et_un_anneau_interne)

B. Une autre MultiPolygon

Cette rivière est un autre exemple de multipolygone. En effet, il est similaire à l'exemple d'immeuble, mais avec un plus grand nombre de membres et
couvrant une superficie beaucoup plus grande. Il peut être consulté sur le site OpenStreetMap
ici:
[http://www.openstreetmap.org/browse/relation/1046961](http://www.openstreetmap.org/browse/relation/1046961.).

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image61.png)![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image23.png)

Cette rivière contient dix lignes qui sont connectées comme un long polygone.

C. Relations de Lignes

Les relations sont également très utiles pour la création, l'étiquetage et l'édition de longues lignes, par exemple, des lignes de bus, des sentiers pédestres, des pistes cyclables, etc.
  Elles se distinguent des multipolygones parce qu'elles sont les relations avec des
membres, contrairement aux multipolygones complexes. Une relation de lignes pourrait simplement être une
ligne avec plusieurs membres, ceux-ci étant intégrés dans la relation comme tels. Des
caractéristiques supplémentaires, comme les arrêts de bus représentés par des nœuds distincts peuvent également être intégrés en tant que membres de la relation.
![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image27.png)![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image37.png)

1. Assurez-vous que tous les chemins par lesquels la route passe ont les bons attributs. Par exemple, highway= footway.

2. Sélectionnez toutes les routes ou chemins que prend le bus. Si vous
     voulez seulement sélectionner certaines parties du chemin, là, malheureusement, vous
     devrez diviser le chemin dans la section que vous souhaitez sélectionner. Cela
     crée plus de travail, mais vous pouvez facilement le faire avec l'outil ¨Couper le chemin¨. Une fois que tous ou une partie des chemins sont sélectionnés, cliquez sur Modifier dans le panneau d'édition de Relation. La boîte de dialogue d'Édition de Relation apparaîtra.

3. Allez dans le menu Attributs et
	sélectionnez successivement dans le menu déroulant : Transport, puis Transport Public, puis Public transport route ou Itinéraire maitre. L'Itinéraire maitre est l'itinéraire principal, tandis que la route est une variante de l'itinéraire du bus.
    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image54.png)

4. Remplissez les informations correspondantes relativement à la ligne de bus.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image60.png)

Les relations sont parfois difficiles à comprendre et n'ont pas nécessairement à être utilisées souvent. Il est cependant important de les connaitre.  À mesure que vous développez vos compétences avec OSM et voulez créer des objets plus complexes (ie. immeubles, rivières et routes), les relations seront utiles.

## Techniques d'édition : Les Faire et ne pas faire

Dans cette section, nous couvrirons quelques erreurs communes dans JOSM et fournirons quelques trucs d'édition pour rendre votre travail dans JOSM plus efficient !

A. Certains objets ne doivent pas être connectés

Lorsque vous créez des polygones et des lignes qui ne sont pas censés être
connecté, assurez-vous qu'ils ne sont pas fusionnés ensemble en partageant un
nœud. Par exemple, les nœuds routiers ne doivent pas être accrochés aux bâtiments,
parce que personne n'aime une route qui mène directement dans un mur! Si vous
voulez démêler deux ou plusieurs objets qui partagent le même nœud, sélectionnez
le nœud, puis appuyez sur \<\<G\>\>.  

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image32.png)  ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image62.png)

Mais, certains objets doivent se connecter

Toutefois, certains objets doivent toujours se connecter! Les Intersections de routes devraient
toujours être connectées. Si deux routes ne partagent pas un noeud commun, alors l'ordinateur n'a aucun moyen de savoir que les routes se connectent une à l'autre.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image20.png)

B. Chevauchement des objets

Une erreur courante est de superposer des polygones lorsque les objets qu'ils
représentent ne se chevauchent pas dans la vraie vie. Un bâtiment ne peut pas chevaucher
un autre bâtiment. Cette erreur est souvent faite avec des bâtiments et les polygones
LANDUSE. Par exemple, un polygone dessiné pour représenter un parc
à l'extérieur d'un bâtiment ne doit pas se chevaucher avec le bâtiment. Au contraire, il
doit être aligné à côté du bâtiment.

Il y a quelques exceptions à cette règle, comme les écoles. Dans une
cour d'école, vous pourriez identifier les bâtiments individuels en utilisant des polygones.
Vous pourriez également vouloir créer un polygone autour de la cour de l'école tout entière.
  Dans ce cas, il est acceptable que les polygones se chevauchent, mais la règle à
suivre ici est de s'assurer que les bâtiments sont complètement à l'intérieur du
polygone LANDUSE.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image46.png)  ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image18.png)

Nous faisons tous des erreurs, et que vous mappez plus vous ferez moins d'erreurs!
  N'oubliez pas que même si vous téléchargez de données qui contient des erreurs, il
est simple à corriger vos erreurs et télécharger le nouveau changement. c'est
ce qui est formidable à propos OSM: vous pouvez toujours faire mieux!

C. Recherche correctement

OSM peut faire des choses étonnantes avec identifiant si fin et objets
ce qui qualifie ces objets devraient avoir, mais il a besoin de votre aide
faire. Par exemple, si vous créez une route qui se transforme en une autre
route sans un nœud distinct, puis JOSM continuera d'étiquetage de la route
comme la précédente. Par conséquent, il est nécessaire que vous fassiez tous
vos routes et des objets de façon claire et rigide que possible.

^[[a]](#cmnt1)^

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image57.png)

Nous terminerons ce chapitre avec ce cadeau:

- Faire pivoter un objet: Si vous maintenez la touche MAJ + CTRL enfoncée et faites glisser votre souris
     clic, vous pouvez faire pivoter les objets sélectionnés.  

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image31.png)


## Résumé

Comme vous pouvez le voir, il ya de nombreuses fonctionnalités supplémentaires qui rendent un JOSM
outil puissant pour faire des cartes. Rappelez-vous que plus vous pratiquez avec
ces outils, le meilleur vous deviendrez à ajouter des informations à
OpenStreetMap.

## Annexe 

### Raccourcis clavier

Parfois, il peut être gênant de cliquer à plusieurs reprises pour sélectionner différents
options et les menus dans JOSM. Heureusement, il ya des touches de raccourci sur le
clavier qui vous permettent de faire de nombreuses tâches courantes (je recommande fortement l'
DEL raccourci). Voici une liste de quelques-uns des plus couramment utilisés
touches de raccourci, ainsi que ce qu'ils font:
        

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image10.png)Chooses the Select tool

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image08.png)Deletes Selected Object

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image30.png)Chooses the Draw Tool

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image36.png)Chooses the Zoom tool

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image21.png)Zoom In

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image09.png)Zoom Out

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image01.png)Split Way

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image34.png)Combine Ways

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image29.png)Align in Circle

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image53.png)Align in line

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image40.png)Orthogonalize (make a shape square)

### More information on the \<\<Selection\>\> Tools.  All of this
information was taken from
[http://wiki.openstreetmap.org/wiki/JOSM/Plugins/utilsplugin2](http://wiki.openstreetmap.org/wiki/JOSM/Plugins/utilsplugin2).
 

A. Sélection des noeuds adjacents (e): Sélectionne les voisins de déjà sélectionné
nœuds. Se souvient des moyens actifs lorsqu'ils sont utilisés en premier et les remplit avant
de passer à d'autres moyens. Si certains égards, sont déjà sélectionnés, nous n'utilisons que des
les faire avancer la sélection. Si seuls moyens sont sélectionnés, les nœuds sont
sélectionné à la place.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image52.png)

Exemple d'utilisation: sélectionnez un nœud (et éventuellement son chemin), appuyez sur E (3
nœuds sont à présent sélectionnés), appuyez sur L pour mettre le nœud sur la ligne droite.

B. Sélectionnez moyens adjacents (Maj + E): Si certains égards ou nœuds sont sélectionnés,
sélectionne moyens adjacents (non récursive).

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image33.png)

C. Sélectionnez toutes les manières connectés (Ctrl-Shift-E): Si certains égards ou nœuds sont
est sélectionné, sélectionne moyens adjacents de manière récursive (à la suite, tous connectés
moyens sont sélectionnés).

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image51.png)

D. Sélectionnez façons d'intersection (I): Si certains égards, sont sélectionnés, ajoute-t-
intersection des moyens de sélection. Iseful avec des nœuds Ajouter des fonctions à
intersections.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image39.png)

E. Sélectionnez tous les moyens intersection (Ctrl + Maj + I): Si certains égards, sont
sélectionnée, sélectionne tous les moyens adjacente et coupant de manière récursive. utile
pour sélectionner des parties du bâtiment à se joindre.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image16.png)

### Relation Détails

Chaque objet dans une relation est étiqueté comme ayant un rôle et ces
rôles définir ce que chaque objet fait au sein d'une relation. Donc, dans ce
Par exemple, le polygone autour de l'extérieur du bâtiment serait proposée
le rôle externe pour indiquer que c'est à l'extérieur et l'intérieur
polygone (s) sont donnés à l'intérieur rôle indiquer qu'ils sont des trous
à l'intérieur du polygone.

A. Une façon plus complexe de multi-polygone Relations: Le multipolygone ci-dessus
contient un polygone de la limite extérieure de la construction et plus de deux
marquer les cours intérieures. Pour créer une relation de ces trois
polygones dont vous avez besoin pour:

1. Utilisez l'outil de sélection pour dessiner un cadre autour de ces trois polygones
     sélectionnez-les tous à la fois.
	 
2.  Click \<\<Presets\>\> \<\<Relations\>\> \<\<Multipolygon\>\>.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image56.png)

3.  Click “New relation”

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image35.png)

4.  You will then be presented with the relation properties window:

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image02.png)

Il ya une grande quantité de données présentées ici, mais la plupart d'entre elles peuvent être
     ignoré pour le moment. Les aspects importants de cette fenêtre sont les lignes tag
     sur le dessus.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image22.png)

5. Dans ces lignes tag sur le dessus, dans le tableau clé / valeur, ajoutez les balises pour
     la relation. Les moyens réels n'ont pas besoin d'être étiquetés à moins qu'il n'existe
     quelque chose d'unique à leur sujet, telles que les sources de données différentes.

6. Ensuite, vous devez définir les rôles au sein de votre relation, pour un
     multipolygone vous devez définir l'extérieur et les voies intérieures.
     Essentiellement, JOSM besoin de savoir quels sont les polygones de la couche externe et
     ceux qui sont les couches internes de manière à pouvoir déterminer la zone est
     l'multipolygone. Choisir les moyens qui sont les cours et les marquer
     que les deux ampoules et la ligne de construction avec le rôle externe:
	 
    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image44.png)

7. Cliquez sur "OK??" et la boîte se ferme. Vous verrez alors votre immeuble
     comme aa forme solide avec les polygones intérieurs représentés avec des lacunes. la
     données sous-jacentes de la relation dans cet exemple est visible sur OpenStreetMap:
    [http://www.openstreetmap.org/browse/relation/2435797](http://www.openstreetmap.org/browse/relation/2435797).
Le bâtiment est rendu par Mapnik comme sur cette image:

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image00.png)

[OSM Wiki: Relation:
MultiPolygon](http://wiki.openstreetmap.org/wiki/Relation:multipolygon#One_outer_and_one_inner_ring)

B. rivière relation: Cet exemple d'une rivière, vous devez créer l'extérieur
et des banques intérieures, ainsi que dans la zone s'étendant à l'intérieur. L'intérieur et
banques extérieures ont été établis puis connecté et identifié comme une relation. comme
vous pouvez voir ci-dessous il ya une seule façon qui est un élément externe, car
il est le seul polygone extérieur dessinée. Tous les autres polygones représentent intérieure
- soit les membres des branches de la rivière ou des trous dans le polygone.

Relation Gare routière: Contrairement interne et externe, les rôles que ceux-ci
membres jouent dans une relation sera avant, en arrière ou arrêter. Stop
correspond à l'endroit où il ya un arrêt de bus et avant / arrière correspondent
à la direction le bus passe le long de la route.
![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image48.png)

1.  Make sure that all of the ways in which the route runs along are
    appropriately tagged.  For example, highway=footway.

2.  Open the relation panel (Alt + R) and select New in the relation
    panel to create a new relation.  

3.  Enter in the proper tags in the new dialog box.  For this bus route,
    it is type=route and name=Route 5.

4.  Click OK.

5.  Select all of the highways or ways that the bus takes.    If you
    would only like to select certain parts of the way, then, sadly, you
    must divide the way into the section you would like to select.  This
    creates more work, but you can easily do it with the  \<\<Split Way\>\>
    tool.  Once some or all of the ways are selected, click \<\<Edit\>\> in
    the relation panel.  The relation editing dialog will pop up.  

6. Click Add selection in that dialog box to add those selected ways.  