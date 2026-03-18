# Data Mining Workspace

Academic repository for Data Mining practice with notebooks, datasets, and project material.

<p align="center">
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/Python-Data%20Analysis-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="Status" src="https://img.shields.io/badge/Status-Active-0A7E8C?style=for-the-badge" />
</p>

---

## Contents

- [Overview](#overview)
- [Repository structure](#repository-structure)
- [Included datasets](#included-datasets)
- [How to use this repository](#how-to-use-this-repository)
- [Featured notebooks](#featured-notebooks)
- [Recommendations](#recommendations)

---

## Overview

This workspace brings together:

- Data Mining class exercises,
- preprocessing workshops,
- classic datasets for experimentation,
- and an applied project with billionaire data analysis.

The goal is to keep both base material (data) and practical work (notebooks) in one place.

---

## Repository structure

```text
.
|-- DataMiningExercises.ipynb
|-- Books/
|-- Datasets/
|   |-- adult/
|   |-- breast+cancer+wisconsin+original/
|   |-- iris/
|   `-- predict+students+dropout+and+academic+success/
|-- Homeworks - Workshops/
|   |-- Entropia - Seleccion de Caracteristicas.ipynb
|   `-- TallerPreprocesamiento-NicolasMartinezLopez-MineriaDeDatos.ipynb
`-- Project/
    |-- Billionaires Statistics Dataset.csv
    |-- Billionaires_dataset.csv
    |-- Billionaires_Original_Categories_Only.csv
    |-- Billionaires_Professional_Titles.csv
    |-- getNumberOfCompanies.ipynb
    |-- person_companies.csv
    |-- person_names.csv
    |-- test_improved_version.ipynb
    `-- unique_sources.csv
```

---

## Included datasets

| Dataset | Main use |
|---|---|
| `adult` | Classification and analysis of socioeconomic variables |
| `breast cancer wisconsin` | Pattern detection in medical diagnosis |
| `iris` | Classic benchmark for multiclass classification |
| `students dropout` | Dropout and academic success prediction |

---

## How to use this repository

### 1) Create an environment (optional but recommended)

```bash
python -m venv .venv
```

In Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 2) Install base libraries

```bash
pip install jupyter pandas numpy matplotlib seaborn scikit-learn
```

### 3) Open notebooks

```bash
jupyter lab
```

or

```bash
jupyter notebook
```

---

## Featured notebooks

- `DataMiningExercises.ipynb`: general exercises.
- `Homeworks - Workshops/TallerPreprocesamiento-NicolasMartinezLopez-MineriaDeDatos.ipynb`: preprocessing workshop.
- `Homeworks - Workshops/Entropia - Seleccion de Caracteristicas.ipynb`: entropy-based feature selection.
- `Project/getNumberOfCompanies.ipynb`: support notebook for the billionaire project.
- `Project/test_improved_version.ipynb`: tests and improvements for the project workflow.

---

## Recommendations

- Keep notebooks clean and reproducible.
- Avoid modifying original datasets without creating a derived copy first.
- Document key findings directly in Markdown cells within each notebook.

---

If you want, in a next step I can also prepare a version with:

- an "academic report" style visual cover,
- an automatic section index,
- and a notebook progress table.
