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
## Project Overview

The dataset contains different physical and quality-related attributes of diamonds, such as:

- Carat (weight)
- Cut
- Color
- Clarity
- Dimensions (x, y, z)
- Depth and Table measurements

The objective of this project was to analyse how these characteristics influence **diamond price variation**.

The analysis focuses primarily on **statistical methods** to understand which factors contribute most significantly to price changes. Special attention was given to diamond dimensions and structural attributes to evaluate their relationship with market value.

## Methodology

The project follows a statistical analysis workflow:

1. Data cleaning and preprocessing
2. Exploratory Data Analysis (EDA)
3. Correlation analysis between price and diamond attributes
4. Hypothesis testing to evaluate factor significance
5. Ordinary Least Squares (OLS) regression modelling using `statsmodels`

The goal was to identify statistically meaningful relationships between diamond properties and pricing behaviour rather than building a complex machine learning prediction system.
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
