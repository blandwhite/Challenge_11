# Module 11 Challenge: Time Series Analysis
UNCC Online FinTech Bootcamp Module 11 Challenge due by 11:59pm 2/20/2022

![](Images/time_analysis_title-banner.jpeg)

image from [www.analyticssteps.com](https://www.analyticssteps.com/blogs/introduction-time-series-analysis-time-series-forecasting-machine-learning-methods-models)

---

## Background

With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. We've been tasked with analyzing the company's financial and user data in clever ways to make the company grow. So, we want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

---

## What's Being Created

In a bid to drive revenue, we’ll produce a Jupyter notebook that contains our data preparation, analysis, and visualizations for all the time series data that the company needs to understand. We’ll use text and comments to document our findings, and we’ll answer the questions related to our findings. Specifically, this file should contain the following:

 - Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.

 - An evaluation of how the company’s stock price correlates to its Google Search traffic.

 - A Prophet forecast model that can predict hourly user search traffic.

 - A plot of a forecast for the company’s future revenue.

---

## Technologies

This application is written in Python 3.7 using JupyterLab version 3.0.14.

Python libraries used:

 - [Pandas](https://pandas.pydata.org/pandas-docs/stable/) - *an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.*
 - [Pathlib](https://docs.python.org/3.7/library/pathlib.html) - *a library that enables consistent input and output of files from the main app.*
 - [hvPlot](https://hvplot.holoviz.org/user_guide/Introduction.html) - *a high-level plotting API for the PyData ecosystem built on HoloViews.*
 - [scikit-learn](https://scikit-learn.org/stable/user_guide.html) - *an open source machine learning library that supports supervised and unsupervised learning.*
 - [plotly](https://plotly.com/python/) - *an interactive, open-source, and browser-based graphing library for Python.*
 - [seaborn](https://seaborn.pydata.org/installing.html) - *a visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.*
 - [prophet](https://facebook.github.io/prophet/) - *a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects*


### Installation Guide

prior to running these libraries, install them from the command line:
  - pandas: `conda install pandas` or `pip install pandas`  
  - pathlib: `pip install pathlib`
  - hvPlot: `conda install -c pyviz hvplot` or `pip install hvplot`
  - sklearn: `pip install-U scikit-learn` - included in conda
  - plotly: `pip install plotly==5.5.0`
  - seaborn: `pip install seaborn` or `conda install seaborn`
  - prophet: `pip install prophet`
  
---

## Usage

 - Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.

 - An evaluation of how the company’s stock price correlates to its Google Search traffic.

 - A Prophet forecast model that can predict hourly user search traffic.

 - A plot of a forecast for the company’s future revenue.

---

## Contributors

Geoff Tarleton - jobeycat@protonmail.com

adapted from Starter Code supplied by UNCC FinTech Online Bootcamp by Trilogy Educational Services, a 2U, Inc. brand.

---

## License

[MIT](LICENSE)