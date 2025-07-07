# 💳 Détection de Fraudes par Carte Bancaire – Projet Machine Learning

Ce projet a été réalisé dans le cadre du cours **Machine Learning – Été 2025** à l'Université du Québec à Chicoutimi (UQAC), par **Ben Aymar Youssouf** (ESIEA – TD38).

---

## 🎯 Objectif
Utiliser des modèles d’apprentissage supervisé pour prédire les fraudes bancaires sur un jeu de données réel et déséquilibré.

---

## 📊 Jeu de données
- Source : Kaggle – [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284 807 transactions
- Variable cible : `Class` (0 = normale, 1 = fraude)
- 30 colonnes anonymisées via PCA : `V1` à `V28`, plus `Time` et `Amount`

---

## 🧪 Modèles utilisés
- Régression Logistique
- Random Forest Classifier

---

## 📈 Évaluation des modèles
- **Métriques** : Précision, Rappel, F1-score, AUC, Matrice de confusion
- **Meilleur modèle** : Random Forest (Recall : 76 %, AUC : 0.98)

---

## 📁 Fichiers fournis

| Fichier | Description |
|--------|-------------|
| `Projet_ccfd_final.ipynb` | Notebook complet avec preprocessing, entraînement et évaluation |
| `Rapport_Projet_Python.pdf` | Rapport technique de 10 pages |
| `repartition_classes.png` | Histogramme des classes |
| `matrices_confusion_comparaison.png` | Résultats comparés |
| `courbe_roc_comparaison.png` | Courbe ROC |

---

## ▶️ Exécution

```bash
pip install scikit-learn pandas matplotlib seaborn
