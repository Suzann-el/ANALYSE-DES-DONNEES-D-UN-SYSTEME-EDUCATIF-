# 🎓 Analyse du système éducatif mondial — Expansion internationale

> Analyse exploratoire des données éducatives de la Banque mondiale pour identifier les marchés prioritaires d'une plateforme EdTech.

---

## 🎯 Contexte

Dans le cadre d'un projet d'expansion internationale d'une start-up EdTech, ce projet analyse les données éducatives mondiales pour répondre à une question stratégique : **quels pays représentent le plus fort potentiel de clients et méritent d'être ciblés en priorité ?**

---

## ⚙️ Ce que fait le projet

- **Audit qualité** — évaluation des données manquantes, doublons, cohérence des indicateurs
- **Exploration** — description des 4 000+ indicateurs disponibles, sélection des variables pertinentes
- **Analyse géographique** — calcul des indicateurs statistiques clés (moyenne, médiane, écart-type) par pays et par bloc géographique
- **Identification des marchés** — classement des pays selon leur potentiel (taux de scolarisation, évolution démographique, accès à Internet...)
- **Visualisations** — cartes et graphiques pensés pour un public décisionnel non technique

---

## 🔍 Questions explorées

- Quels pays concentrent le plus grand nombre de lycéens et étudiants ?
- Quelle est l'évolution projetée de ce potentiel sur les prochaines années ?
- Quels marchés combinent fort potentiel et accessibilité (infrastructure numérique) ?

---

## 🛠️ Stack

`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Plotly`

---

## 📁 Structure du projet

```
├── notebooks/
│   └── analyse_exploratoire.ipynb   # Analyse complète et visualisations
└── README.md
```

---

## 📂 Données

Dataset **EdStats** de la Banque mondiale — [datacatalog.worldbank.org](https://datacatalog.worldbank.org/dataset/education-statistics)

Plus de 4 000 indicateurs internationaux : taux de scolarisation, diplomation, dépenses éducatives, données enseignants — couvrant la quasi-totalité des pays du monde.
