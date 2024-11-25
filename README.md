# Traffic-simulation-avec-Python
Ce projet simule un système de trafic routier réaliste en utilisant les modèles IDM (Intelligent Driver Model) et IIDM (Improved Intelligent Driver Model) pour modéliser le comportement des conducteurs.  Il inclut également une gestion simplifiée des feux de circulation pour simuler les interactions entre véhicules et intersections.

# Fonctionnalités principales :
## *Simulation des routes et intersections : 
Modélisation de routes, intersections et générateurs de trafic
## *Comportement des véhicules : 
Utilisation des modèles IDM/IIDM pour ajuster dynamiquement la vitesse et la distance de sécurité des véhicules.
## *Gestion des feux de circulation :
Implémentation de cycles fixes pour simuler des feux à une intersection.
## *Extensibilité : 
Le système peut être amélioré pour inclure des feux de circulation dynamiques ou des mesures de densité de trafic.

# Structure du Projet :
### main.py :
Script principal pour lancer la simulation.
### simulation.py :
Contient les classes principales (Route, Cross, Vehicle) et la logique de simulation.
### constants.py :
Définit les constantes globales, les couleurs, et les exceptions utilisées dans le projet pour uniformiser la configuration et gérer les erreurs.
### functions.py : 
Contient des fonctions utilitaires pour calculs mathématiques comme les angles.
### map_creator.py : 
Est un programme interactif basé sur Tkinter, qui permet de manipuler une carte en y ajoutant des éléments comme des croisements, des générateurs et des routes.
### gui.py : 
Gère l'interface graphique de la simulation de trafic avec TKINTER. Il permet d'afficher une carte interactive, de dessiner des éléments comme des routes et véhicules, et de contrôler la simulation via des boutons pour jouer, mettre en pause et ajuster la vitesse .
### run_simulation.bat :
Fichier batch pour exécuter facilement la simulation.
### README.md :
Documentation complète du projet.


