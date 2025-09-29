![Links](https://github.com/JanHuberty/Thesis/actions/workflows/links.yml/badge.svg)
![License](https://img.shields.io/github/license/JanHuberty/Thesis)

# Nutrition in Gaming – Survey Analytics (Thesis)

Survey of 200+ gamers to profile nutrition-related behaviours.  
**Stack:** Python (pandas, numpy), scikit-learn (PCA, KMeans), visualization.

## Overview
- Cleaned and validated survey data, handled missingness
- PCA to reduce dimensionality while retaining variance
- KMeans segmentation; profiles visualized (e.g., radar charts)

## Quick Start
```bash
python -m venv .venv
# macOS/Linux:
source .venv/bin/activate
# Windows (PowerShell):
# .\.venv\Scripts\Activate.ps1

pip install -r requirements.txt
jupyter lab   # or: jupyter notebook
Minimal `requirements.txt` (if you don’t have one yet):

*(If you use seaborn/plotly, add them too.)*

## 3.5 Results visuals
1) **Add file → Upload files** → upload to `docs/`:
   - `docs/radar_clusters.png`
   - `docs/dashboard.png`
2) In `README.md` add:
```md
## Results
- PCA retained **X%** of variance in first N components.
- Chosen clusters: **K = …** (via silhouette/inertia).

![Radar clusters](docs/radar_clusters.png)
![Dashboard](docs/dashboard.png)
