# Morpion

Jeu <a href="https://fr.wikipedia.org/wiki/Tic-tac-toe">Morpion </a>(ou Tic Tac Toe), pour deux joueurs, codé en Ruby.
Ce jeu, connu également sous le nom de "Tic-Tac-Toe", est un <a href="https://fr.wikipedia.org/wiki/Jeu">jeu</a> de réflexion se pratiquant à deux joueurs au tour par tour dont le but est de créer le premier un alignement. Le jeu se joue généralement avec papier et crayon. 
Source: <a href="https://fr.wikipedia.org/wiki/Wikip%C3%A9dia:Accueil_principal">Wikipédia</a>.

## Instructions ##

### Installation du jeu ###

Ouvrez votre Terminal et déplacez-vous dans le dossier où vous souhaitez installer le jeu.
Entrez les commandes suivantes :
```
git clone https://github.com/Ridkuruma/morpion.git
cd morpion
bundle install
```

### Lancement du jeu ###
```
ruby game.rb
```
### Règles du jeu ###

Deux joueurs s'affrontent : player 1 et player 2.
Ils doivent remplir tour à tour une case de la grille avec le symbole qui leur est attribué : <b>O</b> ou <b>X</b>.
Le gagnant est celui qui arrive à aligner trois symboles identiques, horizontalement, verticalement ou en diagonale.
En raison du nombre de combinaisons limité, l'analyse complète du jeu est facile à réaliser : si les deux joueurs jouent chacun de manière optimale, la partie doit toujours se terminer par un match nul.
En cas de match de match nul relancer la commande ruby game.rb

Have Fun !

Fait par Joanne Rabenarisoa & Ridwan Baboolall
