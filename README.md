# AI for Wearable Emergency Detection — Code Repository

## Quick Start
```bash
pip install -r requirements.txt
python src/baseline_random_forest.py --output_dir figures/
python src/shap_explain.py --output figures/shap_summary_plot.png
```

Use your dataset (optional):
```bash
python src/baseline_random_forest.py --data data/WISDM_preprocessed.csv --output_dir figures/
python src/shap_explain.py --data data/WISDM_preprocessed.csv --output figures/shap_summary_plot.png
```

## Structure
- src/: scripts
- notebooks/: Jupyter notebook
- figures/: saved images
- data/: place your dataset here
- requirements.txt, environment.yml, .gitignore
