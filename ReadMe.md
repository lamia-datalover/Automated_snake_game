# To my english lovers : 

My project aims to develop a standard SNAKE game (playable using keyboard arrow keys) as well as an intelligent version using the A star (A*) algorithm. This algorithm enables the snake to find the quickest path to the fruit it needs to eat without touching obstacles. The path found is not necessarily predetermined.

Through this application, players can select their desired game mode. They can choose to play against the computer using keyboard keys, play with a friend using keyboard keys, or select the intelligent option where the snake autonomously chooses its own path.

My task involves creating graphical user interfaces (GUI) and developing the game in two modes: the standard option (playing using keyboard keys) and the intelligent option, which involves implementing the theoretical algorithm into a programming language.

You can check the visual aspect of the application by looking at the pictures below, where you will find the menu of the game, the option mono player, the option bi-player, and finally the automated one with the A* algorithm that is used in pathfinding!

Here is how the algorithm works!

![image](https://github.com/lamia-datalover/Automated_snake_game/assets/145395677/7afe6f10-d9c1-48e9-9760-01fd6c7e57e7)

If you understand French, I recommend you read what is written down. If you are still learning it or do not know this language, do not hesitate to reach out to me using lamiachekkaba.data@gmail.com !

# Le but de ce projet : 
Dans le cadre de la préparation du diplôme universitaire technique, je suis censée effectuer un Stage de fin d’étude pour faire un rapprochement entre la théorie enseignée au sein de l’école et la pratique.
Mon projet  a pour but le développement d’un jeu SNAKE normal (possibilité de le jouer en utilisant les touches de directions du clavier) et intelligent en utilisant l’algorithme A star (A*) pour que le serpent puisse trouver le chemin vers le fruit qui doit manger d’une façon rapide sans toucher les obstacles, le chemin trouvé n’est pas forcé-ment.
A travers cette application, il est possible au joueur de sélectionner le mode de jeu souhaité (si l’utilisateur veut jouer contre le PC en utilisant les touches du clavier, jouer avec un ami en utilisant les touches du clavier aussi ou choisir l’option intelligente qui permet de regarder le serpent choisir son propre chemin).
Mon travail consiste donc à créer des interfaces graphiques (GUI) et de développer le jeu option normale (c’est-à-dire jouer en utilisant les touches du clavier) et en option intelligente qui est la traduction de l’algorithme théorique en language de programmation.

# Les outils utilisés:

![tab](https://github.com/lamia-datalover/Automated_snake_game/assets/145395677/3a0dbdfa-cbcd-4e06-85e5-cb5c8100ce54)

# Parlons UML :
L’image ci-dessous représente le diagramme d’état du joueur qui choisit l’option normal c’est-à-dire qu’il joue contre le PC ou contre un ami de son choix en utilisant les touches directionnelles du clavier dans les deux cas (contre le PC et jouer contre une personne). Cette image représente le déroulement global du jeu en suivant ses différents états du début à la fin de cette option.
![image](https://github.com/lamia-datalover/Automated_snake_game/assets/145395677/b0ae8f51-4230-44ae-afcb-1984a42d32bd)

L’image ci-dessous représente le diagramme d’état de l’option AI c’est-à-dire que le serpent est intelligent est choisi son chemin tout seul pour arriver au fruit sans toucher les obstacles. Cette image représente le déroulement global du jeu en suivant ses différents états du début à la fin de cette option.

![image](https://github.com/lamia-datalover/Automated_snake_game/assets/145395677/da5d294f-f2c7-4d8c-841b-e81ff6335fb9)

# Parlons interfaces :

#### Interface de bienvenue :

Dans cette interface on a une image à fond noir avec le logo du jeu au milieu. En haut on trouve un GIF compo-sé de 4 ronds colorés et dynamique qui donnent un aspect non-statique à l’interface sans oublier le décompteur de 5 s qui se trouve en bas au milieu ; dès que le chiffre atteint est 0 il mène l’utilisateur vers le menu du jeu. Il y’a aussi une musique en arrière-plan lors de l’utilisation de cette interface.

![image](https://github.com/lamia-datalover/Automated_snake_game/assets/145395677/eec9d5fa-e64d-4315-8e39-839542b7a387)

#### Menu du jeu:

Dans cette interface on trouve un GIF à fond gris en haut au milieu pour donner un aspect dynamique à l’interface. Au milieu on a les modes de jeu présentés dans l’image ci-dessous .

![image](https://github.com/lamia-datalover/Automated_snake_game/assets/145395677/e552f6e8-1247-4f51-8a18-1ce48d3660c6)

#### Interface du jeu automatisé avec A* :

Cette interface nous montre le serpent qui choisit tout seul son chemin en utilisant A STAR. Le carré bleu est la tete du serpent les carres blanches sont sa queue qui grandit au fur et à mesure de manger le fruit vert qui change d’endroit à chaque fois. Les carres rouges sont les obstacles à éviter.
L’image ci-dessous montre cela :

![image](https://github.com/lamia-datalover/Automated_snake_game/assets/145395677/c661ff19-97cb-4e29-a958-dc755f06580d)

#### Interface du jeu en mode mono player :

![image](https://github.com/lamia-datalover/Automated_snake_game/assets/145395677/83569265-2d1e-4f19-96a2-8a67d4a2bca0)

#### Interface du jeu en mode bi-player :

Cette interface permet à l’utilisateur de jouer contre un ami . Le carré rouge est le fuit à manger, le carré  bleu représente le joueur 1 et un autre carré rouge représente le joueur 2 .
On fait la différence entre les carrés rouges par le fait que celui du joueur bouge toujours contrairement au fruit qui change de position lorsqu’il est mangé par un des deux serpents.

![image](https://github.com/lamia-datalover/Automated_snake_game/assets/145395677/d95eedac-8b02-41a8-bad3-334b9f9a33f6)

#### Menu final :

Dans ce menu on peut revenir au premier menu ou sortir du jeu on peut voir le score obtenu.
Une fenêtre de confirmation de quitter le jeu sort dès qu’on appuie sur le bouton exit.

![image](https://github.com/lamia-datalover/Automated_snake_game/assets/145395677/d43c05cc-dc09-4fa8-8864-725484e46e6b)

![image](https://github.com/lamia-datalover/Automated_snake_game/assets/145395677/221de90d-d6a1-4f1a-9d91-ee2aba9e51df)

# Parlons algorithme A* :

Le « PATHFINDING » est un domaine de l'informatique qui étudie les différentes façons de trouver un chemin entre un point A et un point B. 
 L'un des algorithmes de pathfinding les plus connus est A* (A étoile, ou A star en anglais).
#### Qu’est-ce-que A* ???
 A star a été proposé pour la première fois par Peter E. Hart, Nils Nilsson et Bertram Ra-phael en 1968.C’sst un algorithme itératif qui permet la recherche d’un chemin à partir d’un état Initial (source) vers un état final (destination).
PS : Il ne donne pas toujours la solution optimale mais il donne très rapidement une bonne solution. Contrairement à celui de DIJKSTRA qui donne la solution avec le moindre coût. Mais il n’est pas aussi rapide que A*.
# Où trouvons-nous A* ??
On le trouve dans plusieurs domaines :
  	Déplacement réaliste d’un personnage contrôlé par le joueur vers un objectif désigné par le joueur. 
  	Simulation / vie artificielle :  Etude du comportement d’une foule, du trafic automobile
   Effets spéciaux (scènes de bataille, …) .
# Vocabulaires nécessaire à savoir:
  Le graphe: ensemble des nœuds et des arcs. 
  Un nœud: c'est une unité du graphe, l'algorithme va parcourir le graphe en passant des nœuds. 
  La liste ouverte: C'est une liste qui contient les nœuds à analyser. 
  La liste fermée: C'est une liste qui contient les nœuds déjà analysés.
  Pour chaque nœuds on a les propriétés suivante : 
  Parent (P): il s'agit du prédécesseur du nœud courant. 
  G: il s'agit de la distance parcourue depuis le point de départ pour arriver au nœud courant (Coût depuis la source). 
  H: il s'agit de la distance à vol d'oiseau entre le nœud courant et le nœud d'arrivée (Coût vers la destination). 
  Poids(F): Coût depuis la source (G) + Coût vers la destination (H) 

# Algorithme de A*:

![image](https://github.com/lamia-datalover/Automated_snake_game/assets/145395677/be0a5171-c32c-4f5a-aca4-6d03eb612853)

 
# Ce projet a été réalisé en collaboration constante avec M. Benazzi et M. Bouchentouf, deux professeurs universitaires au sein de l'Université Mohammed Premier à Oujda, au Maroc.                              

