# Analyse et Prédiction du Churn Client - Telco

Projet portfolio Data Science (débutant) – Février 2026

**Objectif**  
Comprendre les facteurs de départ des clients (churn) dans un dataset télécom et construire un modèle simple de prédiction.

**Dataset**  
- Telco Customer Churn (Kaggle)  
- Lien : https://www.kaggle.com/datasets/blastchar/telco-customer-churn  
- 7043 clients, 21 colonnes  
- Colonne cible : Churn (Yes/No)

**Observations rapides du dataset**  
- Taux de churn global : environ 26-27 % (beaucoup de perte clients !)  
- Tenure moyenne : ~32 mois  
- Clients avec contrat Month-to-month churnent plus (à vérifier)  
- TotalCharges a des valeurs vides à nettoyer (" " → NaN)  
- Autres idées : impact de MonthlyCharges, PaymentMethod, InternetService

**Étapes du projet**  
1. Chargement et nettoyage (Pandas)  
2. Analyse Exploratoire (EDA) : graphiques Seaborn/Matplotlib  
3. Modélisation : Logistic Regression / Random Forest  
4. Dashboard Power BI (KPI, slicers)  
5. Conclusions + déploiement sur GitHub

**Technologies**  
- Python : Pandas, NumPy, Scikit-learn, Seaborn  
- Power BI Desktop  
- GitHub pour le portfolio

Prochaines étapes : premier notebook Colab + visualisations !

Feedback bienvenu ! #DataScience #ChurnPrediction #Portfolio
