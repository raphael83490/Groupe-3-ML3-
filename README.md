# Groupe-3-ML3 - Anomaly Detection Notebook

Ce projet contient un notebook de Machine Learning non supervisé pour la détection d'anomalies sur des données de maintenance industrielle.

## Contenu

- `Session5_Anomaly_Detection_Notebook.ipynb` : notebook principal (EDA, modélisation, comparaison technique, analyse business).
- `ai4i2020.csv` : dataset local utilisé par le notebook.

## Lancer le projet

1. Ouvrir le notebook `Session5_Anomaly_Detection_Notebook.ipynb`.
2. Exécuter les cellules dans l'ordre.
3. Vérifier que le fichier `ai4i2020.csv` est présent à la racine du projet.

## Objectif business

Comparer plusieurs modèles de détection d'anomalies (`IsolationForest`, `OneClassSVM`, `LOF`, `EllipticEnvelope`) et choisir celui qui minimise le coût financier selon :

- Faux Positif (FP) = 500 EUR
- Faux Négatif (FN) = 15 000 EUR
