# InternCircle Data Science & AI Internship

This repository contains my completed InternCircle Data Science & AI internship tasks, including exploratory data analysis, data visualization, and customer sales/churn analysis.

## Tasks Completed

### Task 1 — Exploratory Data Analysis (EDA) on Titanic

Notebook:
`notebooks/Titanic_EDA_Task_1.ipynb`

Main work:
- Dataset inspection using `head()`, `info()`, and `describe()`
- Shape and column analysis
- Missing-value analysis and treatment
- Duplicate-row checking
- Survival-rate calculations
- Grouping and aggregation
- Survival analysis by gender and passenger class
- Age-group and family-size analysis
- Basic visualizations
- Written conclusions and statistical insights

Dataset:
`data/titanic.csv`

### Task 2 — Data Visualization with Matplotlib & Seaborn

Notebook:
`notebooks/Titanic_Visualization_Task_2.ipynb`

Main work:
- Histograms and distribution analysis
- Box plots
- Correlation matrix / heatmap
- Count plots
- Matplotlib and Seaborn visualizations
- Interpretation of charts and relationships in the Titanic dataset

### Task 3 — Customer Churn / Sales Trend Analysis

Notebook:
`notebooks/Customer_Churn_Sales_Analysis.ipynb`

Main work:
- End-to-end e-commerce sales analysis
- Data cleaning and validation
- Date extraction and feature engineering
- Revenue calculation
- Monthly revenue trends and month-over-month growth
- Pivot-table analysis
- Top products by revenue
- RFM-style customer segmentation
- Customer inactivity analysis as a churn-risk proxy
- Revenue analysis by customer segment and country
- Actionable business recommendations

Dataset:
UCI Machine Learning Repository — Online Retail Dataset.

The notebook loads the dataset programmatically with `ucimlrepo`, so the large raw Excel file does not need to be stored inside this GitHub repository.

> Note: The Online Retail dataset does not contain a direct churn label. Task 3 therefore uses customer inactivity (recency greater than 90 days) as an analytical churn-risk proxy rather than claiming a true churn prediction model.

## Repository Structure

```text
interncircle-data-science-aii/
│
├── data/
│   └── titanic.csv
│
├── notebooks/
│   ├── Titanic_EDA_Task_1.ipynb
│   ├── Titanic_Visualization_Task_2.ipynb
│   └── Customer_Churn_Sales_Analysis.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- UCI ML Repository (`ucimlrepo`)
- OpenPyXL

## How to Run

### Google Colab

1. Open the required notebook in Google Colab.
2. For Task 1 and Task 2, make sure the repository data path is available when running the notebook.
3. For Task 3, install the required packages if needed:

```python
!pip install -r requirements.txt
```

or:

```python
!pip install ucimlrepo openpyxl
```

4. Run the notebook cells from top to bottom.

### Local Jupyter

Install the dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook
```

Then open the required notebook from the `notebooks/` folder.

## Dataset Sources

### Titanic Dataset
The Titanic dataset is stored locally in `data/titanic.csv` and is used by Tasks 1 and 2.

### Online Retail Dataset
Task 3 uses the UCI Machine Learning Repository Online Retail dataset:

Daqing Chen. (2015). *Online Retail*. UCI Machine Learning Repository.  
DOI: https://doi.org/10.24432/C5BW33

The dataset is retrieved through the `ucimlrepo` Python package.

## Skills Demonstrated

Python • Pandas • NumPy • Matplotlib • Seaborn • Data Cleaning • Exploratory Data Analysis • Data Visualization • Feature Engineering • Pivot Tables • Trend Analysis • Customer Segmentation • RFM Analysis • Business Intelligence • Analytical Problem Solving
