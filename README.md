# 📊 Customer Churn Prediction – Telco Dataset

## 📌 Description  
Ce projet prédit le **churn des clients** à partir du dataset WA_Fn-UseC_-Telco-Customer-Churn.  
Il comprend le **prétraitement des données, l’analyse exploratoire et l’entraînement de modèles de Machine Learning** (Régression Logistique, Random Forest,K-Nearest Neighbor, etc.) pour identifier les clients à risque.  
L’objectif est de fournir des **insights exploitables** afin d’améliorer la fidélisation des clients.  

---

## 🚀 Étapes principales  
1. **Exploration des données (EDA)**  
   - Analyse des variables catégorielles et numériques  
   - Détection et traitement des valeurs manquantes  
   - Visualisation des distributions et des corrélations  

2. **Prétraitement des données**  
   - Encodage des variables catégorielles avec **One-Hot Encoding**  
   - Normalisation / standardisation des variables numériques  
   - Séparation des données en `X` (features) et `y` (target = Churn)  

3. **Modélisation**  
   - Entraînement de plusieurs modèles de classification (Logistic Regression, Random Forest,K-Nearest Neighbor, etc.)  
   - Optimisation des hyperparamètres (GridSearchCV / RandomizedSearchCV)  
   - Évaluation des performances avec **Accuracy, Precision, Recall, F1-score et AUC**  

4. **Résultats**  
   - Comparaison des modèles  
   - Identification des features les plus importantes  
   - Visualisation des métriques et matrices de confusion  

---

## 📂 Contenu du repo  
- `customer_churn_prediction_telco.ipynb` → Notebook principal avec tout le workflow  
- `README.md` → Description du projet  
- `requirements.txt`  → dépendances Python  
- `WA_Fn-UseC_-Telco-Customer-Churn.csv`  → dataset  

---

## 🛠️ Technologies utilisées  
- **Python**  
- **Pandas, Numpy** → manipulation de données  
- **Matplotlib, Seaborn** → visualisation  
- **Scikit-learn** → prétraitement, modèles ML et évaluation

---

