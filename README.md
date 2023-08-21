# Classification eau

# Ce projet est une application de l'EDA et de l'apprentissage

Il traite 3 différents fichier CSV contenant des données sur la qualité de l'eau et a pour objectif de créer un modèle pouvant prédire la qualité de l'eau.

# Modèles utilisés

KNeighbors Classifier
SVM Classifier
Decision Tree Classifier 
Random Forest Classifier
XGB Classifier
MLP Classifier (Réseau de neurones)

Chaque modèle (sauf le réseau de neurones) a été utilisé deux fois de la manière suivante :
    - 1 fois sans hyperparamètres
    - 1 fois en changeant les hyperparamètres
L'objectif étant de comparer l'impact des hyperparamètres dans différents modèles.

# EDA

Lors de l'EDA, j'ai supprimé les valeurs objet autres que la classification (qui était la cible), et j'ai nettoyé et choisi les 10 colonnes les plus proches de la classification après traduction et encodage (avec LabelEncoder) via une matrice de corrélation.

# Résultat 

Les modèles les plus précis et qui devinent la mieux la bonne réponse sont : 

XGBClassifier
RandomForestClassifier
DecisionTreeClassifier