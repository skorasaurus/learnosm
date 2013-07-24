---
layout: doc
title: Editing with JOSM
permalink: /fr/beginner/editing-with-josm
lang: fr
category: beginner
---

# Editer en d�tail

## Introduction

Dans ce chapitre, nous allons d�crire les relations, les outils d'�dition JOSM, et les techniques d'�dition plus en d�tail.

> Bien que ce chapitre ne soit pas tr�s avanc�, il est plus difficile
> que les chapitres pr�c�dents. Si vous sentez que vous n'avez pas bien compris 
> les le�ons pr�c�dentes, vous pouvez vous pratiquer un peu plus 
> avant de continuer.

Les sujets abord�s dans ce chapitre:

- Outils d'�dition: Outils, le plugin de construction, et les raccourcis

- Relations: Description et comment modifier et ajouter des attributs

- Techniques d'�dition: Les **Fait** et **Ne fait pas**

## Outils d'�dition JOSM

Il y a quelques fa�ons d'acc�der � des outils d'�dition suppl�mentaires dans JOSM. Nous allons
examiner de plus pr�s les outils par d�faut, certains greffons, puis les raccourcis clavier d'�dition.

### Outils de dessin

JOSM a des outils suppl�mentaires pour faciliter le tracage des lignes et des formes. Ces outils se trouvent dans le menu "Outils" au haut de JOSM.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image12.png)

Afin d'appliquer les fonctions de ce menu, vous devez d'abord s�lectionner un
point, une ligne ou une forme dans la fen�tre Carte. Quelques unes des fonctions les plus utiles sont d�crites ci-dessous:

1. Couper un chemin: Cela vous permet de diviser une ligne en deux lignes distinctes.
     Ceci est utile si vous souhaitez ajouter des attributs diff�rents pour diff�rents sections d'une route, comme un pont. Pour utiliser cette fonction, s�lectionnez un
     point au milieu de la ligne que vous voulez partager, S�lectionnez **Couper le chemin** dans le menu Outils, et votre ligne sera scind�e en deux.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image38.png)

2. Fusionner les chemins: Ceci fait le contraire de la fonction Couper un chemin. Pour combiner deux 
     lignes en une seule, elles doivent partager un seul point. Pour utiliser
     cette fonction, s�lectionnez les deux lignes que vous souhaitez combiner. Vous pouvez
     s�lectionner plus d'un objet en maintenant la touche MAJ de votre
     clavier et en cliquant sur chaque ligne. Lorsque vous avez s�lectionn� les deux
     lignes, s�lectionnez **Fusionner les chemins** dans le menu Outils.
	 
    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image28.png)

    > Si vous tentez de fusionner des routes qui ont des directions diff�rentes,
    > le message d'avertissement suivant s'affichera:

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image15.png)

    Si les routes sont connect�es et vont dans la m�me direction, choisissez alors
    \<\<Reverse and Continue\>\>.

3.  Inverser le chemin: Cela va changer la direction de la ligne. Si la ligne ne repr�sente pas correctement une rivi�re ou une route � sens unique, vous voudrez sans doute changer sa direction. A moins que quelqu'un aie d�lib�r�ment cr�� un chemin avec attribut sens unique, vous n'avez g�n�ralement pas � vous soucier de modifier
     l'instruction parce que les chemins dans OSM peuvent par d�faut aller dans dans les deux sens.
     ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image26.png)

4.  Simplifiez le chemin: Si votre ligne a trop de points et que vous souhaitez la simplifier, cela va enlever quelques-uns des points de la ligne.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image41.png)

5.  Cr�er un cercle OU aligner les n�uds en cercle: Si vous essayez de faire une forme circulaire, dessiner le cercle du mieux que vous pouvez, puis s�lectionnez
     trois noeuds et la fonction. Elle aidera � organiser vos points dans un     cercle.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image04.png)

6.  Aligner les n�uds sur une ligne: Cette fonction permettra d'aligner une s�rie de points
     dans une ligne droite. Avec de longues lignes, il est pr�f�rable de s�lectionner les sections
     de la ligne � redresser. Soyez prudent car cela ne le
     tendance � d�placer la ligne un peu.
	 ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image17.png)

