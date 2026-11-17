# Human Activity Recognition Using Smartphones (21CSC305P Machine Learning)

Everything is in `HAR_Classification_Project.ipynb` (Review 1: statistics, Review 2: from-scratch models, Review 3: ensembles and HMM). Saved outputs are included, so it can be read without running.

## Data
- `train.csv`, `test.csv` (in this repo): UCI HAR feature tables, used by every section.

## Extra datasets needed only to re-run §10.2 and §11
These are too large for the repo (328 MB and 241 MB). Download them and place them **next to the repo folder** (the notebook reads `../`):

| Folder (sibling of the repo) | Source |
|---|---|
| `human+activity+recognition+using+smartphones/UCI HAR Dataset/` | UCI: Human Activity Recognition Using Smartphones |
| `smartphone+based+recognition+of+human+activities+and+postural+transitions/` | UCI: Smartphone-Based Recognition of Human Activities and Postural Transitions (HAPT) |

All other sections run with `train.csv` and `test.csv` alone.

## Run
Python 3 with `numpy pandas matplotlib seaborn scikit-learn jupyter`, then run all cells.
