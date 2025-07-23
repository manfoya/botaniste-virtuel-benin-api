# Botaniste Virtuel du Bénin (API Backend) BJ

Le "Shazam des plantes" du Bénin. Ce projet est le backend (API) d'une application d'intelligence artificielle visant à identifier la flore locale pour soutenir l'agriculture, l'éducation et la conservation de la biodiversité.

---

## Objectif du Projet

Le Bénin possède une riche biodiversité, mais l'identification des espèces végétales reste un défi pour les agriculteurs, les étudiants et même les chercheurs. Une erreur d'identification peut avoir des conséquences économiques (mauvaise culture) ou sanitaires (plante toxique).

Ce projet vise à créer un **botaniste virtuel de poche** en développant :
1.  **Un modèle de Deep Learning** capable d'identifier des plantes béninoises à partir d'une simple photo.
2.  **Une base de données informative** sur les usages (médicinaux, agricoles), la toxicité et les caractéristiques de chaque plante.
3.  **Une API robuste** pour servir ce modèle à des applications web et mobiles.

## Statut Actuel

**Phase 1 : Preuve de Concept (PoC) en cours.**

Nous développons un premier modèle capable de reconnaître 5 espèces emblématiques et distinctes :
*   Manioc (Manihot esculenta)
*   Maïs (Zea mays)
*   Palmier à huile (Elaeis guineensis)
*   Baobab (Adansonia digitata)
*   Hibiscus (Hibiscus rosa-sinensis)

## Structure du Dépôt

```
/
├── data/              # Données brutes et traitées (ignoré par Git)
├── docs/              # Documentation du projet
├── models/            # Modèles entraînés (ignoré par Git)
├── notebooks/         # Carnets Jupyter d'expérimentation
├── src/               # Code source principal (traitement, modèle, API)
├── tests/             # Tests unitaires et d'intégration
├── .gitignore         # Fichiers à ignorer
├── README.md          # Vous êtes ici
└── requirements.txt   # Dépendances Python
```

## Installation et Utilisation

(À compléter plus tard...)

1.  Clonez le dépôt :
    ```bash
    git clone https://github.com/manfoya/botaniste-virtuel-benin-api.git
    cd botaniste-virtuel-benin-api
    ```

2.  Installez les dépendances :
    ```bash
    pip install -r requirements.txt
    ```

## 🤝 Contribution

Ce projet est ouvert et collaboratif. N'hésitez pas à ouvrir une *issue* pour discuter de nouvelles fonctionnalités ou proposer des améliorations.