7.  Rendre une forme Orthogonale: Cette fonction est tr�s utile pour dessiner des
     formes r�guli�res comme les b�timents. Apr�s avoir dessin� une zone, cette
     fonction permet de la remodeler pour avoir des coins carr�s. Cette fonction est
     plus utile pour d'autres fonctions de forme r�guli�re, comme les tennis,
     tribunaux ou les zones d'utilisation du sol. (L'utilisation du greffon b�timent, qui sera
     expliqu� ci-dessous, peut �tre plus facile).

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image45.png)

8.  D�coller un chemin: Cet outil vous permet de d�tacher les n�uds qui sont
     connect�es.
	 
    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image59.png)

    > La ligne et le noeud n'appara�tront pas effectivement s�par� comme la derni�re  Capture d'�cran l'implique.

### Greffons

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image25.png)

A.  Greffon Immeubles: Ce greffon est de loin l'un des plus utiles parmi les outils d'�dition (num�risation). Cet outil vous permet de cr�er des formes
avec des angles � 90 degr�s avec seulement trois clics. Tout d'abord, vous tracez le
bord de votre b�timent, puis vous faites glisser sur la ligne d'en faire un
polygone.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image58.png)![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image19.png)

Vous pouvez �galement cr�er des b�timents plus complexes � l'aide de l'option de fusion.
 Cr�ez votre plan de construction, s�lectionnez tous les polygones (appuyez sur MAJ pour tous les mettre en �vidence) et ensuite MAJ + J pour fusionner les objets.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image03.png)

En outre, vous pouvez modifier les param�tres par d�faut (taille et attributs) � partir du menu
\<\<Edit\>\>. Vous s�lectionnez ensuite au bas du panneau �D�finir la dimension de l'immeuble�.  

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image07.png)

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image11.png)

Si vous traitez une s�rie d'immeubles de dimension similaire, vous pouvez modifier la taille des immeubles pour une certaine dimension, soit par exemple 5 x 6 m�tres (l'unit� est en m�tres).  Encore plus, si vous cartographiez des infrastructures similaires, telles que des bungalows dans une m�me zone, vous pouver �diter les attributs pour �tre tous identiques � partir de l'onglet  \<\<Advanced\>\>.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image13.png)![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image64.png)

B. Utilsplugin2 (Plus d'outils):  Ce greffon a quelques fonctionnalit�s qui peuvent �tre utiles pour �diter.  

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image47.png)

Apr�s l'installation du grefffon et le red�marrage de JOSM, l'onglet suivant sera ajout� :  \<\<More Tools\>\>:

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image24.png)

Ces outils se sont r�v�l�s �tre les plus utiles:

1. Ajout de n�uds aux intersections: Cet outil est tr�s utile pour ajouter
     des n�uds manquants aux intersections de voies s�lectionn�es. Il est une bonne
     pratique que les routes et les rivi�res aient toujours des n�uds communs � leur intersection.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image43.png)

2. Copiez les attributs de la s�lection pr�c�dente: Cette fonction facilite la copie des attributs. Si vous voulez cr�er plusieurs objets avec les m�mes attributs,
     dessinez d'abord les objets. Puis ajoutez les attributs � un objet. Cliquez ensuite sur un autre objet et appuyez sur Maj + R pour copier les balises de l'objet pr�c�demment s�lectionn�. Vous pouvez le r�p�ter pour tous les objets que
     que vous souhaitez marquer. Rappelez-vous que les attributs seront copi�s � partir de l'objet s�lectionn� pr�c�demment. Donc, si vous cliquez sur un objet sans attribut
     puis ensuite un autre objet sans attribut, vous ne serez pas en mesure de copier des attributs.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image05.png)

3. Ajouter un Attribut Source: Cet outil simplifie l'ajout d'un Attribut Source. Il
     se souvient de la source qui a �t� sp�cifi�e en dernier et il ajoute cet attribut source � vos objets. Vous pouvez ins�rer la source 
	 avec un seul clic.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image63.png)

