# Data Analysis and Financial Modelling Projects

A collection of academic projects using R and Python for statistical modelling, financial data analysis, data retrieval, and visualisation.

## Projects

### Spotify Track Popularity Analysis

**Language:** R  
**File:** [`Spotify-analysis.Rmd`](./Spotify-analysis.Rmd)

A group project exploring the relationship between Spotify track features and popularity. The analysis includes data cleaning, exploratory analysis, regression and classification models, and visualisations.

Methods used include linear and logistic regression, decision trees, bagging, random forests, ROC/AUC analysis, and word clouds.

**My contribution:** Conducted statistical analysis in R to investigate factors associated with Spotify song popularity, implementing and comparing regression models, regression trees, Bagging, and Random Forest.

The project requires a `dataset.csv` file, which is not included in this repository.

### Stock Portfolio Risk Modelling

**Language:** R  
**File:** [`risk mgt project.Rmd`](./risk%20mgt%20project.Rmd)

An analysis of six US stocks using Yahoo Finance price data from 2010–2019. The project calculates log returns, applies principal component analysis, fits GARCH(1,1) models to selected factors, and estimates volatility and 5% Value at Risk for an equally weighted portfolio.

The file also includes an attempted rolling-window VaR backtest. The source records an unresolved issue with the rolling calculation, so those backtesting results are not presented as verified.

### Understanding What Affects the Total Amount Owed

**Language:** R  
**File:** [`Loan-analysis.Rmd`](./Loan-analysis.Rmd)

An individual project exploring factors associated with the total amount owed, using a dataset provided by the course instructor. The analysis includes data cleaning, categorical variable recoding, missing-data handling, multicollinearity and outlier checks, and logistic regression using different outcome thresholds.

The dataset is not included in this repository. Model assessment is conducted on the analysis data, without a separate holdout set.

### Financial Data Retrieval and Visualisation

**Language:** Python  
**File:** [`Data Retrieval.ipynb`](./Data%20Retrieval.ipynb)

A notebook that retrieves and visualises financial data from Yahoo Finance, Tushare, and FRED. It explores historical prices for US and Chinese stocks alongside selected US macroeconomic indicators, using pandas and Plotly.

Tushare and FRED access require credentials supplied by the user. No API keys are included in this repository. Saved results reflect the data available when the notebook was last run; rerunning it may produce different results.

### Stock-Index Correlation Analysis

**Language:** Python  
**File:** [`Correlation Task.ipynb`](./Correlation%20Task.ipynb)

A notebook that retrieves historical price data for the Dow Jones Industrial Average, Nasdaq-100, and their current constituents, then calculates price correlations and visualises them with heatmaps.

The analysis uses current index constituent lists and price levels, so results may change over time and should not be interpreted as correlations between stock returns.

## Tools and Libraries

- **R:** tidyverse, quantmod, PerformanceAnalytics, rugarch, randomForest, tree, ROCR, car, and ggplot2
- **Python:** pandas, NumPy, yfinance, Tushare, fredapi, Plotly, matplotlib, and seaborn

## Data and Reproducibility

- Some projects require separate datasets that are not included here. Check the relevant course or data-provider terms before sharing or downloading data.
- The loan-analysis dataset was provided by the course instructor and is not included in this repository.
- API credentials are not included. Anyone running the data retrieval notebook must provide their own authorised credentials locally.
- Financial data and index constituents can change over time, so results may differ when the notebooks are run again.
- These projects were completed for academic analysis and are not production software.

## Running the Projects

Open `.Rmd` files in RStudio or another R Markdown-compatible environment. Open `.ipynb` files in Jupyter Notebook or JupyterLab.

Install the libraries listed in each project before running it. Some projects also require external data files or API credentials, as described above.
