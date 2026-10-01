# Analyse comparative des prix hôteliers — Côte d'Azur & Monaco

## Le problème
Les hôteliers indépendants fixent souvent leurs prix à l'intuition,
sans données sur le marché concurrentiel ni sur l'impact des événements
locaux sur la demande.

## La solution
Analyse complète des prix hôteliers sur 6 villes de la Côte d'Azur
sur 60 jours — saisonnalité, impact événements, comparaison par catégorie.

## Résultats clés
- 🏨 **6 villes analysées** — Nice, Cannes, Antibes, Menton, Juan-les-Pins, Monaco
- 📊 **1 800 entrées** sur 60 jours (juin-juillet 2024)
- 💰 **Monaco 2.6x plus cher** que Menton pour la même catégorie
- 📅 **+35 à 38% le weekend** dans toutes les villes
- 🏎️ **Grand Prix F1** — pic de +250% sur les prix de Monaco

## Insights business

| Ville | Prix moyen | vs Nice |
|-------|-----------|---------|
| Monaco | 860 € | +101% |
| Antibes | 526 € | +23% |
| Cannes | 501 € | +17% |
| Nice | 428 € | référence |
| Juan-les-Pins | 373 € | -13% |
| Menton | 326 € | -24% |

## Stack technique
- **Python** — Pandas, NumPy, Plotly
- **Visualisation** — 4 graphiques interactifs

## Structure du projet
- data/hotel_prices.csv — Dataset 1800 entrées
- notebooks/01_collecte_donnees.ipynb — Génération des données
- notebooks/02_analyse_visualisations.ipynb — Analyse et visualisations

---
*Projet réalisé par [ClearInsightdata](https://github.com/clearinsightdata)*