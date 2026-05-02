# Mammographic Density Prediction

This repository contains a Jupyter Notebook–based project focused on **predicting mammographic (breast) density**, along with supporting analyses and outputs.

## Repository Contents

- `coursework.ipynb` — Main notebook for data loading, preprocessing, modeling, and evaluation.
- `Model_Inspection/` — Model inspection/interpretability and related exploration.
- `Subgroup_Analysis/` — Analysis of model performance across subgroups.
- `output/` — Saved figures, tables, and/or exported results.
- `report.pdf` — Project report describing the approach and results.
- `requirements.txt` — Python dependencies.

## Getting Started

### 1) Clone the repository
```bash
git clone https://github.com/fedmand/Mammographic_Density_Prediction.git
cd Mammographic_Density_Prediction
```

### 2) Create an environment (recommended)
Using `venv`:
```bash
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
# .venv\Scripts\activate    # Windows
```

### 3) Install dependencies
```bash
pip install -r requirements.txt
```

### 4) Run the notebook
```bash
jupyter notebook coursework.ipynb
```
Or with JupyterLab:
```bash
jupyter lab
```

## How to Navigate the Project

1. Start with **`report.pdf`** for a full write-up of the problem, methods, and results.
2. Open **`coursework.ipynb`** to reproduce the workflow end-to-end.
3. Review:
   - `Model_Inspection/` for deeper investigation into model behavior
   - `Subgroup_Analysis/` for stratified performance and fairness-related checks
4. Check `output/` for saved artifacts produced by the notebook(s).

## Notes

- If the notebook expects local data files that are not included in the repository, you’ll need to place them in the expected path(s) used inside `coursework.ipynb`.
- Reproducibility will depend on matching package versions from `requirements.txt`.
