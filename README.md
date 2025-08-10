# AI for Wearable Emergency Detection — Code Repository

<!-- Badges -->
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brianhaw/wearables-ai-project/blob/main/notebooks/Final_Wearables_Project.ipynb)
![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Last Commit](https://img.shields.io/github/last-commit/brianhaw/wearables-ai-project)

A compact, reproducible codebase for my MSAI final project.  
It trains a **Random Forest** on wearable sensor features (WISDM-style), evaluates performance, and explains predictions with **SHAP**.  
Runs **end-to-end even without the dataset** (synthetic fallback), so reviewers can execute immediately.

- **Baseline accuracy:** ~92%  
- **Tuned accuracy:** ~94%  
- **Key SHAP insights:** Z-axis std (vertical variability) & Y-axis mean (lateral sway)

---

## Try it in Colab
Click the badge above to open the notebook in Google Colab.  
No dataset required — the notebook generates synthetic data if `data/WISDM_preprocessed.csv` isn’t present.

---

## Quick Start (local)

> Requires Python 3.11+

```bash
# Option A: pip
pip install -r requirements.txt

# Option B: conda
conda env create -f environment.yml
conda activate wearables-ai
