![Links](https://github.com/JanHuberty/Thesis/actions/workflows/links.yml/badge.svg)
![License](https://img.shields.io/github/license/JanHuberty/Thesis)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JanHuberty/Thesis/blob/main/Dissertation_stats%20(3).ipynb)


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
jupyter lab  # or: jupyter notebook

*(If you use seaborn/plotly, make sure they’re listed in `requirements.txt`.)*

---

## Step 3 — Add Results images (nice portfolio touch)

1) Add file → **Upload files** → upload to **`docs/`**:
   - `docs/radar_clusters.png`
   - `docs/dashboard.png`

2) In README, add below Quick Start:
```md
## Results
- PCA retained **X%** variance in first **N** components.
- Clustering: **K = ?** (chosen via silhouette/inertia).

![Radar clusters](docs/radar_clusters.png)
![Dashboard](docs/dashboard.png)
