# Python Pandas Data Cleaning

This repository showcases a data cleaning and exploratory analysis
workflow using Python and Pandas applied to datasets related to
a company in Colombia. It contains Jupyter notebooks that walk through the process of
importing, cleaning, transforming, and analyzing raw data to produce
structured and analysis-ready datasets.

------------------------------------------------------------------------

## 📁 Repository Structure

    ├── Colombia.ipynb            # Initial data cleaning and analysis notebook
    ├── Colombia_Analisis.ipynb   # Follow-up analysis and visualization
    ├── .gitignore
    └── README.md

-   **Colombia.ipynb**\
    Contains the first stage of the data cleaning workflow --- loading
    raw datasets, inspecting structure, handling missing values,
    standardizing variables, and preparing data for further analysis.

-   **Colombia_Analisis.ipynb**\
    Contains deeper exploratory analysis and visualization based on the
    cleaned dataset.

------------------------------------------------------------------------

## 📌 Project Objective

The objective of this repository is to demonstrate a complete data
cleaning pipeline using Python and the Pandas library, including:

-   Loading raw datasets into DataFrames
-   Inspecting structure and data quality
-   Cleaning and transforming variables
-   Handling missing values and duplicate records\
-   Generating summary statistics\
-   Preparing clean datasets ready for modeling or reporting

The notebooks document a structured workflow for practical data
preprocessing in Python.

------------------------------------------------------------------------

## 🧠 Workflow Overview

### 1️⃣ Data Import & Inspection

-   Load data into Pandas DataFrames
-   Review column types and structure
-   Preview and assess data consistency

### 2️⃣ Data Cleaning

-   Standardize column names
-   Convert data types (numeric, datetime, categorical)
-   Handle missing values (`dropna`, `fillna`)
-   Remove duplicates

### 3️⃣ Feature Engineering

-   Create derived variables\
-   Reformat and normalize string and numeric fields

### 4️⃣ Exploratory Data Analysis

-   Summary statistics (`describe()`, `value_counts()`)
-   Distribution analysis
-   Basic visualizations

------------------------------------------------------------------------

## 📦 Requirements

Python 3.x

Recommended libraries:

``` bash
pip install pandas numpy matplotlib seaborn jupyter
```

------------------------------------------------------------------------

## 🔁 Reproducibility

To reproduce the analysis:

1.  Clone the repository.
2.  Open the notebooks in Jupyter Notebook or JupyterLab.
3.  Run each notebook cell sequentially to follow the data cleaning and
    analysis workflow.

------------------------------------------------------------------------

## 📝 License

This repository, its code, analysis logic, and all associated materials
are proprietary and confidential to Econometria S.A. No usage, sharing,
redistribution, or modification is permitted without explicit written
authorization.

See LICENSE for full terms.

**Contact for Licensing or Permission Requests:**\
Email: jj.rincon@hotmail.com