4. Remplacer la G�om�trie: Cet outil est id�al si vous voulez redessiner un objet mal dessin� tout en conservant l'historique, les attributs le ID de l'objet. Par exemple, si vous apercevez un immeuble
     qui est compliqu� et mal dessin�, alors au lieu de l'op�ration p�nible de modifier chaque n�ud, vous pouvez (2) juste dessiner � nouveau l'objet
     (3) S�lectionnez l'objet ancien et le nouveau (4) appuyez sur �Remplacer la g�om�trie� pour transf�rer tous les informations sur le nouvel objet.

C. Utilsplugin2 (S�lection):

Et vous avez acc�s � davantage de \<\<Selection\>\>
tool:![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image55.png)

Ces outils se sont r�v�l�s �tre les plus utiles:

1. D�s�lectionner les n�uds: Cet outil vous permet de d�s�lectionner les n�uds, ce qui rend
     utile pour le marquage des objets s�lectionn�s. Cet outil est n�cessaire si
     vous avez mapp� plusieurs objets polygonaux avec des attributs similaires et
     tenez � modifier les attributs des objets sans ajouter ces attributs aux n�uds. Pour ce faire,
     s�lectionnez tous les objets - des polygones, des chemins et des relations - d�-s�lectionnez
     les n�uds et ajoutez ensuite les attributs de mani�re appropri�e.
	 ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image50.png)

2. S�lectionnez les derniers n�uds modifi�s: Cet outil vous permet de revenir aux
     n�uds qui vous avez r�cemment chang�. C'est comme une op�ration Annuler: style de n�ud.
     

Amusez-vous � les utiliser!

## Relations

Dans le Guide du d�butant, nous avons appris qu'il y a trois types d'objets
qui peuvent �tre dessin�s dans OpenStreetMap - des points (n�uds), des lignes (voies), et
des polygones. Les Lignes contiennent de nombreux points, et la ligne elle-m�me porte
les attributs qui d�finissent ce ces noeuds repr�sentent. Les Polygones sont similaires aux
lignes, � l'exception que la ligne est trac�e de fa�on � ce qu'elle se termine l� ou elle a commenc�, afin de
former une forme.

En fait, il y a un autre type d'objet dans OpenStreetMap, et celui-ci est appel� relation. De la m�me mani�re qu'une ligne comprend une s�rie de points, une relation contient un groupe d'autres objets, qu'il s'agisse de points,
lignes ou des polygones. Si vous voulez d�velopper des comp�tences d'�dition avanc�e, il est important de comprendre les relations et de savoir les �diter.

Par exemple, imaginez que vous souhaitez dessiner un b�timent qui a des cours, jardins dans le centre. Vous auriez besoin de dessiner un polygone � l'ext�rieur du
l'immeuble, et indiquer que les polygones autour des cours ne font pas partie de l'�difice. Ceci est un exemple o� s'applique une relation. La relation devrait contenir plusieurs polygones - et les attributs de l'immeuble �tres fix�s � la relation et non � chaque polygone.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image42.png)

Les relations sont utilis�es pour repr�senter quoi que ce soit qui n�cessite de d�finir une collection d'objets. D'autres relations peuvent �tre d�finies par exemple pour des lignes de bus (une collections de lignes), des objets longs et complexes (rivi�res ou routes), ou des polygones multiples qui font tous partie du m�me endroit (comme les b�timents d'une universit�).

Il existe principalement quatre types de relations que vous rencontrerez dans OSM:
Multipolygones, Routes, Fronti�res, et restrictions (telles que, pas de virage � gauche). Dans cette section, nous allons passer en revue les multipolygones et Routes.

A. �diter les Relations: Le multipolygone ci-dessus contient un polygone pour les
limites ext�rieures du b�timent et deux autres pour marquer les cours int�rieures.
Pour cr�er une relation avec ces trois polygones, vous devez:

1. S�lectionnez tous les polygones.

2. Aller � �Outils� et pr�s du bas �multi-polygone�
    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image49.png)

3. Les polygones doivent automatiquement �tre cr�� en tant que multi-polygone.

     ! [] ({{}} site.baseurl / images/intermediate/en_edit_in_detail_image14.png)

Vous verrez alors votre b�timent repr�sent� avec une surface solide et les polygones int�rieurs repr�sent�s avec des vides. Les donn�es sous-jacentes de la relation dans cet
exemple sont visibles sur OpenStreetMap:[http://www.openstreetmap.org/browse/relation/2435797](http://www.openstreetmap.org/browse/relation/2435797).
Le b�timent est rendu par Mapnik comme sur cette image:

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image00.png)

