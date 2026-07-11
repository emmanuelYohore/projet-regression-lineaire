# Projet de Régression Linéaire – Prédiction des prix de l'immobilier

## Description

Ce projet met en œuvre un modèle de **régression linéaire** afin de prédire le prix de vente de maisons à partir du jeu de données **Ames Housing**. Il illustre les principales étapes d'un projet de Machine Learning, depuis le chargement des données jusqu'à l'évaluation des performances du modèle.

Ce notebook s'inscrit dans un exercice pratique permettant d'appliquer les notions de :

* Feature Engineering
* Validation croisée (Cross Validation)
* Optimisation des hyperparamètres (Grid Search)
* Évaluation d'un modèle de régression

---

## Objectifs

* Charger et explorer le jeu de données Ames Housing.
* Préparer les données pour l'entraînement.
* Construire un modèle de régression linéaire.
* Optimiser les paramètres du modèle avec **GridSearchCV**.
* Évaluer les performances sur un jeu de test.
* Interpréter les résultats obtenus.

---

## Technologies utilisées

* Python 3
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## Jeu de données

Le notebook utilise le jeu de données **AMES Housing**, contenant des caractéristiques détaillées de logements ainsi que leur prix de vente.

Le fichier est chargé directement depuis un dépôt GitHub afin de faciliter l'exécution du notebook.

---

## Structure du projet

```text
Projet_Régression_Linéaire.ipynb
README.md
```

---

## Étapes réalisées

1. Importation des bibliothèques.
2. Chargement du jeu de données.
3. Exploration des données.
4. Préparation des variables explicatives et de la variable cible.
5. Séparation des données en ensembles d'entraînement et de test.
6. Entraînement d'un modèle de régression linéaire.
7. Optimisation des hyperparamètres via Grid Search.
8. Validation croisée.
9. Évaluation des performances du modèle.
10. Analyse des résultats.

---

## Résultats attendus

À l'issue du notebook, le modèle est capable de prédire le prix d'un logement à partir de ses caractéristiques, tout en étant évalué à l'aide de métriques adaptées à un problème de régression (par exemple MAE, RMSE ou R² selon les sections du notebook).

---

## Lancement

1. Cloner le dépôt ou télécharger le notebook.
2. Installer les dépendances :

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

3. Ouvrir le notebook :

```bash
jupyter notebook Projet_Régression_Linéaire.ipynb
```

ou

```bash
jupyter lab
```

4. Exécuter les cellules dans l'ordre.

---

## Compétences mises en œuvre

* Analyse de données
* Prétraitement des données
* Machine Learning supervisé
* Régression linéaire
* Validation croisée
* Optimisation des hyperparamètres
* Évaluation de modèles

---

## Auteur

Emmanuel YOHORE
