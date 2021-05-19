# TIPE


Bonjour
Je vous présente ici mon travail de TIPE de l'année 2020-2021. Celui ci a été fait dans le langage python, et a pour objectif la création et l'exploration de labyrinthes.


L'objectif est ici de s'intzresser à la mise en place de la génération de labyrinthes parfaits (1 et 1 seul chemin entre 2 couples de cases) ainsi qu'à leur résolution, et enfin à l'implémentation d'une interface graphique nécessaire à leur représentation.

La génération du labyrinthe est faite à l'aide d'une adaptation de l'algorithme de Kruskal (qui permet à l'origine de trouver un arbre couvrant de poids minimum). On a  notamment utilisé la structure UNIOND-FIND pour générer notre labyrinthe. 
La résolution se fait à l'aide d'un parcours en profondeur, plus efficace que l'algorithme de Dijkstra à cause de la contrainte de perfection.


La convention des couleurs est la suivante : 
Blanche -> Case Vide
Dorée -> Case avec un rover
Noire -> Objectif du Rover

Pour faire fonctionner les différents algorithmes, compiler le code ouvrira une fenêtre Tkinter, qui comporte une grille dont les bordures foncées sont les murs du labyrinthe.
Ensuite, cliquer plusieurs fois sur une case fera alterner la couleur, donc le contenu de la case.

Une fois 1 rover et 1 objectif placés, appuyer d'abord sur "matrice des chemins" (pour trouver le chemin) puis sur "aller à l'objectif" pour déclencher l'animation graphique qui amène le rover à l'objectif.


Normalement, ce travail de TIPE comporte une deuxième partie concernant la résolution avec plusieurs rovers et 1 objectif, mais je n'ai pas fini l'implémentation en python avant la date de rendu des dossiers.