[OSM Wiki: Relation:
MultiPolygon](http://wiki.openstreetmap.org/wiki/FR:Relation:multipolygon#Un_anneau_externe_et_un_anneau_interne)

B. Une autre MultiPolygon

Cette rivi�re est un autre exemple de multipolygone. En effet, il est similaire � l'exemple d'immeuble, mais avec un plus grand nombre de membres et
couvrant une superficie beaucoup plus grande. Il peut �tre consult� sur le site OpenStreetMap
ici:
[http://www.openstreetmap.org/browse/relation/1046961](http://www.openstreetmap.org/browse/relation/1046961.).

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image61.png)![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image23.png)

Cette rivi�re contient dix lignes qui sont connect�es comme un long polygone.

C. Relations de Lignes

Les relations sont �galement tr�s utiles pour la cr�ation, l'�tiquetage et l'�dition de longues lignes, par exemple, des lignes de bus, des sentiers p�destres, des pistes cyclables, etc.
  Elles se distinguent des multipolygones parce qu'elles sont les relations avec des
membres, contrairement aux multipolygones complexes. Une relation de lignes pourrait simplement �tre une
ligne avec plusieurs membres, ceux-ci �tant int�gr�s dans la relation comme tels. Des
caract�ristiques suppl�mentaires, comme les arr�ts de bus repr�sent�s par des n�uds distincts peuvent �galement �tre int�gr�s en tant que membres de la relation.
![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image27.png)![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image37.png)

1. Assurez-vous que tous les chemins par lesquels la route passe ont les bons attributs. Par exemple, highway= footway.

2. S�lectionnez toutes les routes ou chemins que prend le bus. Si vous
     voulez seulement s�lectionner certaines parties du chemin, l�, malheureusement, vous
     devrez diviser le chemin dans la section que vous souhaitez s�lectionner. Cela
     cr�e plus de travail, mais vous pouvez facilement le faire avec l'outil �Couper le chemin�. Une fois que tous ou une partie des chemins sont s�lectionn�s, cliquez sur Modifier dans le panneau d'�dition de Relation. La bo�te de dialogue d'�dition de Relation appara�tra.

3. Allez dans le menu Attributs et
	s�lectionnez successivement dans le menu d�roulant : Transport, puis Transport Public, puis Public transport route ou Itin�raire maitre. L'Itin�raire maitre est l'itin�raire principal, tandis que la route est une variante de l'itin�raire du bus.
    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image54.png)

4. Remplissez les informations correspondantes relativement � la ligne de bus.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image60.png)

Les relations sont parfois difficiles � comprendre et n'ont pas n�cessairement � �tre utilis�es souvent. Il est cependant important de les connaitre.  � mesure que vous d�veloppez vos comp�tences avec OSM et voulez cr�er des objets plus complexes (ie. immeubles, rivi�res et routes), les relations seront utiles.

## Techniques d'�dition�: Les Faire et ne pas faire

Dans cette section, nous couvrirons quelques erreurs communes dans JOSM et fournirons quelques trucs d'�dition pour rendre votre travail dans JOSM plus efficient !

A. Certains objets ne doivent pas �tre connect�s

Lorsque vous cr�ez des polygones et des lignes qui ne sont pas cens�s �tre
connect�, assurez-vous qu'ils ne sont pas fusionn�s ensemble en partageant un
n�ud. Par exemple, les n�uds routiers ne doivent pas �tre accroch�s aux b�timents,
parce que personne n'aime une route qui m�ne directement dans un mur! Si vous
voulez d�m�ler deux ou plusieurs objets qui partagent le m�me n�ud, s�lectionnez
le n�ud, puis appuyez sur \<\<G\>\>.  

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image32.png)  ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image62.png)

Mais, certains objets doivent se connecter

Toutefois, certains objets doivent toujours se connecter! Les Intersections de routes devraient
toujours �tre connect�es. Si deux routes ne partagent pas un noeud commun, alors l'ordinateur n'a aucun moyen de savoir que les routes se connectent une � l'autre.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image20.png)

B. Chevauchement des objets

