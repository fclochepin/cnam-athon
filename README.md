# CNAM athon Pronunciation
Michael Nauge, Université de Poitiers (2022)

*Formation aux **basic skills** du métier d'ingénieur DATA en Science Humaine au travers d'un hackathon de données linguistiques*


## Buts du cours

* Maitriser le web scrappping (requests et beautifulsoup)
* Créer, Croiser, régulariser, enrichir et filtrer des matrices de données (pandas)
* Découvrir la création de widgets interactifs (ipywidgets)
* Déployer une micro application web pour une utilisation côté client (git+myBinder)


## Problématique 

### Discussion autours de la macine à café

> Il me faut une moulinette pour croiser les données d'un dictionnaire de prononciation en langue anglaise de 1757 avec les enregistrements audios contemporains de Linguee ou Longman Dictionary ou Cambridge dictionary. Faudra aussi m'ajouter la transcription de la prononciation en Sampa et IPA pour que ça serve réellement à quelque chose.*A. Lovelace (chercheuse en SHS)* 


Si je comprends bien il faut :
* Utiliser un dictionnaire ancien
* Collecter des données variées dispersées dans des plateformes web
* Les re-structurer, les enrichir et les régulariser pour les croiser avec un vieux dictionnaire
* Créer différentes matrices dynamiquements facilitant l'interrogation

C'est ça ?

> Oui, je veux bien des graphiques interactifs aussi avec des widget sympas. Et que je puisse m'en servir depuis ma tablette quand je suis à la maison.

Euh, oui, on verra ce qu'on peut faire dans les temps. C'est pour quand ?

> Hier, évidemment. Mais j'ai eu exeptionnelement une extension de deadline de 7 jours pour soummettre mon article à une prestigieuse conférence internationale ;-)

Ah, parfait, on est large alors :-)


### Cahier des charges

1. Produire par programmation un enrichissement du dictionnaire de Buchanan 1757 en ajoutant
    1. une colonne motVedette (transformation/simplification de la prononciation d'origine)
    1. une colonne Sampa (transformation/croisement de données)

1. Disposer d'une UI permettant de filtrer les entrées du dictionnaire enrichi de Buchanan sur :
    1. la colonne motVedette (expression régulière)
    1. la colonne prononciation Sampa (expression régulière)
    1. une taille maximale d'échantillon résultat
    1. un bouton demandant la collecte/scrapping des fichiers audios (depuis des sources externes) des entrées isolées 

2. Afficher en résultat 
    1. un player pour chaque audio collecté
    1. le spectrogramme pour chaque audio collecté




## Projet à réaliser 

Avoir déployé une micro application web permettant le croisement entre les données d'un dictionnaire ancien et les prononciations contemporaines tels que décrit dans le cahier des charges.

Les projets réalisés doivent être déposées sous forme de dépôt GitHub. Le lien vers le dépôt Git à évaluer doit m'être transmis par mail pour le N/P/2022

Le dépôt Git de ce cours doit servir de modèle de structuration de données et codes. Le readme.md devra contenir un lien pour le lancement de l'application via myBinder (en mode notebook et en mode voilà).


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/git/https%3A%2F%2Fgitlab.huma-num.fr%2Fmnauge%2Fcnam-athon-pronunciation/HEAD)

https://mybinder.org/v2/git/https%3A%2F%2Fgitlab.huma-num.fr%2Fmnauge%2Fcnam-athon-pronunciation/HEAD?urlpath=voila%2Frender%2Fnotebook%2Fprenom_nom_App.ipynb











