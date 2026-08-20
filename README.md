# 📊 Atelier Matplotlib – Capteurs IoT

## 📌 Contexte

Après avoir nettoyé et analysé les données de capteurs IoT avec NumPy et Pandas, cet atelier utilise **Matplotlib** pour représenter graphiquement les informations afin d'identifier tendances, différences entre bâtiments et anomalies.

Atelier réalisé dans le cadre du cours **Python pour ML et IA** – P1 IA, Orange Digital Center (ODC).

## 🎯 Objectifs

- Réaliser différents types de graphiques avec Matplotlib
- Identifier visuellement des tendances et des anomalies
- Comparer des bâtiments entre eux
- Exporter des graphiques dans différents formats

## 🗂️ Structure du projet

```
atelier_matplotlib_iot/
├── data/
│   └── mesures_capteurs.csv
├── notebooks/
│   └── atelier_matplotlib_iot.ipynb
└── exports/
    ├── temperature.png
    └── temperature.pdf
```

## 🧩 Contenu de l'atelier

| Partie | Graphique | Objectif |
|---|---|---|
| 1 | Line plot | Évolution de la température dans le temps, détection visuelle d'anomalies |
| 2 | Bar chart (vertical/horizontal) | Comparaison de la consommation moyenne par bâtiment |
| 3 | Histogramme | Distribution des températures et de la consommation (impact du nombre de classes) |
| 4 | Scatter plot | Relation entre température et consommation |
| 5 | Box plot | Comparaison de la dispersion température vs consommation |
| 6 | Pie chart | Répartition des états des capteurs (OK / ALERTE / ERREUR) |
| 7 | Courbes multiples | Évolution de la température par bâtiment sur un même graphique |
| 8 | Export | Sauvegarde des graphiques en PNG et PDF |
| 9 | Bonus | Fonctionnalité additionnelle pertinente |

## 🔍 Points clés d'analyse

- Détection visuelle de valeurs anormales sur la courbe de température
- Comparaison de la position de la médiane, de la taille des boîtes et des valeurs extrêmes (température vs consommation)
- Interprétation de la proportion de capteurs OK / ALERTE / ERREUR
- Impact du nombre de classes d'un histogramme sur l'interprétation de la distribution

## ▶️ Utilisation

```bash
pip install matplotlib pandas jupyter
jupyter notebook notebooks/atelier_matplotlib_iot.ipynb
```

## 📦 Livrable attendu

Dossier `atelier_matplotlib_iot/` complet, poussé sur un dépôt public GitHub avec commits explicites au fur et à mesure.

## 👤 Auteure

**Rokhaya Coumba Diouf** – parcours IA (P1 IA) Orange Digital Center (ODC)
