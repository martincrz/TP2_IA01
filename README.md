# TP2_IA01

## Description 

Le but de ce TP est de trouver différentes manières de faire gagner une IA au jeu de Nim. 
Pour rappel, le jeu de Nim est un jeu de pure stratégie. Il se joue avec un tas d’allumettes, chaque joueur peut retirer au maximum 3 allumettes par tour. Le joueur qui prend la dernière allumette a perdu. Le jeu de Nim est ainsi équivalent à se déplacer d’un sommet à un autre dans un arbre : les sommets représentent les diverses positions du jeu et les arêtes les transitions d’une position à une autre. Il montrera qu’il existe une stratégie optimale.

Ce TP est divisé en 2 parties, chacune ayant un objectif différent.

Le but de la première partie est d’étudier la fonction proposée et de déterminer quel type de recherche elle effectue pour la résolution du jeu de Nim. Nous allons également déterminer quelle recherche (en profondeur ou en largeur) semble la plus adaptée pour ce jeu et voir s’il est possible d’améliorer la fonction proposée. 
Pour la deuxième partie, le but est de programmer une IA capable d’améliorer sa stratégie au fur et à mesure de jeux successifs. Pour ceci, dès qu’un coup mènera à la victoire de l’IA, il sera ajouté à une base de données contenant les coups que l’IA peut jouer à partir d’un certain état. Ce système est propagé à tous les coups qui ont mené à la victoire. Ainsi, au prochain lancement du jeu, les probabilités que l’IA tombe sur un coup qui mène à la victoire seront augmentées. Ceci permettra de faire émerger des stratégies gagnantes.

## Collaboration

Avec Alexandre Labouré
