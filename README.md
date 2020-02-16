- [Boston and Seattle Airbnb Data Analysis](#chicago-airbnb-data-analysis)
  - [Installation](#installation)
  - [Background](#background)
  - [File Descriptions](#file-descriptions)
  - [Results](#results)
  - [Licensing, Authors, Acknowledgements](#licensing-authors-acknowledgements)

<!-- /TOC -->

## Installation

The code was developed using the Anaconda distribution of Python, versions 3.8.1 Python libraries used are `numpy`, `pandas`, `datetime`, `matplotlib`, `seaborn`, `sklearn`, `random`, `re`.

## Background

This analysis focuses on price. The Seattle and Boston Airbnb datasets are from Kaggle. The Seattle dataset has 3818 records and the Boston dataset has 3585 records.

The business questions to be answered are:
1. Is there any trend in Airbnb rental price? How does price compare between Boston and Seattle?
2. Should you become a superhost?
3. What factors affect the Airbnb listing price?

These questions were answered using statistics, regression, and visualization.

## File Descriptions

There are 5 notebooks available here to showcase work related to the above questions.

1. [`01 seasonality.ipynb`](01 seasonality.ipynb): load calendar data and find if there is any trend in Airbnb rental price to answer Q1
2. [`02 dataprep_boston.ipynb`](02 dataprep_boston.ipynb): prepare Boston data, including the handling of , data type conversions, categorical variables and missing data, to answer Q2-Q3
3. [`03 dataprep_seattle.ipynb`](03 dataprep_seattle.ipynb): prepare Seattle data, including the handling of , data type conversions, categorical variables and missing data, to answer Q2-Q3
4. [`04 superhost_vs_regular_host.ipynb`](04 superhost_vs_regular_host.ipynb): compare superhost vs regular host in both Boston and Seattle, to anwer Q2
5. [`05 modeling_boston_seattle.ipynb`](05 modeling_boston_seattle.ipynb): train regression model and use the trained model to answer Q3

Markdown cells in each notebook were used to assist in walking through the thought process for individual steps.

## Results

The main findings of the code can be found at the post available [here](https://medium.com/@ustcdj/wanna-make-more-money-on-airbnb-e7549453d5b0).

## Licensing, Authors, Acknowledgements

Please find the Licensing for the dataset at Kaggle [Boston data](https://www.kaggle.com/airbnb/boston/data) and [Seattle data](https://www.kaggle.com/airbnb/seattle/data). Other than that, feel free to play with the code here.
