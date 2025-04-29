# EDA with BigQuery and Colab Enterprise on Vertex AI

[![BigQuery](https://img.shields.io/badge/BigQuery-blue?logo=google-cloud-platform&logoColor=white)](https://cloud.google.com/bigquery)
[![Colab Enterprise](https://img.shields.io/badge/Colab%20Enterprise-purple?logo=google-colab&logoColor=white)](https://cloud.google.com/vertex-ai/docs/workbench/colab-enterprise/overview)
[![Vertex AI](https://img.shields.io/badge/Vertex%20AI-red?logo=google-cloud&logoColor=white)](https://cloud.google.com/vertex-ai)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-4C766A?logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)

This repository documents one of my exploratory data analysis (EDA) practice as part of the Machine Learning Engineer Learning Path on Google Cloud. It showcases the process I followed to analyze a dataset stored in Google BigQuery using the collaborative environment of Colab Enterprise. This involved querying data, performing statistical analysis with Pandas and visualizing patterns using Seaborn.

## This project covers the following steps:

1.  **Environment Setup:** Configuring the Google Cloud environment and enabling the Vertex AI API.
2.  **Colab Enterprise Notebook Creation:** Setting up the interactive workspace for data analysis.
3.  **Basic Code Execution:** Running introductory Python code to get familiar with Colab Enterprise.
4.  **Version History Exploration:** Exploring the version tracking features within the notebook.
5.  **Data Loading and Exploration:**
    * Importing necessary Python libraries (Seaborn, Pandas, NumPy, BigQuery).
    * Establishing a connection to BigQuery using the BigQuery client.
    * Executing SQL queries to retrieve data from a BigQuery dataset.
    * Loading the query results into a Pandas DataFrame.
    * Examining the initial rows (`df.head()`) and getting a summary (`df.info()`).
    * Generating descriptive statistics of the dataset (`df.describe()`).
6.  **Data Visualization:**
    * Creating a correlation heatmap to visualize relationships between numerical features using Seaborn.
7.  **Specific Data Selection:**
    * Writing and executing SQL queries to select specific columns from the BigQuery dataset.
    * Displaying the first few rows of the resulting DataFrame.


## How to Run

To reproduce this, you would need:

1.  A Google Cloud Platform account.
2.  Access to BigQuery.
3.  The `bigquery-public-data.catalonian_mobile_coverage_eu.mobile_data_2015_2017` public dataset in BigQuery.
4.  Access to Vertex AI and the Colab Enterprise environment.
