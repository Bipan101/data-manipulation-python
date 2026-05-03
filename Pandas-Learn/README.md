# Pandas (data manipulation)

This folder contains practice notebooks for learning **Pandas** for working with tabular data using `Series` and `DataFrame` workflows.

If you are viewing this inside the full repo, start from the repo root README for cloning instructions.

## Contents

Notebook sequence:

- `1)Series.ipynb` — building and manipulating `Series`
- `2)DataFrames.ipynb` — DataFrame creation, selection, and common operations
- `3)MissingData.ipynb` — detecting, cleaning, and imputing missing values
- `4)MergingJoiningConcat.ipynb` — combining datasets (merge/join/concat)
- `5)GroupByAggregation.ipynb` — `groupby`, aggregation, and summarization
- `6)PivotTables.ipynb` — pivot tables and reshaping
- `7)Operations.ipynb` — common transformations and utilities
- `8)FeatureExtraction.ipynb` — extracting features from columns
- `9)DataExtraction.ipynb` — pulling structured information from datasets

Datasets used by the notebooks:

- `anime.csv`
- `Countries.csv`

## Getting started

### Requirements

- Python 3.10+ recommended
- Jupyter Notebook or JupyterLab

### Environment setup (recommended)

From the repo root (one environment for everything):

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install pandas numpy jupyter
```

Or from this folder (a dedicated environment for Pandas only):

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install pandas numpy jupyter
```

Launch Jupyter:

```bash
jupyter lab
# or: jupyter notebook
```

## Notes

- This folder currently contains a local `.venv/` and `.ipynb_checkpoints/`. Keep both out of git.
