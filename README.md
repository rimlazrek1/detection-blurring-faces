# Floutage des visages pour anonymisation RGPD

Projet de détection et floutage automatique des visages dans les images pour anonymisation conforme au RGPD.

## Installation

### Dépendances principales
Le projet nécessite les bibliothèques suivantes :
- **OpenCV** : Pour la détection et le traitement d'images
- **NumPy** : Pour les calculs numériques
- **Matplotlib** : Pour l'affichage des images et graphiques
- **Jupyter** : Pour l'exécution du notebook

### Avec pip
```bash
pip install opencv-python numpy matplotlib jupyter
```

### Avec Conda
Un environnement Conda préconfiguré est fourni dans `environment.yml`. Pour l'installer et l'activer :
```bash
conda env create -f environment.yml
conda activate face-blur
```

## Utilisation

### Avec Jupyter Notebook
Ouvrez `face_blur_project.ipynb` et exécutez les cellules dans l'ordre.

### Avec Python
```bash
python face_blur.py
```

**Note :** Les résultats du traitement sont déjà disponibles dans le dossier `output/`. Il n'est pas nécessaire d'exécuter le projet si vous souhaitez uniquement consulter les images floutées et les comparaisons.

## Structure du projet

```
ia-projet/
├── .gitignore               # Fichiers à ignorer par Git
├── environment.yml          # Configuration de l'environnement Conda
├── face_blur_project.ipynb  # Notebook Jupyter principal
├── README.md                # Ce fichier de documentation
├── __pycache__/             # Cache Python (généré automatiquement, ignoré par Git)
├── images/                  # Images à traiter
└── output/
    ├── blurred/            # Images avec visages floutés
    └── comparison/          # Images de comparaison avant/après
```

## Résultats

- **50 images** traitées
- Détection des visages frontaux et de profil
- Floutage gaussien pour anonymisation
- Statistiques de traitement sauvegardées





