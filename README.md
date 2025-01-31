# Labyrinthe Game - Projet de Jeu de Casse-Tête en C++ avec Raylib

## Description du Projet

Ce projet consiste à développer un jeu de casse-tête de type labyrinthe en utilisant la programmation orientée objet (POO) en C++ et la bibliothèque graphique Raylib. Le jeu propose une expérience immersive où le joueur doit naviguer dans un labyrinthe généré aléatoirement à chaque nouvelle partie. Le jeu comprend trois niveaux de difficulté (facile, moyen, difficile) qui affectent la taille du labyrinthe et la complexité de la navigation.

## Fonctionnalités

### 1. Génération Automatique de Labyrinthes
- Génération procédurale de labyrinthes à chaque lancement du jeu.
- Respect des règles de connexité : chaque position doit être atteignable et une solution doit exister.

### 2. Trois Niveaux de Difficulté
- **Facile** : Petit labyrinthe avec peu de pièges ou d'obstacles.
- **Moyen** : Labyrinthe de taille moyenne avec des chemins plus complexes et des obstacles plus nombreux.
- **Difficile** : Grand labyrinthe avec de multiples chemins trompeurs et des obstacles complexes.

### 3. Interface Graphique avec Raylib
- Visualisation en 2D avec Raylib.
- Représentation des murs par des blocs et d'un personnage contrôlable par le joueur.
- Déplacement du joueur avec les touches de direction.

### 4. Mécanique de Jeu
- Le joueur commence à l’entrée du labyrinthe et doit atteindre la sortie.
- Chronomètre affichant le temps pris pour résoudre le labyrinthe.
- Possibilité de réinitialiser la partie à tout moment, générant ainsi un nouveau labyrinthe.

### 5. Système de Sauvegarde et de Scores (Optionnel)
- Enregistrement du temps du joueur à la fin de chaque partie.
- Affichage d'un tableau des meilleurs scores.

## Exigences Techniques

- **Langage** : C++
- **Bibliothèque Graphique** : Raylib (gestion de l'interface graphique 2D)
- **Modèle de Programmation** : Programmation orientée objet (POO)

## Classes Clés

### 1. Labyrinthe
- Représente la grille du labyrinthe et contient les méthodes de génération aléatoire.
- **Propriétés** : largeur, hauteur, tableau 2D de cases (murs ou passages).
- **Méthodes** : génération procédurale, vérification de solution, affichage.

### 2. Joueur
- Représente le personnage contrôlé par le joueur.
- **Propriétés** : position x, position y, mouvements.
- **Méthodes** : déplacement, interaction avec le labyrinthe.

### 3. Niveau
- Gestion des niveaux de difficulté (facile, moyen, difficile).
- **Méthodes** : sélection de la taille du labyrinthe et ajustement des obstacles en fonction du niveau.

### 4. Jeu
- Gestion de la boucle principale du jeu.
- **Propriétés** : état du jeu, chronomètre, interface utilisateur (menu, fin de partie).
- **Méthodes** : gestion des événements, démarrage et réinitialisation des parties.

## Défis Techniques

- Implémentation de l’algorithme de génération procédurale des labyrinthes (par exemple, avec l'algorithme de recherche en profondeur ou Prim).
- Gestion des collisions pour assurer que le joueur ne traverse pas les murs.
- S’assurer que chaque labyrinthe généré est résolvable.

## Résultats Attendus

À la fin de ce projet, le jeu devra être fonctionnel, avec une interface graphique intuitive, un gameplay fluide, et des labyrinthes de difficultés variables générés automatiquement. Le jeu doit être jouable sur différentes plateformes grâce à la portabilité de Raylib.

## Livrables

- Code source (organisé, commenté en FR ou ANG)
- Rapport détaillé

## Extensions Possibles (Optionnel)

- Ajout d'obstacles mobiles ou de pièges.
- Introduction de thèmes visuels différents selon les niveaux de difficulté.
- Multijoueur local avec un second joueur contrôlé par une autre touche ou un contrôleur.

## Comment Ajouter ce Projet sur GitHub

1. **Créer un Nouveau Dépôt sur GitHub** :
   - Allez sur [GitHub](https://github.com) et connectez-vous à votre compte.
   - Cliquez sur le bouton "New" pour créer un nouveau dépôt.
   - Donnez un nom à votre dépôt (par exemple, `Labyrinthe-Game`).
   - Choisissez entre un dépôt public ou privé.
   - Cliquez sur "Create repository".

2. **Initialiser un Dépôt Git Local** :
   - Ouvrez un terminal sur votre machine locale.
   - Naviguez jusqu'au dossier de votre projet.
   - Initialisez un dépôt Git avec la commande suivante :
     ```bash
     git init
     ```

3. **Ajouter les Fichiers au Dépôt Local** :
   - Ajoutez tous les fichiers de votre projet avec la commande :
     ```bash
     git add .
     ```
   - Faites un commit des fichiers ajoutés :
     ```bash
     git commit -m "Initial commit"
     ```

4. **Lier le Dépôt Local à GitHub** :
   - Copiez l'URL de votre dépôt GitHub (disponible sur la page du dépôt).
   - Ajoutez l'URL comme remote avec la commande :
     ```bash
     git remote add origin https://github.com/votre-utilisateur/Labyrinthe-Game.git
     ```

5. **Pousser les Fichiers sur GitHub** :
   - Poussez les fichiers sur GitHub avec la commande :
     ```bash
     git push -u origin master
     ```

6. **Vérifier sur GitHub** :
   - Allez sur la page de votre dépôt GitHub pour vérifier que tous les fichiers ont bien été poussés.

## Conclusion

Vous avez maintenant un projet de jeu de labyrinthe fonctionnel et hébergé sur GitHub. Vous pouvez continuer à développer de nouvelles fonctionnalités, corriger des bugs, et collaborer avec d'autres développeurs en utilisant les fonctionnalités de GitHub. Bon codage !
