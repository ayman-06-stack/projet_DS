# Projet Data Science 
## Données et pipeline (DVC)
Jeu : UCI Breast Cancer Wisconsin (Diagnostic), 569 observations.
Pipeline : `prepare` -> `train` -> `evaluate` (voir `dvc.yaml`).

- Déclarer le stockage : `dvc remote add --local -d storage <dossier>`
- Récupérer données et modèle : `dvc pull`
- Rejouer le pipeline : `dvc repro` ; métriques : `dvc metrics show`
- Version de référence : tag `data-bc-v1`
