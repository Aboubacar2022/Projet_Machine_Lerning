## 💶 Détection de Faux Billets – Machine Learning (Python)
### 📌 Description du projet

Ce projet a pour objectif de développer un algorithme capable de détecter automatiquement des faux billets à partir de leurs caractéristiques géométriques.

L’analyse est réalisée en Python via un Jupyter Notebook et s’appuie sur des techniques de :

### *Data Cleaning*

Analyse exploratoire des données (EDA)

Machine Learning supervisé et non supervisé

Analyse en Composantes Principales (ACP)

### 🎯 *Objectifs*

L’Organisation souhaite :

Identifier les caractéristiques discriminantes entre vrais et faux billets

Construire un modèle capable de classifier automatiquement un billet

Explorer la structure des données via des méthodes statistiques et de clustering

### 🧹 Nettoyage et Préparation des Données

Vérification des doublons

Détection des valeurs négatives

Gestion des valeurs manquantes

Imputation des valeurs manquantes (margin_low) via régression linéaire

Standardisation des données (StandardScaler)

### 📈 Analyse Exploratoire (EDA)
Analyse univariée

Répartition des vrais et faux billets (diagramme circulaire)

Histogrammes des variables

Étude des distributions

Analyse bivariée

Boxplots par classe

Pairplots

Matrice de corrélation

### 🤖 Machine Learning
🔹 Apprentissage non supervisé – K-Means

Normalisation des données

Recherche du nombre optimal de clusters via le coefficient de silhouette

Résultat : K = 2, cohérent avec les deux classes (vrai / faux)

🔹 Analyse en Composantes Principales (ACP)

### 🛠️ Technologies utilisées

Python 3

Jupyter Notebook

NumPy

Pandas

Matplotlib

Seaborn

Plotly

Scikit-learn

Réduction de dimension

Étude de la variance expliquée

Visualisation des relations entre variables

Identification des variables les plus discriminantes

### 📌 Résultats

Les variables géométriques permettent de distinguer efficacement les faux billets.

Le clustering K-Means retrouve naturellement 2 groupes.

Certaines variables comme length et margin_low sont particulièrement discriminantes.

L’ACP confirme la séparation structurelle des classes.

### 📚 Compétences démontrées

Analyse de données

Data cleaning

Régression linéaire

Clustering (K-Means)

Réduction de dimension (PCA)

Visualisation de données

Interprétation statistique
