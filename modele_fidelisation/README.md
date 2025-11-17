# 🤖 Modélisation de la Fidélisation Client (E-commerce)

## 🎯 Objectif
Construire un modèle prédictif permettant d’identifier les facteurs qui influencent
le plus la fidélité des clients et estimer la probabilité qu’un client devienne fidèle.

Cette analyse combine :
- statistiques exploratoires,
- tests d’hypothèses,
- modélisation (régression logistique).

---

## 🧠 Approche analytique

### 1. Analyse exploratoire
- Étude des variables démographiques, comportementales et transactionnelles
- Visualisations pour détecter tendances et anomalies
- Analyse de corrélations

### 2. Tests statistiques
- Test Khi² (relations entre variables catégorielles)
- Test t & ANOVA (comparaison de moyennes)

### 3. Modèle prédictif
- Régression logistique (sklearn)
- Analyse des coefficients → impact direct sur la fidélité
- Matrice de confusion
- Mesures de performance : Accuracy, Precision, Recall

---

## 🛠️ Technologies utilisées
- Python : pandas, numpy, matplotlib, seaborn
- Machine Learning : scikit-learn

---

## 📊 Résultats clés
- **Précision du modèle : ~86 %**
- Variables les plus influentes :
  - satisfaction client (corr ≈ 0.64)
  - engagement web (visites, durée)
  - fréquence d’achat
- Les variables socio-démographiques ont un impact faible
- Potentiel de segmentation pour campagnes CRM

---

## 🧭 Recommandations business
- Renforcer l’expérience utilisateur (UX) → impact fort sur fidélité
- Cibler les non-fidèles via campagnes de réactivation
- Segmenter les clients en High / Medium / Low potentiel
- Optimiser site et tunnel d’achat pour booster engagement

---

## 📁 Contenu du dossier
- `/notebooks` : modèle complet (EDA + ML)
- `/img` : matrices, graphiques, distributions
- `/data` : dataset anonymisé ou échantillon

---

## 📌 Conclusion
Ce projet démontre la capacité à mener une étude complète :
statistique → modélisation → interprétation → recommandations marketing.

