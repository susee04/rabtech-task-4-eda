# Rabtech Academy — Task 4: Exploratory Data Analysis & Statistical Insights

## Dataset
Cleaned Global Superstore transaction-line dataset from Task 3 (`data/clean_dataset.csv`), with 51,290 rows and 31 columns.

## Deliverable
- `EDA_Statistical_Insights.ipynb` — descriptive statistics, histograms, box plots, IQR outlier summary, correlation heatmap, multivariate charts, three business hypothesis tests, and five written findings.
- `data/clean_dataset.csv` — input dataset used by the notebook.

## Run
Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```
Open `EDA_Statistical_Insights.ipynb` in Jupyter Notebook/JupyterLab or Google Colab. Keep `clean_dataset.csv` in the `data/` folder and run all cells from top to bottom.

## Interpretation note
The dataset is transaction-line level. Repeated Order IDs can be valid because one order may contain multiple product lines. Statistical associations do not imply causation.
