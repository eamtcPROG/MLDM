# MLDM

Course labs / materials for Machine Learning & Data Mining (MLDM).

## Contents

- `lab1/`
  - `lab1.ipynb`: Jupyter notebook for Lab 1
  - `data/data.csv`: dataset used in Lab 1

## Getting started

### Prerequisites

- Python 3.10+ (3.11 recommended)
- Jupyter (Notebook or JupyterLab)

### Setup (recommended)

Create a virtual environment and install Jupyter:

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install jupyterlab pandas numpy scikit-learn matplotlib seaborn
```

### Run the notebook

From the repo root:

```bash
jupyter lab
```

Then open `lab1/lab1.ipynb`.

## Notes

- The repository is organized by lab folders (`lab1/`, `lab2/`, ...).
- If you add more labs, keep each lab self-contained (notebook + `data/` folder if needed).
