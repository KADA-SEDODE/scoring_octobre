# 📊 Projet Scoring - M2 MOSEF (2024-2025)

Ce projet vise à construire un **modèle de scoring de crédit** pour prédire le risque de défaut (`BAD = 1`) ou non (`BAD = 0`) en utilisant des techniques avancées de **Machine Learning**.

---

## 📂 Structure du projet

📁 `data/` - Contient les données :
- `hmeq.csv` : Données brutes de départ
- `data_train.csv` / `data_test.csv` : Jeu d’entraînement et test après preprocessing
- `data_score_imputed.csv` : Données imputées après traitement des valeurs manquantes

📁 `notebooks/` - Contient les notebooks d'analyse :
- `EDA.ipynb` : Analyse exploratoire des données
- `Random_Forest.ipynb` : Modélisation avec Random Forest
- `XGBoost.ipynb` : Modélisation avec XGBoost
- `LightGBM.ipynb` : Modélisation avec LightGBM
- `Reg_Log.ipynb` : Régression Logistique

📄 `requirements.txt` - Liste des dépendances pour exécuter le projet  
📄 `README.md` - Ce fichier  

---

## 🛠️ Installation & Exécution

### **1️⃣ Cloner le projet**
```bash
git clone https://github.com/KADA-SEDODE/scoring_octobre.git
cd scoring_octobre
python -m venv venv
2️⃣ Créer un environnement virtuel et installer les dépendances
source venv/bin/activate  # (Windows: venv\Scripts\activate)
pip install -r requirements.txt
3️⃣ Lancer un Notebook Jupyter
jupyter notebook
