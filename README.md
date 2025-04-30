# Research Project: Analysis and Modeling of music bands based on Last.fm, Yandex Music, and Wikipedia data

## Project Description
This project focuses on building a dataset of music groups using data parsing and enrichment from multiple sources. The goal is to analyze patterns in the data and build a machine learning model to predict the number of likes a group might receive on Yandex Music.

## Repository Structure
```text
├── ANDAN_PROJECT.ipynb            # Initial setup and data preparation notebook, including basic scraping and dataset structure.
├── ANDAN_PROJECT_5000_TURBO.ipynb # Large-scale scraping of data for 5,000 bands from external sources.
├── ANDAN_PROJECT_EDA.ipynb        # Exploratory data analysis: visualizations, descriptive statistics, and hypothesis testing.
├── ANDAN_PROJECT_ML.ipynb         # Feature engineering and training machine learning models to predict popularity (likes).
└── saved_data/                    # Intermediate datasets saved during the parsing and preprocessing stages.
```

## Methods & Libraries Used

### 1. Data Collection & Preprocessing
- `requests` / `BeautifulSoup` / `re` – for scraping information from Last.fm and Wikipedia.
- `pandas` / `numpy` – for tabular data manipulation and cleaning.

### 2. Exploratory Data Analysis (EDA)
- `matplotlib` / `seaborn` / `plotly` – for visualizing distributions, trends, and correlations.
- statistical testing – using t-tests, ANOVA, correlation analysis to check hypotheses about genres, popularity, and more.

### 3. Machine Learning
- `scikit-learn` – for preprocessing (encoding, scaling), model selection, training, and evaluation.
- `LinearRegression`, `RandomForestRegressor` – as a models for regression tasks (likes prediction).
- `GridSearchCV`, `Ridge` – for hyperparameter tuning and model validation.
