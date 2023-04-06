Prédiction et classification du risque de maladie cardiaque à l’aide de divers algorithmes ML et comparaison de leur précision.
L’objectif principal de ce projet est la prédiction des maladies cardiaques a l’aide de différents algorithmes de classification tels que la régression logistique, K-plus proches voisins (KNN), la machine a vecteur du support (SVM), l’algorithme bayésien naïf, les arbres de décisions et les algorithmes de classificateur de forets aléatoires. Les mesures d’évaluation utilise est la matrice de confusion et le score de validation croisée k-fold.
1.	Importer les bibliothèques nécessaires
2.	Importer un ensemble de données. 
3.	Visualisation des données à l’aide de la distribution d’histogrammes, courbes et graphes a barres. Utilisation de cartes thermiques pour déterminer la corrélation des différentes fonctionnalités entre elles
4.	Prétraitement des données : Dummy variable trap pour l’élimination des caractéristiques insignifiantes de l’ensemble de données, fractionnement de l’ensemble de données en ensembles d’apprentissage et test, mise à l’échelle des caractéristiques
5.	Les modèles d’apprentissage automatique utilisés pour la prédiction des risques et la classification des maladies cardiaques sont les suivants :
•	XGB Classifier
•	Random Forest Classifier
•	Logistic Regression
•	LGBM Classifier
•	SGD Classifier
•	SVC
•	K Neighbors Classifier
6.	Evaluation des performances et de la précision des différents modèles ML utilisés. Les paramètres d’évaluation comprennent :
	Matrice de confusion
	Courbe de Roc
7.	Tracer un graphe a barres pour la comparaison des différentes précisions de test obtenues en utilisant les différents algorithmes de classification ML.	
8.	Résultats : Précisions de test obtenues sur les trois algorithmes les plus performants : 0.90 pour KNN, 0.88 pour LR et 0.85 pour RF
