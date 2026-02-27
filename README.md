# Diamonds — EDA & Statistical Analysis (Jupyter Notebook)

This repository contains an exploratory data analysis (EDA) and statistical modelling workflow on the classic **diamonds** dataset. The work is presented as a Jupyter Notebook, with an accompanying PDF export of the analysis.

## What’s inside

- **Pre-processing**
  - Load `diamonds.csv`
  - Basic dataset inspection (`head`, `info`, missing values)
  - Remove irrelevant / index-style column(s)
- **EDA (Exploratory Data Analysis)**
  - Visual exploration of relationships (e.g., price vs categorical features)
  - Discussion of the “4Cs” (cut, color, clarity, carat) and how they relate to price
- **Statistical analysis**
  - Hypothesis testing (comparing groups / categorical effects on price)
  - Correlation analysis (e.g., price vs carat)
  - **Linear regression (OLS)** using `statsmodels` to model diamond price

## Repository structure

- `Assesment.ipynb` — main notebook with all code, plots, and explanations
- `Assesment.pdf` — PDF export of the notebook/report
- `diamonds.csv` — dataset used for the analysis

## Requirements

This project uses standard Python data-science libraries:

- Python 3.9+ (recommended)
- pandas
- matplotlib
- statsmodels
- scipy
- jupyter (or JupyterLab)

## Setup

Clone the repo:

```bash
git clone https://github.com/kazx22/Diamonds.git
cd Diamonds

python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

pip install pandas matplotlib statsmodels scipy jupyter

jupyter notebook


## Author

**Kazi Alif**

- GitHub: https://github.com/kazx22
- MSc Computer Science (Distinction) — University of South Wales
- Research Interests: Machine Learning, Data Science, Graph Learning, AI for Healthcare
