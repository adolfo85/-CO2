# Valores de CO2 a nivel mundial.  

By: Adolfo C. De Boeck.

Version: 0.1.0

Medición de valores de CO2 analizados por país y región. 

## Prerequisites

- [Anaconda](https://www.anaconda.com/download/) >=4.x
- Optional [Mamba](https://mamba.readthedocs.io/en/latest/)

## Create environment

```bash
conda env create -f environment.yml
activate CO2
```

or 

```bash
mamba env create -f environment.yml
activate CO2
```

## Project organization

    CO2
        ├── data
        │   ├── processed      <- The final, canonical data sets for modeling.
        │   └── raw            <- The original, immutable data dump.
        │
        ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
        │                         the creator's initials, and a short `-` delimited description, e.g.
        │                         `1.0-jvelezmagic-initial-data-exploration`.
        │
        ├── .gitignore         <- Files to ignore by `git`.
        │
        ├── environment.yml    <- The requirements file for reproducing the analysis environment.
        │
        └── README.md          <- The top-level README for developers using this project.

---
Project created for demonstration purposes for the course "[Personalización Avanzada de Entorno para ciencia de Datos]()" by [Platzi](https://platzi.com/) - [@jvelezmagic](https://jvelezmagic.com/).
