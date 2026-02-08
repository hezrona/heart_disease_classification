# Classification des Maladies Cardiaques 🫀

Ce projet utilise l'apprentissage automatique (Machine Learning) pour prédire la présence d'une maladie cardiaque chez un patient en fonction de ses paramètres médicaux.


## 📋 Paramètres attendus (Features)

Pour obtenir une prédiction, le modèle attend les **13 paramètres** suivants dans cet ordre précis :

1.  **age** : Âge en années
2.  **sex** : Sexe (1 = homme; 0 = femme)
3.  **cp** : Type de douleur thoracique (0 à 3)
4.  **trestbps** : Pression artérielle au repos
5.  **chol** : Cholestérol sérique en mg/dl
6.  **fbs** : Glycémie à jeun > 120 mg/dl (1 = vrai; 0 = faux)
7.  **restecg** : Résultats électrocardiographiques au repos
8.  **thalach** : Fréquence cardiaque maximale atteinte
9.  **exang** : Angine induite par l'exercice (1 = oui; 0 = non)
10. **oldpeak** : Dépression du segment ST induite par l'exercice
11. **slope** : Pente du segment ST au sommet de l'exercice
12. **ca** : Nombre de vaisseaux majeurs (0-3) colorés par fluoroscopie
13. **thal** : 1 = normal; 2 = défaut fixé; 3 = défaut réversible

## 🚀 Comment l'utiliser

1. **Exécuter les cellules** : Suivez le code pour charger les bibliothèques (`pandas`, `numpy`, `sklearn`) et entraîner le modèle.
2. **Prédire** : Utilisez la fonction `model.predict()` avec un tableau NumPy contenant les 13 paramètres listés plus haut.

## 🛠️ Bibliothèques utilisées
* Scikit-Learn (Modèles : Logistic Regression, KNN, Random Forest)
* Pandas & NumPy (Manipulation de données)
* Matplotlib & Seaborn (Visualisation)
