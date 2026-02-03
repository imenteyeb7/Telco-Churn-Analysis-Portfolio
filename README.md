# Analyse et Prédiction du Churn Client - Telco

Projet portfolio Data Science (débutant) – Février 2026

**Objectif**  
Comprendre pourquoi certains clients quittent la compagnie télécom (churn) et construire un modèle simple pour les prédire.

**Dataset**  
- Nom : Telco Customer Churn  
- Source : Kaggle  
- Lien : https://www.kaggle.com/datasets/blastchar/telco-customer-churn  
- Nombre de lignes : 7043 clients  
- Nombre de colonnes : 21  
- Colonne cible : **Churn** (Yes = client parti, No = client resté)

**Premières observations (après ouverture du CSV)**  
- Taux de churn approximatif : ~26-27 % (plus d'un quart des clients partent !)  
- Colonne TotalCharges : contient des valeurs vides (" ") → à convertir en NaN et nettoyer  
- Contrat : 3 types (Month-to-month, One year, Two year) → Month-to-month semble risqué  
- Tenure : moyenne autour de 32 mois, mais probablement plus faible pour les churners  
- MonthlyCharges : moyenne ~64-65 $ (à confirmer avec df.describe())

**Étapes prévues du projet**  
1. Chargement et nettoyage des données (Pandas)  
2. Analyse Exploratoire (EDA) : graphiques churn par contrat, tenure, charges, etc.  
3. Modélisation : Logistic Regression ou Random Forest (Scikit-learn)  
4. Évaluation : accuracy, confusion matrix, etc.  
5. Dashboard interactif Power BI (KPI, filtres)  
6. Conclusions business + upload sur GitHub

**Technologies utilisées**  
- Python : Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- Power BI Desktop  
- Google Colab pour les notebooks  
- GitHub pour le portfolio

Prochaines étapes : premier notebook avec df.head(), nettoyage et EDA !

Feedback / suggestions bienvenus !  
#DataScience #ChurnPrediction #Python #Portfolio #BusinessIntelligence
