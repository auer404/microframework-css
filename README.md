# microframework-css

Ce framework ne s'occupe que d'une chose : mettre en place un système de colonnes automatiques pour accueillir du contenu.


-- Utilisation des classes --

• microframework.css utilise principalement 3 classes : "container" , "row" et "column". Celles-ci peuvent être données à plus ou moins n'importe quel type d'élément HTML.

• Seule règle à respecter : une colonne ("column") doit se trouver dans une rangée ("row"), qui doit se trouver dans un conteneur ("container").

• Un conteneur peut accueillir plusieurs rangées, une rangée peut accueillir plusieurs colonnes. 

• Dans une rangée, les colonnes se répartiront équitablement l'espace.


-- Seuils de largeur --

• Au-dessus de 1200px de largeur fenêtre, un conteneur conservera une largeur de 1200px et se centrera horizontalement. En-dessous, il occupera la pleine largeur de la fenêtre.

• Sous 800px de largeur de fenêtre, toute la mise en page basculera sur une seule colonne.


-- Gestion des gouttières --

• La mesure des gouttières est basée sur la taille de police donnée à l'élément "html".

• Dans un conteneur auquel on ajoute la classe "no-v-gap", les rangées ne seront pas espacées verticalement.

• Dans une rangée à laquelle on ajoute la classe "no-h-gap", les colonnes ne seront pas espacées horizontalement.

• Dans un conteneur auquel on ajoute la classe "no-h-gap", les colonnes ne seront pas espacées horizontalement.

• Un conteneur auquel on ajoute la classe "no-top-gap" ne sera pas espacé verticalement par rapport à l'élément qui le précède.
