# 🧠 Projet de Parallélisation - ML & KMeans sur Spark vs Centralisé

Ce dépôt présente un projet d'exploration de la **parallélisation d'algorithmes de Machine Learning** à l'aide d'Apache Spark, comparée à leurs versions centralisées recodées en Python. Deux cas d'étude ont été réalisés : la détection de botnets avec l'algorithme de **régression logistique**, et la classification de chiffres manuscrits (**MNIST**) avec l'algorithme de **K-Means**.

---

## 📁 Structure du projet


- `botnet_logistic_regression/`
  - `ml_botnet_centralised.ipynb` : Version centralisée de la régression logistique recodée en python.
  - `ml_botnet_parallelized.ipynb` : Version parallèle avec PySpark de la régression logistique avec validation croisée.
  - `ML Written Report Botnet.pdf` : Rapport spécifique à cette expérimentation.

- `mnist_kmeans/`
  - `kmeans_centralised.ipynb` : Implémentation centralisée du K-Means sur MNIST.
  - `kmeans_parallelized.ipynb` : Implémentation distribuée avec Spark.
  - `ML Written Report KMeans.pdf` : Rapport spécifique à cette expérimentation.

- `slides_presentation.pdf` : Slides de présentation du projet.

- `README.md` : Présentation générale du projet (ce fichier).
---

## ⚙️ Objectif

Étudier l'apport de la **parallélisation avec Spark** sur les performances de modèles d’apprentissage automatique par rapport aux versions centralisées classiques. Comparaison en termes de :

- Temps d'exécution
- Qualité des résultats
- Scalabilité

---

## 🖥️ Environnement recommandé

- Python 3.8+, numpy, matplotlib
- Jupyter Notebook
- Apache Spark avec PySpark

---

## 🧾 Présentation

Le fichier **`slides_presentation.pdf`** contient un résumé des approches, résultats comparatifs, et conclusions du projet.