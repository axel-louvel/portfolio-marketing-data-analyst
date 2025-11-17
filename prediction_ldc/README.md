# ⚽ Prédiction Ligue des Champions – Simulations & Modèle Pondéré

## 🎯 Objectif
Construire un modèle simple de prédiction de la Ligue des Champions en combinant :
- données historiques des saisons précédentes,
- pondération de performance,
- simulations aléatoires guidées,
- analyse des résultats probables par phase (groupes → finale).

Ce projet montre la mise en place d’un moteur de simulation basé sur des données réelles.

---

## 🧠 Approche analytique

### 1. Préparation des données
- Importation via GitHub openfootball (saisons historiques)
- Harmonisation des noms d’équipes (cleaning nécessaire)
- Structuration : phases, scores, progression des équipes

### 2. Construction d’un indice de performance
L’indice prend en compte :
- points marqués,
- différence de buts,
- performance historique récente,
- résultats contre gros clubs.

### 3. Simulation complète de la compétition
- Phase de groupes : détermination des 8ᵉ de finale
- Arbre final : 8ᵉ → Quarts → Demies → Finale
- Pondération des probabilités selon l’indice calculé

### 4. Analyse des issues possibles
- Probabilité d’atteindre les quarts / demies / finale
- Comparaison équipes fortes vs underdogs
- Visualisations

---

## 🛠️ Technologies utilisées
- Python (pandas, numpy)
- Matplotlib / Seaborn
- Sources OpenData football

---

## 📊 Résultats clés
- Les clubs avec le meilleur différentiel historique progressent en moyenne plus loin
- Les simulations produisent un gagnant probable en fonction des données récentes
- La pondération permet de mieux refléter la dynamique réelle des équipes

---

## 🎮 Intérêt du projet
Ce projet montre :
- compétences en data cleaning,
- compréhension des pondérations et modèles probabilistes,
- capacité à structurer une compétition complète,
- restitution d’un résultat compréhensible et exploitable.

---

## 📁 Contenu du dossier
- `/scripts` : moteur de simulation
- `/notebooks` : analyse complète
- `/data` : fichiers open football
- `/img` : graphiques de simulation

---

## 📌 Conclusion
Un projet original montrant ta capacité à manipuler des données sportives, 
à créer un modèle de simulation et à analyser un phénomène complexe à partir de données réelles.