Une erreur courante est de superposer des polygones lorsque les objets qu'ils
repr�sentent ne se chevauchent pas dans la vraie vie. Un b�timent ne peut pas chevaucher
un autre b�timent. Cette erreur est souvent faite avec des b�timents et les polygones
LANDUSE. Par exemple, un polygone dessin� pour repr�senter un parc
� l'ext�rieur d'un b�timent ne doit pas se chevaucher avec le b�timent. Au contraire, il
doit �tre align� � c�t� du b�timent.

Il y a quelques exceptions � cette r�gle, comme les �coles. Dans une
cour d'�cole, vous pourriez identifier les b�timents individuels en utilisant des polygones.
Vous pourriez �galement vouloir cr�er un polygone autour de la cour de l'�cole tout enti�re.
  Dans ce cas, il est acceptable que les polygones se chevauchent, mais la r�gle �
suivre ici est de s'assurer que les b�timents sont compl�tement � l'int�rieur du
polygone LANDUSE.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image46.png)  ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image18.png)

Nous faisons tous des erreurs, et que vous mappez plus vous ferez moins d'erreurs!
  N'oubliez pas que m�me si vous t�l�chargez de donn�es qui contient des erreurs, il
est simple � corriger vos erreurs et t�l�charger le nouveau changement. c'est
ce qui est formidable � propos OSM: vous pouvez toujours faire mieux!

C. Recherche correctement

OSM peut faire des choses �tonnantes avec identifiant si fin et objets
ce qui qualifie ces objets devraient avoir, mais il a besoin de votre aide
faire. Par exemple, si vous cr�ez une route qui se transforme en une autre
route sans un n�ud distinct, puis JOSM continuera d'�tiquetage de la route
comme la pr�c�dente. Par cons�quent, il est n�cessaire que vous fassiez tous
vos routes et des objets de fa�on claire et rigide que possible.

^[[a]](#cmnt1)^

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image57.png)

Nous terminerons ce chapitre avec ce cadeau:

- Faire pivoter un objet: Si vous maintenez la touche MAJ + CTRL enfonc�e et faites glisser votre souris
     clic, vous pouvez faire pivoter les objets s�lectionn�s.  

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image31.png)


## R�sum�

Comme vous pouvez le voir, il ya de nombreuses fonctionnalit�s suppl�mentaires qui rendent un JOSM
outil puissant pour faire des cartes. Rappelez-vous que plus vous pratiquez avec
ces outils, le meilleur vous deviendrez � ajouter des informations �
OpenStreetMap.

## Annexe 

### Raccourcis clavier

Parfois, il peut �tre g�nant de cliquer � plusieurs reprises pour s�lectionner diff�rents
options et les menus dans JOSM. Heureusement, il ya des touches de raccourci sur le
clavier qui vous permettent de faire de nombreuses t�ches courantes (je recommande fortement l'
DEL raccourci). Voici une liste de quelques-uns des plus couramment utilis�s
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
 

A. S�lection des noeuds adjacents (e): S�lectionne les voisins de d�j� s�lectionn�
n�uds. Se souvient des moyens actifs lorsqu'ils sont utilis�s en premier et les remplit avant
de passer � d'autres moyens. Si certains �gards, sont d�j� s�lectionn�s, nous n'utilisons que des
les faire avancer la s�lection. Si seuls moyens sont s�lectionn�s, les n�uds sont
s�lectionn� � la place.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image52.png)

Exemple d'utilisation: s�lectionnez un n�ud (et �ventuellement son chemin), appuyez sur E (3
n�uds sont � pr�sent s�lectionn�s), appuyez sur L pour mettre le n�ud sur la ligne droite.

B. S�lectionnez moyens adjacents (Maj + E): Si certains �gards ou n�uds sont s�lectionn�s,
s�lectionne moyens adjacents (non r�cursive).

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image33.png)

C. S�lectionnez toutes les mani�res connect�s (Ctrl-Shift-E): Si certains �gards ou n�uds sont
est s�lectionn�, s�lectionne moyens adjacents de mani�re r�cursive (� la suite, tous connect�s
moyens sont s�lectionn�s).

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image51.png)

D. S�lectionnez fa�ons d'intersection (I): Si certains �gards, sont s�lectionn�s, ajoute-t-
intersection des moyens de s�lection. Iseful avec des n�uds Ajouter des fonctions �
intersections.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image39.png)

