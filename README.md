# Hexabot

Ceci est un template de dépôt Git pour le cours d'ingénierie système et modélisation robotique de l'UV 5.8 à l'ENSTA Bretagne en 2020.


## Lancer la simulation

### Dépendences

ros-melodic-effort-controllers  # contrôleur  
cv2                             # traitement d'image  
numpy                           # calcul  
matplotlib                      # affichage simple  
scikit-image                    # traitement d'image  

### Démarrer la simulation

```bash
roslaunch phantomx_gazebo phantomx_gazebo.launch
```
Lancer gazebo avec la demo walker.py

Pour lancer l'exploration de la grotte

```bash
roslaunch phantomx_mapping exploration.launch
```

## Groupe

### Membres

Yann Musellec  
Corentin JEGAT  
Alexandre Courjaud  
Matthieu Bouveron  
Philibert ADAM  
Driss Tayebi  

### Gestion de projet

https://tree.taiga.io/project/erysme-hexapode_nom_groupe/

## Structure du dépôt

### Workspace ROS

Le dossier `workspaceRos` est la racine du workspace `catkin` pour les packages ROS. Ces derniers doivent être placés sous `workspaceRos/src`.    
Consulter le [README](workspaceRos/README.md) du workspace pour plus d'informations.


### Documents

Le dossier `docs` contient tous les documents utiles au projet:
- Des [instructions pour utiliser Git](docs/GitWorkflow.md)
- Un [Mémo pour ROS et Gazebo](docs/MemoROS.pdf)


### Rapports

Le dossier `reports` doit être rempli avec les rapports d'[objectifs](reports/GoalsTemplate.md) et de [rétrospectives](reports/DebriefTemplate.md) en suivant les deux templates mis à disposition. Ces deux rapports doivent être rédigés respectivement au début et à la fin de chaque sprint.
