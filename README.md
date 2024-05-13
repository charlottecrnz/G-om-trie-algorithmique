## Géométrie algorithmique
## TP1 
Le but de ce TP était de créer en premier objet de genre 1 puis un objet de genre 2 sur Blender. 

### Installation

## TP2 

Le but de ce TP est de prendre en main la librairie CGAL afin de pouvoir réaliser certains calculs sur un maillage. Pour représenter un maillage, j'utilise ici une structure de surfaces polyédrales qui s’appuie sur une structure de données en demi-arêtes. Le sujet de ce TP se trouve [ici][sujet1].

- Calcul d'une première propriété locale :

[x] Calcul pour chaque face d'un maillage donné son périmètre
[x] Afficher cette liste de longueurs dans la sortie standard
[x] Stocker ces données dans une structure adaptée
- Sauver le maillage avec des couleurs :

[x] Ecrire une fonction qui prend en entrée un maillage, un ensemble de valeurs scalaires, ainsi qu'un nom de fichier, et qui sauve le maillage au format OFF, en transformant les valeurs scalaires en couleurs pour chaque facette

- Implémenter d'autres mesures locales :

[x] Implémenter quelques mesures locales

- Segmenter un maillage par seuillage :

[x] Créer une fonction qui prend une map de mesure et calcule une map de segmentation qui à chaque face associe une étiquette en fonction d’un seuil
[x] Créer une fonction qui sauvegarde un maillage coloré mettant en évidence les faces étiquetées. Chaque étiquette doit avoir une couleur distincte

- Résoudre un problème par une segmentation :

[ ] Vous disposez d’un maillage simplifié de votre nouvel appartement tout neuf, que vous souhaitez décorer. Vous souhaitez connaître les emplacements où installer des meubles et des décorations murales, selon les contraintes suivantes : on ne peut déposer des meubles que sur une surface relativement plane et orientée vers le haut. On ne peut accrocher un tableau que sur une surface relativement plane et orthogonale au sol. Il serait intéressant de connaître les emplacements où peuvent tenir des décorations de différents gabarits
 
Le compte-rendu de ce TP se trouve [ici][cr1].


[sujet1]: ./sujet3.pdf
[cr1]: ./cr3.pdf
