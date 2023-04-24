# IS 327 Final Project
This is the repository for the final project of IS327: Concepts of Machine Learning (SP23). The subject is NBA Player and Salary Data.

Submitted PDF documents (proposal, report) are included.

## Dataset
The `/data` directory contains the original dataset CSVs, cleaning script, and dataset used for analysis.

The dataset to be used for analysis is `cleaned2021-2022.csv`. Cleaning was done to only consider players in the 2021-2022 (most recent) NBA season

Credits to https://www.kaggle.com/datasets/loganlauton/nba-players-and-team-data?select=NBA+Player+Stats%281950+-+2022%29.csv for the original data CSVs.

## Methodology and Results

Basic `sk-learn` ML models were trained and fit via `/notebooks/ml.ipynb`.

Results in the form of evaluative metrics (coefficient of determination, silhouette score) are in the same notebook.

Various scatterplots and supporting visuals can be found in `/visualizations`. They are all explained by the `report.pdf`. 
