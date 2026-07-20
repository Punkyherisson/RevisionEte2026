# 📚 Notebooks de Révision DataCamp

7 notebooks organisés par thème pour réviser tes 31 cours DataCamp.
Dernière Mise à jour 20/07/2026

---

## Organisation

| # | Notebook | Cours couverts | Thèmes clés |
|---|----------|----------------|-------------|
| 1 | `01_Python_Fondamentaux.ipynb` | Intro Python, Intermediate Python (×2), Intro Functions | Types, listes, dicts, boucles, fonctions, OOP, erreurs, générateurs |
| 2 | `02_NumPy_Pandas.ipynb` | Intro NumPy, Data Manipulation with pandas, Intro Data Science | Arrays, indexing, groupby, merge, pivot, NaN |
| 3 | `03_SQL_Bases_de_Donnees.ipynb` | SQL (Intro + Intermediate + Relational + Joining + Design + AI) | SELECT, JOIN, GROUP BY, Window functions, CTE, normalisation |
| 4 | `04_Visualisation_de_Donnees.ipynb` | Matplotlib, Seaborn, Plotly, Understanding DataViz | Histogramme, boxplot, scatter, heatmap, FacetGrid, Plotly interactif |
| 5 | `05_Statistiques_Echantillonnage.ipynb` | Intro Statistics (×2), Sampling | Descriptives, distributions, TCL, IC, tests d'hypothèses, bootstrap |
| 6 | `06_Machine_Learning.ipynb` | Understanding ML, Supervised Learning, Tree-Based Models, Unsupervised, Cluster, Dimensionality | Classification, régression, arbres, Random Forest, XGBoost, clustering, PCA, t-SNE |
| 7 | `07_EDA_Donnees_Manquantes.ipynb` | EDA in Python, Dealing with Missing Data | Checklist EDA, NaN (MCAR/MAR/MNAR), outliers, encodage |

---

## Comment utiliser ces notebooks ?

1. **Lance Jupyter** : `jupyter notebook` dans ce dossier (ou JupyterLab : `jupyter lab`)
2. **Exécute les cellules** une par une avec `Shift+Enter`
3. **Fais les exercices** avant de regarder les solutions
4. **Reviens souvent** : révise un notebook par session de 45 minutes

## Ordre recommandé

Débutant → Avancé :
```
01 → 02 → 03 → 04 → 05 → 07 → 06
```

Si tu veux te concentrer sur le Machine Learning :
```
02 → 05 → 07 → 06
```

## Dépendances Python requises

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn plotly xgboost
```
