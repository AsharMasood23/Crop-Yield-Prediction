# Crop Yield Analysis & Visualization

Exploratory data analysis of FAO crop yield data (1961–2016) for 10 major crops. Includes data cleaning, visualization, and trend analysis using Python (Pandas, Matplotlib, Seaborn) to uncover global agricultural patterns and support food security insights.

## How to run
1. Create a virtual environment and install dependencies:
   python -m venv .venv
   source .venv/bin/activate   # Windows: .venv\Scripts\activate
   pip install -r requirements.txt

2. Open the notebook:
   jupyter notebook crop-yield-eda-viz.ipynb

## Data
- `data/sample.csv` includes a tiny sample so the notebook can run.
- Do **not** add large/full raw datasets to the repo. Instead, place the full dataset at `data/full_dataset.csv` or follow the notebook's data-loading instructions.

## Files included
- `crop-yield-eda-viz.ipynb` (your main notebook) — add this file to the repo root.
- `requirements.txt` — Python dependencies.
- `.gitignore` — ignores virtual env, data folder, and notebook checkpoints.
- `data/sample.csv` — a small sample dataset for quick testing.
- `LICENSE` — MIT license.

## License
This project is available under the MIT License. See LICENSE file.
