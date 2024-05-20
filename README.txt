Projet CDataframe de Arthur Dequesne et Luc Labarbe

Description :
Le projet CDataframe est une librairie de fonctions en langage C ayant pour but de reprendre quelques fonctionnalités de la librairie "DataFrame" dans Pandas en Python

Utilisation :
	Le projet est essentiellement constitué de fichiers librairies et d'un fichier main.c qui contient un jeu de test pour tester les librairies.

Fonctionnalités :
	Les fonctionnalités sont le résultat obtenu de l'exécution des fonctions de la librairie
	Note : Voir les fichiers d'en-tête (.h) pour consulter les fonctions et la documentation de leur utilisation en commentaire
	Fichiers :
		Le projet contient les 12 fichiers suivants :

		- column.h     :
			Contient les déclarations de toutes les fonctions necessaires pour la manipulation des colonnes dont les lignes sont toutes de même type (avec plusieurs types existant)
			Nous avons :
			- la création de colonne
			- l'insertion d'une valeur dans une colonne
			- supprimer une colonne
			- supprimer une valeur dans une colonne
			- convertir une valeur de n'importe quel type en chaine de caractères
			- afficher une valeur d'une colonne
			- afficher une colonne entière
			- afficher partiellement une colonne
			- compter le nombre de d’occurrences d’une valeur x
			- retourner la valeur présente à la position x
			- compter le nombre de valeurs qui sont supérieures à x
			- compter le nombre de valeurs qui sont inférieures à x
			- compter le nombre de valeurs qui sont égales à x

		- column.c     :
			Contient les définitions de toutes les fonctions de column.h

		- sort.h       :
			Contient les déclarations de toutes les fonctions utilisées pour les tri
			Nous avons :
			- le tri rapide
			- le tri par insertion
			- la comparaison de deux valeurs
			- fonctions de gestion des index des colonnes

		- sort.c       :
			Contient les définitions de toutes les fonctions de sort.h

		- cdataframe.h  :
			Contient les déclarations de toutes les fonctions utilisées pour la gestion du CDataframe
			Nous avons :
			- le remplissage d'un CDataframe par les entrées de l'utilisateur
			- le remplissage d'un CDataframe en dur dans le code
			- l'affichage complet d'un CDataframe
			- l'affichage partiel d'un CDataframe
			- l'affichage d'une valeur du CDataframe
			- la détermination du type d'une colonne à l'aide de son indice dans la CDataframe
			- l'ajout d'une ligne dans la CDataframe
			- la suppression d'une ligne dans la CDataframe
			- l'ajout d'une colonne
			- la suppression d'une colonne
			- renommer une colonne
			- vérifier si une valeur se trouve dans la CDataframe
			- remplacer une valeur dans la CDataframe
			- afficher le nom d'une colonne
			- afficher le nom de toutes les colonnes
			- compter le nombre de colonnes
			- compter le nombre de lignes
			- compter le nombre de valeurs qui sont supérieures à x
			- compter le nombre de valeurs qui sont inférieures à x
			- compter le nombre de valeurs qui sont égales à x
			- supprimer une CDataframe
			- remplir une CDataframe à partir d'un fichier CSV
			- enregistrer une CDataframe dans un fichier

		- cdatafram.c  :
			Contient les définitions de toutes les fonctions de cdataframe.h

		- main.c       :
			Contient un jeu de test qui peux être complété en faisant appel aux fonctions de la librairie

		- Makefile     :
			Contient les commandes necessaire pour compiler tout le projet en prenant en compte tous les fichiers d'en-tête et sources

		- input.csv    :
			Fichier test d'entrée

		- output.csv   :
			Fichier test de sortie

		- list.h       :
			Contient les déclarations de toutes les fonctions necessaires à la gestion des listes doublement chainées

		- list.c       :
			Contient les définitions de toutes les fonctions de list.h
