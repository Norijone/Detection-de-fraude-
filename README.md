# Projet 5 – Détection de fraude bancaire

Yacine Hammadache · Kousseila Tekerrabet – La Cité, automne 2026

## Phase 2 – Diagnostic des données (tâches 2.1 à 2.6)

| Fichier | Contenu |
|---|---|
| `Projet5_Phase2_taches_2.1_a_2.6.ipynb` | Notebook exécuté : chargement, relations, formats, manquants, doublons, aberrations |
| `sorties/phase2_diagnostic_2.1_a_2.6.xlsx` | Tableaux de résultats (un onglet par tâche) + journal des décisions pour la 2.7 |

## Exécuter le notebook

1. Décompresser `donnees_banque.zip` dans `data/` (on obtient `data/donnees banque/`).
2. `pip install pandas pyarrow matplotlib openpyxl jupyter` (Python 3.11 à 3.13).
3. Ouvrir le notebook et faire *Run All* (environ 4 min, 5 Go de RAM libre).

Les données converties sont enregistrées dans `data/interim/*.parquet` pour les tâches 2.7 et 2.8.
Le dossier `data/` n'est pas versionné.
