## Mini-Projet VBA : LE JEU TOUCHE-COULE

# Introduction

* C’est quoi ce jeu ?

Battleship (également Battleships ou Sea Battle) est un jeu de devinettes de type stratégie pour deux joueurs. Il se joue sur des grilles réglées (papier ou carton) sur lesquelles la flotte de navires de chaque joueur (y compris les cuirassés) est marquée. Les emplacements des flottes sont cachés à l'autre joueur. Les joueurs alternent leurs tours en appelant des « coups » sur les navires de l'autre joueur, et l'objectif du jeu est de détruire la flotte du joueur adverse.
Battleship est connu dans le monde entier comme un jeu de crayon et de papier datant de la Première Guerre mondiale. Le jeu a engendré des versions électroniques, des jeux vidéo, des applications pour appareils intelligents et un film.

* Comprendre les règles du jeu 

Après avoir cherché sur Wikipédia voici les règles que nous avons synthétisées. Le jeu se joue sur quatre grilles, deux pour chaque joueur. Les grilles sont généralement carrées - généralement 10 × 10 - et les carrés individuels de la grille sont identifiés par une lettre et un chiffre.  Sur une grille, le joueur organise les navires et enregistre les tirs de l'adversaire. Sur l'autre grille, le joueur enregistre ses propres coups.
Avant le début du jeu, chaque joueur arrange secrètement ses vaisseaux sur sa grille principale. Chaque navire occupe un certain nombre de carrés consécutifs sur la grille, disposés horizontalement ou verticalement. Le nombre de carrés pour chaque navire est déterminé par le type de navire. Les navires ne peuvent pas se chevaucher (c'est-à-dire qu'un seul navire peut occuper une case donnée de la grille). Les types et le nombre de navires autorisés sont les mêmes pour chaque joueur. Celles-ci peuvent varier en fonction des règles.

Une fois les navires positionnés, le jeu se déroule en une série de tours. À chaque tour, chaque joueur annonce à son tour une case cible dans la grille de l'adversaire qui doit être tirée. L'adversaire annonce si la case est occupée ou non par un navire. S'il s'agit d'un « hit », le joueur qui est touché le marque seul ou sur la grille « océan » (avec une cheville rouge dans la version à panneau perforé). Le joueur attaquant marque la touche ou échec sur sa propre grille de « suivi » ou de « cible » avec une marque au crayon dans la version papier du jeu, ou la cheville de couleur appropriée dans la version avec panneau perforé (rouge pour « coup », blanc pour « miss "), afin de construire une image de la flotte de l'adversaire.
Lorsque toutes les cases d'un navire ont été touchées, le propriétaire du navire annonce le naufrage du transporteur, du sous-marin, du croiseur / destructeur / patrouilleur ou du cuirassé titulaire. Si tous les navires d'un joueur ont été coulés, la partie est terminée et son adversaire gagne. Si tous les navires des deux joueurs sont coulés à la fin du tour, le jeu est nul. 

# Guide d’utilisation 

Quand on lance le fichier Excel , un Window est monté 

![1](https://user-images.githubusercontent.com/69216854/107957196-8adb2400-6fa0-11eb-81eb-357203b8fdc6.png)

On clique sur commencer pour commencer à jouer
On clique sur Quitter pour quitter le jour
Après , on est dirigé ver la feuille de joueur 1 pour faire le setup des bateau dans la carte

![2](https://user-images.githubusercontent.com/69216854/107957282-ae9e6a00-6fa0-11eb-985e-41563f4cac76.png)

Double-Cliquer sur le sur le nom de bateau pour le placer

![3](https://user-images.githubusercontent.com/69216854/107957368-cd9cfc00-6fa0-11eb-8830-d77357a01ab8.png)

Cliquer sur Yes et on dirige ver le Window comme celui-ci , clque sur non si vous changez l’idée

![4](https://user-images.githubusercontent.com/69216854/107957429-e4dbe980-6fa0-11eb-9563-04cfaaa62a08.png)

Après avoir cliqué Ok , on selecte sur la carte pour placer le bateau

![5](https://user-images.githubusercontent.com/69216854/107957449-ed342480-6fa0-11eb-97fe-6416d1aa1ab9.png)

Quand finir, on clique sur OK pour continuer avec le joueur 2 

![6](https://user-images.githubusercontent.com/69216854/107957535-0a68f300-6fa1-11eb-9174-3e240a1e824d.png)

Cliquer sur Reset si vous voulez relancer tous les placements des bateaux
Après , on est dirigé ver la feuille Combat , le joueur 1 commencer par choisir une carré et cliquer tirer pour tirer au carré correspondante de joueur 2

![7](https://user-images.githubusercontent.com/69216854/107957605-2076b380-6fa1-11eb-8c71-818db958e25f.png)

Et toujours faire attention à votre tour

![8](https://user-images.githubusercontent.com/69216854/107957673-371d0a80-6fa1-11eb-9e30-e791dabc58b8.png)

Si c’est votre tour , cliquez sur Abadonner si vous voulez abadonner

![9](https://user-images.githubusercontent.com/69216854/107957677-38e6ce00-6fa1-11eb-85ba-8cc979975799.png)

Quand tous les bateaux d’un joueur sont coulé ou un joueur clique abadonner , un Window va monter le joueur gagnant , vous pouvez cliquer sur Recommencer pour recommencer un nouveau match 
