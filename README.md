# Floutage des visages pour anonymisation RGPD

Projet de détection et floutage automatique des visages dans les images pour anonymisation conforme au RGPD.

## Installation

```bash
pip install opencv-python numpy matplotlib
```

## Utilisation

### Avec Jupyter Notebook
Ouvrez `face_blur_project.ipynb` et exécutez les cellules dans l'ordre.

### Avec Python
```bash
python face_blur.py
```

## Structure du projet

```
ia-projet/
├── images/              # Images à traiter
├── output/
│   ├── blurred/        # Images avec visages floutés
│   └── comparison/     # Images de comparaison avant/après
└── face_blur_project.ipynb  # Notebook Jupyter
```

## Résultats

- **50 images** traitées
- Détection des visages frontaux et de profil
- Floutage gaussien pour anonymisation
- Statistiques de traitement sauvegardées





