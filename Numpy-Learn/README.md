# NumPy (data manipulation)

This folder contains practice notebooks for learning **NumPy** for numerical computing and array-based data manipulation.

If you are viewing this inside the full repo, start from the repo root README for cloning instructions.

## Contents

Notebook sequence:

- `phase1.ipynb` — fundamentals (arrays, dtypes, indexing/slicing)
- `phase2.ipynb` — vectorized operations, broadcasting, math functions
- `phase3.ipynb` — reshaping, aggregation, boolean masking, basic linear algebra patterns
- `phase4.ipynb` — mixed practice across topics

Included artifacts:

- `array1.npy`, `array2.npy`, `array3.npy` — sample NumPy arrays used in exercises
- `numpy-logo.npy` — example NumPy binary file

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
python -m pip install numpy jupyter
```

Or from this folder (a dedicated environment for NumPy only):

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install numpy jupyter
```

Launch Jupyter:

```bash
jupyter lab
# or: jupyter notebook
```

## Notes

- Jupyter checkpoint folders (`.ipynb_checkpoints/`) and virtual environments (`.venv/`) should not be committed.
