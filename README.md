# Machine Learning (ML)

Ce dossier contient le code derrière deux projets utilisant le machine learning (apprentissage profond) pour exploiter les données existantes dans les modèles numériques de bâtiments.

## Classification des locaux d'un projet de bureaux

L'objectif de ce travail est de créer un modèle d'apprentissage profond capable de prédire le type de local en fonction du nom de celui-ci. Le résultat permet de faire des estimations et calculs en première intention. Le réseau neuronal utilisé a trois couches : deux composées de cellules LSTM (Long-Short Term Memory) capables de garder en 'mémoire' les valeurs qui leur sont passées, et un couche de sortie. Tenserflow et Sci-Kit Learn ont étés choisis pour l'abondance de ressources disponibles. Pandas est employé pour la manipulation des données et leur nettoyage.

![live-demo-3](https://github.com/jonathanatger/ml/assets/50679537/881f7a04-dc90-4cf8-ab76-de640760c3c9)



## Predictions des données de chauffage, ventilation et climatisation pour les locaux d'un hopital

Ce modèle utilise un modèle de "Forêt d'arbres décisionnels", modèle simple et éprouvé pour des base de données de taille réduite.
