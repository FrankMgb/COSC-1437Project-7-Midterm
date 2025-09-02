# Data Science Approaches to Analyzing and Elucidating Factors Associated with Depression

A reproducible, education-focused analysis that explores factors associated with self‑reported depression using Python. This project demonstrates clean data ingestion, quick exploratory analysis, and clear visualizations that can be re-run end-to-end.


## Repository structure

- `workshop_1.ipynb` — Python and pandas warm‑up; basic counts/percentages
- `depression_case_study.ipynb` — Main case study: data download, prevalence estimation, symptom analysis, visualizations
- `workshop_statistics.ipynb` — Intro statistics (distributions, summaries)
- `Data_handling_patterns.ipynb` — Data handling patterns (loading, cleaning)
- `Extended_analysis_patterns.ipynb` — Extended analysis patterns
- `6_Visualization_plots.ipynb` — Visualization workshop (matplotlib/seaborn)
- `depression_data.csv` — Dataset (downloaded in notebooks or kept locally for offline runs)



## Reproducible workflow

1) Open `2_depression_case_study.ipynb` and Run All.
2) Verify quick integrity checks (row counts, required columns).
3) Review outputs:
   - Prevalence (e.g., ~50.3% vs 49.7% split in the sample)
   - Symptom distributions across selected statements
   - Horizontal bar plots and percentage charts
4) Explore `6_workshop_plots.ipynb` for additional visuals.

Tips
- If you re-run multiple times, clear outputs between runs to keep diffs small.
- Keep the CSV local if your environment blocks outbound downloads.


## What this repo demonstrates

- Programmatic ingestion with `gdown` for simple, repeatable data pulls
- Clean pandas patterns for counts, percentages, and column access
- Matplotlib/seaborn plots suitable for quick reporting
- Notebook organization that separates ingest, profile, and visualize phases


## Suggested extensions (good first issues)

- Add a light data dictionary to document columns
- Add a baseline logistic regression with a proper train/validation split
- Parameterize plots into small reusable functions
- Build a simple test that validates expected columns and value ranges before analysis


## Operational notes

- Environment: created via `uv venv` to avoid global Python mutations
- Reproducibility: notebooks run top‑to‑bottom with no hidden state; use the registered kernel
- Performance: dataset is small enough for laptop workflows; no special hardware needed


## Contributing

- Use feature branches and small, focused pull requests
- Keep notebooks clean: prefer clear headings, minimal side effects, and re-runnable cells
- For new dependencies, document the reason and update the Quick start section

