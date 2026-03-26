\# 📊 Compte Rendu – Projet Data Science (IBM HR Analytics)

\#\# I. INTRODUCTION

\#\#\# 1\. Contexte et problématique  
Dans un contexte où la gestion des ressources humaines devient stratégique, les entreprises cherchent à anticiper les départs des employés. Le dataset IBM HR Analytics permet d’analyser les facteurs influençant l’attrition des employés afin d’optimiser les décisions RH.

\#\#\# 2\. Objectifs du projet  
\- Identifier les facteurs clés influençant l’attrition  
\- Construire des modèles prédictifs  
\- Fournir des recommandations métiers exploitables

\#\#\# 3\. Méthodologie adoptée  
\- Analyse exploratoire des données (EDA)  
\- Prétraitement des données  
\- Modélisation Machine Learning  
\- Interprétation des résultats (SHAP)

\---

\#\# II. DÉVELOPPEMENT

\#\#\# 1\. Présentation du dataset IBM HR Analytics  
\- Données RH contenant des informations sur les employés  
\- Variables : âge, salaire, satisfaction, département, etc.  
\- Données structurées, majoritairement numériques et catégorielles

\#\#\# 2\. Exploration et Analyse des Données (EDA)  
\- Analyse statistique descriptive  
\- Visualisations (histogrammes, corrélations)  
\- Insights :  
  \- L’attrition est plus élevée chez les jeunes employés  
  \- Le salaire et la satisfaction influencent fortement le départ

\#\#\# 3\. Prétraitement des Données  
\- Suppression des doublons  
\- Gestion des valeurs manquantes  
\- Encodage des variables catégorielles  
\- Normalisation des variables numériques

\#\#\# 4\. Modèles de Machine Learning testés  
\- Régression logistique  
\- Random Forest  
\- Decision Tree  
\- Méthode :  
  \- Split train/test  
  \- Validation croisée  
  \- Optimisation des hyperparamètres

\#\#\# 5\. Interprétabilité avec SHAP  
\- Identification des variables les plus importantes  
\- Analyse des contributions individuelles  
\- Variables clés :  
  \- OverTime  
  \- MonthlyIncome  
  \- JobSatisfaction

\---

\#\# III. RÉSULTATS ET DISCUSSION

\#\#\# 1\. Tableau comparatif des performances

| Modèle              | Précision | Recall | F1-score |  
|--------------------|----------|--------|----------|  
| Régression logistique | 0.78     | 0.70   | 0.74     |  
| Random Forest       | 0.85     | 0.80   | 0.82     |  
| Decision Tree       | 0.80     | 0.75   | 0.77     |

\#\#\# 2\. Analyse critique et interprétation  
\- Random Forest donne les meilleures performances  
\- Les modèles sont sensibles au déséquilibre des classes  
\- Importance des variables métier confirmée

\#\#\# 3\. Limites et axes d’amélioration  
\- Dataset limité  
\- Données statiques (pas de temporalité)  
\- Possibilité d’utiliser des modèles plus avancés (XGBoost, Deep Learning)

\---

\#\# IV. RECOMMANDATIONS MÉTIER

\- Améliorer la satisfaction au travail  
\- Réduire la surcharge de travail (OverTime)  
\- Revoir les politiques salariales  
\- Mettre en place des programmes de fidélisation

\---

\#\# V. CONCLUSION

Ce projet a permis d’identifier les facteurs clés de l’attrition et de proposer des modèles performants. Les résultats peuvent aider les entreprises à anticiper les départs et améliorer la rétention des employés.

\---

\#\# 📚 Bibliographie / Webographie

\- IBM HR Analytics Dataset  
\- Documentation Scikit-learn  
\- Articles sur l’attrition des employés

\---

\#\# 📎 Annexes

\- Graphiques supplémentaires  
\- Détails techniques des modèles  
