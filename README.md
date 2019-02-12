# Workshop_processing_PCD2019
Code for the processing workshop @stereolux for the processing community days 2019

Processing est une plateforme logicielle libre et gratuite pour l’apprentissage de la programmation dans le contexte des arts graphiques, créée par Casey Reas et Ben Fry. Elle est complémentée par une version web appelée p5.js, crée par Lauren McCarthy. Aujourd’hui Processing et p5.js sont utilisés de part le monde par une communauté rassemblant artistes, programmeurs, éducateurs et étudiants.

L’un des objectifs de ce projet est de rendre l’apprentissage de la programmation et des œuvres créatives à base de code accessible à toute sorte de communauté, en particulier celle qui sont généralement tenues à l’écart de ces outils et autre ressources. Le premier Processing Community Day (PCD), organisé par Taeyoon Choi et la Fondation Processing en 2017 a été l’un de nos efforts pour améliorer la diversité au sein des communautés de programmeurs et d’artistes. Se déroulant dans les locaux du MIT MediaLab à Boston, PCD 2017 a réuni les membres de la communauté venant en particulier de la côte Est des Etats Unis, leur permettant de se rencontrer « dans la vrai vie », de partager leur travaux, d’apprendre et d’initier de nouvelles collaborations.

En savoir plus sur le PCD 2017 et l’histoire de Processing.
Pour PCD 2019, nous voudrions élargir l’audience et l’impact de cette communauté en s’organisant avec des centaines de Communauté Processing de part le monde. La Fondation Processing organisera le Processing Community Day de Los Angeles et invitera d’autres organisateurs à les rejoindre via d’autres événements et ateliers partout dans le monde.

Lien vers PCD @ worldwide [https://day.processing.org/pcd-ww.html](https://day.processing.org/pcd-ww.html)

## Un peu d'inspiration : 

  - [Documentation P5 js](https://p5js.org/)
  - [Colorhunt, un site de palettes de couleurs](https://colorhunt.co/)
  - [Site de daniel Shiffman](https://shiffman.net/)


## Premier sketch

### Les variables 
Processing nécessite de déclarer le type des variables. Selon le type, une variable pourra stocker différents types de valeurs et avoir une taille de stockage différente.

```java
-int // stocke des entiers
-float // stocke des réels 
-double //stocke également des réels, mais peut contenir plus de chiffres après la virgule
```
### Définir les constantes du sketch
Processing utilise une fonction **setup** qui s'exécute une seule fois au lancement du sketch, puis la fonction **draw** prend le relais et est exécutée en boucle jusqu'à l'arrêt du programme.
Il existe aussi des fonctions évènementielles qui s'exécutent de manière momentannée lorsqu'une action est effectuée par l'utilisateur, comme un clic de souris ou une pression d'une touche de clavier.

```java


void setup(){
size(800,800); // taille de la fenetre de dessin
background(0); //couleur du fond

void draw(){
// le code à executer en boucle
}

void mousePressed(){
// le code à exécuter lorsqu'un clic de souris est effectué
}

```

## SKETCH1:

-Ellipse
-fill/stroke
-placement(width, height)
-taille
-random
-float placement, comment passer a l'ellipse des variable.
-int taille, comment passer a l'ellipse des variable.
-keyPressed==true
-aller vers la version finale du PCD_sketch1_randomellipse


## SKETCH 2 :

-mouseX/mouseY
-opacité

## SKETCH 3 :

-for/push,pop
-map

## SKETCH FINAL :

