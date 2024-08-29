# MarsVolcanDetection

Le jeu de données mars est composé d’images de mars (cf. figures 1 et 2). Le but est de détecter sur les images la présence de volcans. 
Pour cela, des descripteurs ont été calculés en utilisant premièrement un filtre médian puis la méthode de HOG. Les images les plus bruitées ont été supprimées, mais certaines conservent un peu de bruit.

On a deux fichiers avec les données telles que les attributs sont en colonnes et les individus en ligne. Ces deux fichiers n’ont pas les mêmes individus. Le fichier mars train.csv doit être utilisé pour l’entraînement
d’un modèle de classification. Il contient sur sa dernière colonne les classes recherchées : 1 pour l’absence de volcan, 2 pour la présence d’un ou plusieurs volcans. Le fichier mars unknown.csv est le fichier d’évaluation où il y a pas les classes.

Le but est de trouver le modèle qui permettra la meilleure classification.