E. S�lectionnez tous les moyens intersection (Ctrl + Maj + I): Si certains �gards, sont
s�lectionn�e, s�lectionne tous les moyens adjacente et coupant de mani�re r�cursive. utile
pour s�lectionner des parties du b�timent � se joindre.

![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image16.png)

### Relation D�tails

Chaque objet dans une relation est �tiquet� comme ayant un r�le et ces
r�les d�finir ce que chaque objet fait au sein d'une relation. Donc, dans ce
Par exemple, le polygone autour de l'ext�rieur du b�timent serait propos�e
le r�le externe pour indiquer que c'est � l'ext�rieur et l'int�rieur
polygone (s) sont donn�s � l'int�rieur r�le indiquer qu'ils sont des trous
� l'int�rieur du polygone.

A. Une fa�on plus complexe de multi-polygone Relations: Le multipolygone ci-dessus
contient un polygone de la limite ext�rieure de la construction et plus de deux
marquer les cours int�rieures. Pour cr�er une relation de ces trois
polygones dont vous avez besoin pour:

1. Utilisez l'outil de s�lection pour dessiner un cadre autour de ces trois polygones
     s�lectionnez-les tous � la fois.
	 
2.  Click \<\<Presets\>\> \<\<Relations\>\> \<\<Multipolygon\>\>.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image56.png)

3.  Click �New relation�

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image35.png)

4.  You will then be presented with the relation properties window:

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image02.png)

Il ya une grande quantit� de donn�es pr�sent�es ici, mais la plupart d'entre elles peuvent �tre
     ignor� pour le moment. Les aspects importants de cette fen�tre sont les lignes tag
     sur le dessus.

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image22.png)

5. Dans ces lignes tag sur le dessus, dans le tableau cl� / valeur, ajoutez les balises pour
     la relation. Les moyens r�els n'ont pas besoin d'�tre �tiquet�s � moins qu'il n'existe
     quelque chose d'unique � leur sujet, telles que les sources de donn�es diff�rentes.

6. Ensuite, vous devez d�finir les r�les au sein de votre relation, pour un
     multipolygone vous devez d�finir l'ext�rieur et les voies int�rieures.
     Essentiellement, JOSM besoin de savoir quels sont les polygones de la couche externe et
     ceux qui sont les couches internes de mani�re � pouvoir d�terminer la zone est
     l'multipolygone. Choisir les moyens qui sont les cours et les marquer
     que les deux ampoules et la ligne de construction avec le r�le externe:
	 
    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image44.png)

7. Cliquez sur "OK??" et la bo�te se ferme. Vous verrez alors votre immeuble
     comme aa forme solide avec les polygones int�rieurs repr�sent�s avec des lacunes. la
     donn�es sous-jacentes de la relation dans cet exemple est visible sur OpenStreetMap:
    [http://www.openstreetmap.org/browse/relation/2435797](http://www.openstreetmap.org/browse/relation/2435797).
Le b�timent est rendu par Mapnik comme sur cette image:

    ![]({{site.baseurl}}/images/intermediate/en_edit_in_detail_image00.png)

[OSM Wiki: Relation:
MultiPolygon](http://wiki.openstreetmap.org/wiki/Relation:multipolygon#One_outer_and_one_inner_ring)

B. rivi�re relation: Cet exemple d'une rivi�re, vous devez cr�er l'ext�rieur
et des banques int�rieures, ainsi que dans la zone s'�tendant � l'int�rieur. L'int�rieur et
banques ext�rieures ont �t� �tablis puis connect� et identifi� comme une relation. comme
vous pouvez voir ci-dessous il ya une seule fa�on qui est un �l�ment externe, car
il est le seul polygone ext�rieur dessin�e. Tous les autres polygones repr�sentent int�rieure
- soit les membres des branches de la rivi�re ou des trous dans le polygone.

Relation Gare routi�re: Contrairement interne et externe, les r�les que ceux-ci
membres jouent dans une relation sera avant, en arri�re ou arr�ter. Stop
correspond � l'endroit o� il ya un arr�t de bus et avant / arri�re correspondent
� la direction le bus passe le long de la route.
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