
# Data Documentation
## Smart Parking & Loading Dock Monitoring

### 1. Objectif

Ce dossier contient la documentation des datasets
utilisés pour :

- La détection des véhicules.
- La classification des places libres et occupées.
- Le suivi temporel des véhicules.
- L'évaluation des performances du système.

### 2. Datasets à explorer

| Dataset | Utilisation principale | Statut |
|---------|------------------------|--------|
| PKLot | Classification libre/occupé | À explorer |
| CNRPark-EXT | Tests de robustesse | À explorer |
| COCO | Détection des véhicules | À explorer |
| Roboflow | Images complémentaires de camions | À explorer |
| Own Videos | Suivi temporel et tests réels | À collecter |

### 3. Sources et licences

Pour chaque dataset, documenter :

- Nom :
- Source officielle (URL) :
- Auteur / organisme :
- Version :
- Date de téléchargement :
- Licence :
- Conditions d'utilisation :
- Nombre d'images :
- Classes disponibles :
- Format des annotations :

Les licences et les versions seront vérifiées
avant toute utilisation.

### 4. Organisation des données

- raw/ : données originales non modifiées.
- processed/ : données nettoyées et préparées.
- own_videos/ : vidéos enregistrées par l'équipe.

### 5. Prétraitement prévu

1. Vérification de la qualité des images.
2. Analyse des annotations.
3. Identification des doublons.
4. Vérification des classes.
5. Conversion des annotations si nécessaire.
6. Séparation train / validation / test.

### 6. Stockage

Les datasets volumineux ne sont pas stockés
directement sur GitHub.

Les sources et les instructions de téléchargement
seront documentées pour assurer la reproductibilité.
