# Mini-Project 1: From Data Generation to Scientific Analysis

Neuroscience Data Analysis with Python, 2026.

**Team:** Yonatan (project manager), Junia, Yahli
**Due:** 03 December 2026

## Contents

| File | Description |
|------|-------------|
| `Q1_neural_spikes.ipynb` | Q1: simulation and analysis of regular, irregular and bursting spike trains |
| `Q2_laptop_analysis.ipynb` | Q2: exploratory data analysis of the laptop price dataset |
| `AI_USAGE.md` | Documentation of AI assistance and how its output was verified |
| `requirements.txt` | Python packages needed to run the notebooks |
| `figures/` | All figures produced by the notebooks (saved automatically when the notebooks run) |
| `laptop-price-dataset.csv` | Input dataset for Q2, included so the notebook runs as-is |

## How to run

Requires Python 3.10 or newer.

```bash
git clone <repo-url>
cd MiniProject_1
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

Then open each notebook and choose **Kernel → Restart & Run All**.

To run both notebooks from the command line without opening Jupyter:

```bash
jupyter nbconvert --to notebook --execute --inplace Q1_neural_spikes.ipynb
jupyter nbconvert --to notebook --execute --inplace Q2_laptop_analysis.ipynb
```

## Reproducibility

- All randomness in Q1 goes through `numpy.random.default_rng(seed)` with a fixed seed set at the top of the notebook, so every run gives identical results.
- Notebooks use relative paths only. Figures are written to `figures/`, and the dataset is read from the repository root.
- Both notebooks were run end to end in a fresh virtual environment created from `requirements.txt` before submission.

## Summary of findings

<!-- Fill in at the end of the project: 3–5 sentences per question. -->

**Q1:** _to be completed_

**Q2:** _to be completed_
