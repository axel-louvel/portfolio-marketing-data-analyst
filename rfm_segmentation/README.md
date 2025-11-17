# 🔍 Segmentation RFM – Retail (Feminiz)

## 🎯 Objectif
Segmenter la base clients selon trois dimensions clés :
- Recency (récence d’achat)
- Frequency (nombre d’achats)
- Monetary (dépenses cumulées)

L’objectif est d’identifier les segments les plus rentables et d’optimiser les campagnes marketing (fidélisation, réactivation, VIP).

---

## 🧠 Approche analytique
- Nettoyage du dataset
- Calcul des scores RFM
- Analyse corrélation : récence, fréquence, dépenses
- Segmentation en 3 groupes : Low, Medium, High Value
- Visualisations pour interprétation marketing
- Recommandations stratégiques orientées business

---

## 🛠️ Technologies utilisées
- Python (pandas, numpy, matplotlib)
- Power BI (visualisations complémentaires)

---

## 📊 Insights clés
- Forte corrélation entre fréquence et montant dépensé
- Les clientes High Value génèrent une part disproportionnée du revenu
- Les clientes Low Value montrent des signes d'attrition → campagnes de réactivation
- La récence impacte moins que la fréquence sur la valeur cumulée

---

## 📁 Contenu du dossier
- `/notebooks` : Notebook Python (analyse RFM complète)
- `/img` : Graphiques utilisés dans le rapport
- `/data` : Dataset anonymisé ou source

---

## 🧭 Recommandations marketing
- Programme VIP pour clientes High Value (+ offres exclusives)
- Cross-selling ciblé pour Medium Value
- Emailing de réactivation pour Low Value
- Augmenter fréquence → principal levier de croissance du panier total
