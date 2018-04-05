# LaLibrairie

Nouvelles, romans, exercices, brouillons et autres vagabondages

## Mode d'emploi

### Front matter

* prv: chemin relatif de l'élément précédent pour la navigation (et éventuel scripting plus tard)
* nxt: chemin relatif de l'élément suivant pour la navigation (et éventuel scripting plus tard)

### Catégories

* Vagabondages : textes en vracs *(valeur par défaut dans le répertoire idoine)*
* Brouillons : ben, un truc pas fini, à retravailler, ... Peuvent être rangés dans n'importe quel répertoire
* Romans : On ne sait jamais, si jamais j'arrive à me structurer et avancer, avec la notion de projet pour distinguer mes différentes tentatives ? *(valeur par défaut dans le répertoire idoine)*
* Nouvelles : Des textes publiés d'un bloc *(valeur par défaut dans le répertoire idoine)*
* Exercices : Des "réponses" à des exercices d'écriture. Les "projets" marquant ici les sources d'exercices. *(valeur par défaut dans le répertoire idoine)*

### Layout

* default : par défaut pour les postes, base des autres layout.
* collection : pour afficher les résultats d'une collection - par défaut pour les pages du répertoire "collections".

## Reste à faire

* gestion des projets en sous répertoires

* Index avec la structure suivante:
  * texte d'introduction
  * tag cloud/liste :
    * opt: avec le nombre d'entrées dans chaque

* Rework collection layout avec la structure suivante:
  * Titre
  * Liste des projets
  * Entrées dans chaque projet
  * Trier par "ordre logique" dans chaque projet ? (ajout d'un front matter nécessaire ? Jeu avec la date?)

* Création d'une page projet avec la structure suivante:
  * Titre
  * Mot d'introduction sur le projet ("préface")
  * Liste des posts concernés dans l'ordre logique

* Menu dans le layout par défaut sous forme de texte d'introduction à la place du texte d'introduction

* CSS : Réduire le bandeau du haut en cas de scroll mais le garder en permanence ?

* Rework CSS (couleur de lien, pas d'emphase qui marche)