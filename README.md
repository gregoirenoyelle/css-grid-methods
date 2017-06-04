# Grilles Colo : Exo 1

## Détail de l'exercice:

* Partir de la branche: grille_color_base
* Le bloc `.white` prend toute la largeur sur la troisième ligne. Il prend deux lignes de hauteur.
* Le bloc `.black` est au milieu. Il prends 4 lignes de hauteur.
* J'isole le bloc vert avec `#99CC00` pour le placer sur 2 colonnes, tout à droite.

## Notes pour le bloc vert

* Je trouve le bloc facilement dans l'inspecteur en créant une déclaration CSS avec le sélecteur `section:nth-child(2)`.
* J'ajoute un contour visible sur ce bloc.
* En utilisant les flèches du clavier, j'incrémente le child pour trouver la bonne boîte
* Ajout de `grid-auto-flow: dense`, pour combler le vide.
