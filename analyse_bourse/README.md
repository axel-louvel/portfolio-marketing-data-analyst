# 📉 Analyse et Visualisation d'Actions Boursières (Python)

## 🎯 Objectif
Construire un outil automatisé permettant de :
- télécharger les données financières d’une action via `yfinance`,
- calculer les indicateurs techniques (RSI, MA50, MA200),
- évaluer le rendement et la volatilité,
- calculer le ratio de Sharpe,
- afficher des graphiques d’analyse.

Ce projet simule le travail d’un analyste financier basé sur Python.

---

## 🧠 Approche analytique
1. Récupération automatique des données (Open / Close / Volume)
2. Nettoyage & formatage du dataset
3. Calcul :
   - RSI (Relative Strength Index)
   - Moyennes mobiles 50 & 200 jours
   - Rendement journalier, volatilité
   - Ratio de Sharpe
4. Visualisation complète dans Python

---

## 🛠️ Technologies
- Python  
- yfinance  
- Pandas  
- Matplotlib  

---

## 📈 Exemple d’Insights
- Apple (AAPL) : rendement annuel ≈ 28 %, Sharpe ≈ 0.90
- Microsoft (MSFT) : volatilité plus faible, mais bon ratio rendement/risque
- Possibilité de comparer plusieurs actions dans une seule fonction

---

## 📁 Contenu du dossier
- `/scripts` : script Python pour l’analyse
- `/notebooks` : version notebook de l’analyse
- `/img` : graphiques générés
- `/data` : données exportées si nécessaire

---

## 📌 Conclusion
Ce projet démontre la capacité à produire une analyse financière complète en Python, en automatisant la collecte, le calcul d’indicateurs, et l’aide à la décision.

--- 

## 📂 Notebooks disponibles

- 📓 Analyse d’une action seule : [Analyse action](notebooks/Analyse_Action_Unique.ipynb)
- 📓 Comparaison de plusieurs actions : [Comparaison actions](notebooks/Comparaison_Actions.ipynb)
- 📓 Analyse d’un ETF : [Analyse ETF](notebooks/Analyse_ETF_Unique.ipynb)
- 📓 Comparaison de plusieurs ETF : [Comparaison ETF](notebooks/Comparaison_ETF.ipynb)


