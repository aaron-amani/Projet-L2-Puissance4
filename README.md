# Projet Puissance 4++

**Puissance 4++** est une version améliorée du jeu classique *Puissance 4*, développée en langage C. Le jeu permet de jouer dans différents modes, y compris des parties contre un adversaire humain, une IA, ainsi que des jeux à plusieurs joueurs avec des règles variées.

## Fonctionnalités


Le projet propose plusieurs modes de jeu :

- **Mode 1 vs 1 (Normal)** : Deux joueurs s'affrontent sur un plateau de jeu classique, l'objectif étant d'aligner 4 pièces de manière horizontale, verticale ou diagonale.
- **Mode 1 vs IA** : Un joueur humain affronte une IA pour tenter de gagner.
- **Mode 2 vs 2 (Multijoueur)** : Quatre joueurs s'affrontent en équipes de deux. Chaque équipe peut choisir un mode de jeu particulier parmi les options suivantes :
  - **Pièces Pleines** : Les joueurs placent des pièces classiques.
  - **Pièces Creuses** : Les pièces sont vides au centre et ne sont activées que lorsqu'elles sont empilées.
  - **Pièces Bloquantes** : Certaines pièces bloquent les mouvements de l'adversaire pendant quelques tours.

L'objectif du jeu reste le même : alignez 4 pièces en ligne, en colonne ou en diagonale avant votre adversaire.

## Membres du projet

- Aaron Amani
- Oussama Belkadi
- Fatih Ufacık
- Paul Riga

## Installation

### Prérequis
- Un compilateur C (par exemple GCC)
- Un terminal pour exécuter le jeu

### Compilation 
## --- A refaire ---
Clonez ce dépôt et compilez les fichiers source en utilisant la commande suivante :

```bash
gcc -o puissance4 main.c
```

### Exécution
## --- A refaire ---
Pour jouer au jeu, lancez le programme compilé :

```bash
./puissance4
```

Le jeu démarrera et vous pourrez choisir le mode de jeu souhaité.

## Structure du projet

Le projet se compose des fichiers suivants :

## --- A refaire ---
- **main.c** : Point d'entrée du programme et gestion de l'interaction avec l'utilisateur.
- **jeu.c / jeu.h** : Logique du jeu, gestion du plateau, des règles et des conditions de victoire.
- **ia.c / ia.h** : Algorithmes de l'IA, permettant de jouer contre l'ordinateur.
- **mode_multijoueur.c / mode_multijoueur.h** : Gestion des différents modes de jeu pour 2v2.
- **utils.c / utils.h** : Fonctions utilitaires pour la gestion du plateau et de l'affichage.

## Aide & Commandes

Pendant le jeu, vous serez invité à entrer vos actions à l'aide de commandes simples comme :

- **Joueur 1** : Choisissez une colonne pour placer votre pièce.
- **Joueur 2 (ou IA)** : L'IA ou le deuxième joueur choisit également une colonne pour jouer.
- **Mode 2v2** : Sélectionnez votre équipe et le type de pièces à utiliser (pleines, creuses ou bloquantes).

## Remarques

- L'IA utilise un algorithme de recherche de mouvement basé sur des heuristiques simples. Le mode "1vsIA" peut donc être plus ou moins difficile selon votre niveau.
- Le mode multijoueur ajoute une dimension stratégique intéressante avec la possibilité de jouer en équipe.

## Contributions

Si vous souhaitez contribuer au projet, n'hésitez pas à proposer des améliorations ou des idées de nouvelles fonctionnalités ! Les contributions sont les bienvenues via des pull requests.
