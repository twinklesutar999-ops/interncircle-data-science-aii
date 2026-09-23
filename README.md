# InternCircle Data Science & AI — Task 1: Titanic EDA

**Intern:** Tina Devi  
**InternCircle ID:** IC-2026-1286  
**Track:** Data Science & AI  
**Task:** Exploratory Data Analysis (EDA) on the Titanic Dataset

## Project objective

This project performs exploratory data analysis on the classic Titanic passenger dataset using **Python and Pandas**.

The analysis covers:
- `head()`, `info()`, and `describe()`
- Dataset shape and column inspection
- Missing-value analysis
- Duplicate-row checking
- Missing-value treatment
- Survival-rate calculations
- Grouping and aggregation
- Survival analysis by gender and passenger class
- Age-group and family-size analysis
- Basic Matplotlib visualizations
- Written conclusions and statistical insights

## Repository structure

```text
interncircle-data-science-ai/
│
├── data/
│   └── titanic.csv
│
├── notebooks/
│   └── Titanic_EDA_Task_1.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Dataset

The included `data/titanic.csv` contains **891 passenger records and 12 columns**, including:
`PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, and `Embarked`.

## How to run

### Option 1 — Google Colab
1. Upload this repository to GitHub.
2. Open `notebooks/Titanic_EDA_Task_1.ipynb` in Google Colab.
3. Run all cells from top to bottom.

### Option 2 — Local Jupyter Notebook

```bash
pip install -r requirements.txt
jupyter notebook
```

Then open:

```text
notebooks/Titanic_EDA_Task_1.ipynb
```

## Main cleaning decisions

- Missing `Age` values → replaced with the median age.
- Missing `Embarked` values → replaced with the mode.
- Missing `Cabin` values → labelled as `Unknown`.
- Exact duplicate rows → checked and removed if present.

## Important findings

The notebook calculates the exact survival rates directly from the dataset. It examines:
- overall survival;
- survival by gender;
- survival by passenger class;
- survival by age group;
- survival by family size;
- average age, fare, and family size by survival outcome.

## Skills demonstrated

**Python • Pandas • NumPy • Matplotlib • Exploratory Data Analysis • Data Cleaning • Data Aggregation • Statistical Interpretation**

---

### Internship submission

This repository is prepared for **InternCircle Data Science & AI — Task 1: Exploratory Data Analysis (EDA) on Titanic**.
