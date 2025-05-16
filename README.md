# 🧠 Projet IA — Prédiction de maladies cardiaques avec KNN

Ce projet académique a été réalisé dans le cadre d’un travail pratique (TP) en intelligence artificielle supervisée. Il consiste à implémenter un modèle de classification basé sur l’algorithme des K plus proches voisins (KNN) afin de prédire la présence de maladies cardiaques à partir de données cliniques.

## 📁 Fichiers du projet

- `Tp_knn.ipynb` : Notebook Jupyter contenant l’intégralité du code (prétraitement, modélisation, évaluation).
- `Heart_disease_cleveland_new.csv` : Jeu de données contenant les caractéristiques cliniques des patients.

## 🎯 Objectifs pédagogiques

- Apprendre à préparer des données pour un algorithme de Machine Learning.
- Comprendre le fonctionnement de l’algorithme KNN.
- Évaluer les performances d’un modèle de classification.
- Optimiser le paramètre `k` pour améliorer la précision du modèle.

## 🔬 Détails du dataset

Le jeu de données contient plusieurs variables médicales :

- `age`, `sex`, `cp`, `trestbps`, `chol`, `fbs`, `restecg`, `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`
- `target` (variable à prédire) : 1 = présence de maladie cardiaque, 0 = absence

## 🔧 Étapes principales

1. Chargement et exploration du jeu de données
2. Nettoyage des données et gestion des valeurs manquantes
3. Normalisation des variables
4. Séparation en ensembles d'entraînement et de test
5. Entraînement du modèle KNN
6. Évaluation avec la matrice de confusion, précision, rappel, F1-score
7. Optimisation du paramètre `k` avec une courbe de validation

## 📚 Bibliothèques utilisées

- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn

## 🚀 Exécution du projet

```bash
git clone https://github.com/votre-utilisateur/tp-knn-heart.git
cd tp-knn-heart
pip install -r requirements.txt
jupyter notebook Tp_knn.ipynb

