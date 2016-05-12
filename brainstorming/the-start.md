# CUI - Application de coaching de cuisine

-

### MVP

Le Produit Minimal doit se composer de:

1. une liste de recettes
2. une liste des ingredients (pour chaque recette)
2. un player de recette (avec fonctions de _rewind_, _play_  _pause_ et _forward_) 

----

### 1/ Idées :  

Recette en temps réel avec des étapes en vectoriel :

-Possibilité de mettre en pause (GRATUIT)

- Possibilité de mettre en tache de fond (pour la cuisson par exemple) avec une alarme (GRATUIT)

Création du compte :

-Chaque utilisateur doit avoir un compte gratuit ou payant pour accéder au service 

Pour une recette choisie possibilité d’ajouter au panier les ingrédients nécessaires pour la liste de course :

-Possibilité de calculer le nombre d’ingrédient par rapport au nombre de personne (GRATUIT)

-Possibilité de modifier la liste de course manuellement (par exemple si on a déjà des tomates dans le frigo) (GRATUIT)

-Possibilité de supprimer les ingrédients quand on les a mis dans le cadi (GRATUIT)

Gagner de l’xp avec des entrainements de coaching proposés (exemple couper les ognions) :

-En temps réels avec des illustrations vectoriels (type svg)

-Avant chaque exercice illustrer celui-ci par une vidéo d’un professionnel  (PAYANT )

Type de recherche des recettes :
-Par ingrédient / pays / saison  / diététique / difficulté / mieux notés/mots
 Pour chaque recette proposée :

-Possibilité de noté la recette  (PAYANT)
-Calories affichés ((GRATUIT)
-Niveau de difficulté (GRATUIT)
-durée de préparation (GRATUIT)
-durée de cuisson (GRATUIT)
-recette variante associée (GRATUIT)
-lire commentaire (GRATUIT)
-editer commentaire  (PAYANT)
- lire les astuces ((GRATUIT)
- dévoiler ses astuces (PAYANT)
-possibilité de l’ajouter dans ses favoris ou carnet de recette (GRATUIT)

déroulement de chaque recette :

-avant de démarrer le coaching : 
	-Rappel des ingrédients necessaires (GRATUIT)
	-Rappel des outils necessaires (GRATUIT)

-A chaque étape de la recette

Possibilité de mettre en pause et de voir les  vidéos d’entrainement   nécessaire pour la recette (exemple couper les ognions, ébouillanté les tomates ect …) (GRATUIT)

-A la fin de la recette :

- Possibilité de prendre une photo (GRATUIT) et de la mettre dans son carnet (voir pour relier a l’appareil photo du telephone )
- Xp en plus, pour un certain nombre d’étoile aquis -> status de débutant, expert, pro (PAYANT) -> affiché sur les commentaires posté (donne de la crédibilité) 
- Avis et partage de l’internaute sur l’appli et réseaux sociaux (GRATUIT)
- Possibilité de proposé une variante de la recette (PAYANT)

 Proposition de SA recette :

Possibilité de soumettre sa propre recette sur le forum, si beaucoup de like, la recette rentre dans la base de données et devient proposée au internaute (PAYANT)
au bout de 5 recettes validées  service offert pour un an

Et si on pouvait cuisiner ensemble a distance ?
 
Possible avec orid et tablette, via la webcame, lancer la recette en meme temps avec les gens connectés sur l’appli


### 2/ Langages utilisés / OUTILS:  
HTML5 : pour structurer le contenu
CSS3 : pour styler le contenue
MongoDB  :  pour une base de données (recette, commentaire, ect …)
 JS
  Angular 
 
 

### 3/ DEVICE : 
web
mobile
tablette 
Faire du responsive plutôt que du distributed design  / progressive webapp

### 4/ HEBERGEMENT :

Au debut, locale ? Probleme pour setter le meme environnement sur differentes machines (et different SO -> OSX, WIN, UBUNTU)

#### One.com

One.com PRO : 100 GO, 2.22 euros HT par mois, 1 GO RAM, un seul domaine, 2 CPU, SSL, SSH
One.com affaires : 500 GO, 5.25 euros HT par mois, 4 GO RAM, un seul domaine, 8 CPU, SSL, SSH

#### OVH

OVH perso : 100 GO, nom de domaine offert, 2.99 euros HT par mois
OVH pro : 250 GO, nom de domaine offert, 5,99 euros HT par mois
OVH performance : 500 GO, nom de domaine offert, 9,99 euros HT par mois

OVH VPS SSD : <https://www.ovh.com/fr/vps/vps-ssd.xml>  à partir de 2,99 euros HT par mois

#### HOSTPAPA

HOSTPAPA NOVICE : 100 GO, 2.95euros par mois, bande passante illimitée

HOSTPAPA AFFAIRE : illimité, 2.95e/mois
 

### 5/ CONCEPTION ET PRODUCTION DES CONTENUS :

Textes (recettes, explications, liste)
Photos (prise par les internautes)
image vectoriel (svg)
vidéos (pro)


### 6/ COMMENT PARTAGER NOTRE CODE

* GITHUB -> cuiteam (Sanswell, gmorelli, maevaCha)
* GMAIL
* SLACK

### 7/ CONCURRENTS :

#### MARMITON : 
appli mobile + web
http://www.marmiton.org/
Proposition d’apprendre (vidéos) par niveau (débutant, moyen, presque pro)


Moteur de recherce : par mots, par tendance, par ingrédients
Sur mobile : liste de course (problème pas de calcul des ingrédients), possibilité de prendre en photo, technique culinaire en vidéo associé à chaque recette, historique des recettes, possibilité de commenter les recettes, sélection de recette pour les infants, cout des recettes, niveau de difficulté, votes, durée de préparation et cuisson


### 8/ NOS PLUS :

coaching en temps réels
possibilité de proposer ses propres recettes
niveau d xp 
possibilité de s’entrainer sur des techniques spécifiques
possibilité de démarrer une recette avec un internaute connecté (via webcame)
