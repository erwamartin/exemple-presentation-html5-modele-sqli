# Prérequis

* Python 2.x
* Asciidoc 8.x -> Fourni
* Dzslides -> Fourni

# Installation sous windows

##  Installation de python
* Lancer le .exe

## Installation de asciidoc

* dezipper le asciidoc.zip
*  Déclarer dans le PATH le chemin vers le répertoire ascidoc %ASCIIDOC_HOME%

## Installer dzslides
* copier le fichier dzslides.conf dans %USER_HOME%\.asciidoc\backends\dzslides
*  Déclarer dans le Path le chemin vers dzslides %DZSLIDES_HOME%. Ce chemin doit pointer sur un répertoire qui contient le répertoire dzslides ! (dans le répertoire courant)

## Génération du fichier

* lancer le asciidoc.bat fourni avec en paramètre le nom du fichier asciidoc à convertir.
* Lors de l'export, il faudra penser à copier le répertoire dzslides à côté de votre fichier html car ce dernier fait référence à un répertoire dzslides directement à côté du fichier html.