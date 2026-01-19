# MLDM

Course labs / materials for Machine Learning & Data Mining (MLDM).

## Contents

- `lab1/`
  - `lab1.ipynb`: Jupyter notebook for Lab 1 — Unsupervised Learning
  - `data/data.csv`: dataset used in Lab 1
- `lab2/`
  - `lab2.ipynb`: Jupyter notebook for Lab 2 — Supervised Learning
  - `data/data.csv`: dataset used in Lab 2

## Getting started

### Prerequisites

- Python 3.10+ (3.14 recommended)
- Jupyter (Notebook or JupyterLab)

### Setup (recommended)

Create a virtual environment and install Jupyter:

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install jupyterlab pandas numpy scikit-learn matplotlib seaborn scipy
```

### Run the notebook

From the repo root:

```bash
jupyter lab
```

Then open the desired lab notebook (`lab1/lab1.ipynb` or `lab2/lab2.ipynb`).
