# CS 451: Data Science (University of Alabama)

This repository contains coursework, coding practice sessions, and supplemental materials for **CS 451/551 – Data Science** at **The University of Alabama**.

The goal of this repo is twofold:

1. Serve as an organized workspace for assignments and coding practice throughout the semester
2. Act as a clean, professional reference demonstrating practical data science skills in Python and SQL

---

## Course Information

* **Course:** CS 451/551 – Data Science
* **Institution:** The University of Alabama, Department of Computer Science
* **Instructors:** Dr. Jiaqi Gong, Dr. Xiaoming Guo
* **Teaching Assistant:** Samin Yasar
* **Term:** Spring 2026

The course introduces fundamental concepts and techniques in data science, with an emphasis on mathematical foundations, statistical reasoning, and practical implementation.

Topics include:

* Data preprocessing and cleaning
* Exploratory data analysis
* Feature engineering
* Machine learning models
* Model validation and selection
* Data visualization and storytelling
* Deployment, monitoring, and improvement of data-driven systems

---

## Learning Objectives

By the end of this course, students will be able to:

* Implement the standard data science workflow end-to-end
* Recognize and frame real-world data science problems
* Prepare, clean, and transform raw datasets
* Apply and evaluate machine learning models
* Communicate insights effectively using data
* Deploy and assess data-driven solutions

---

## Repository Structure

```text
CS451-DATA-SCIENCE/
│
├── python/
│   ├── datasets/           # CSV datasets used in practice
│   └── notebooks/          # Python Jupyter notebooks
│       ├── CP1.ipynb
│       ├── CP2.ipynb
│       ├── HW1.ipynb
│       └── ...
│
├── sql/
│   ├── datasets/           # SQL-focused datasets
│   │   ├── employees.csv
│   │   ├── departments.csv
│   │   ├── customers.csv
│   │   └── orders.csv
│   │
│   ├── notebooks/          # SQL Jupyter notebooks
│   │   ├── CPS_SQL_01_Fundamentals.ipynb
│   │   └── CPS_SQL_02_Joins_and_Windows.ipynb
│   │
│   └── practice.duckdb     # DuckDB database used for SQL practice
│
├── final project/           # Coming soon!
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Coding Practice Sessions (CPS)

Coding Practice Sessions are a core component of the course. Each CPS focuses on hands-on problem solving aligned with weekly lecture topics.

This repository includes extended and enriched versions of CPS exercises for additional practice.

### Python Practice

Python-based Coding Practice Sessions focus on strengthening core data science programming skills using industry-standard libraries.

Key skills practiced in recent Python practice sessions:

* Data manipulation with Pandas
* Numerical computation with NumPy
* Handling missing values through median imputation
* Target transformation (e.g. log-transforming)
* Feature scaling via standardization and normalization (`StandardScaler`, `MinMaxScaler`)
* Dimensionality reduction using Principal Component Analysis (PCA)
* Feature selection with Recursive Feature Elimination (RFE)
* Polynommial feature transformation to enhance linear models

### SQL Practice (DuckDB + Jupyter)

SQL practice is implemented using:

* **DuckDB** as an embedded analytical database
* **Jupyter Notebooks** with `jupysql` / `ipython-sql`

Key skills practiced in recent SQL practice sessions:

* SELECT queries and filtering
* Aggregations and GROUP BY
* Handling NULLs and data quality checks
* Sorting and limiting results
* Derived columns and expressions
* Data validation queries

---

## Tools & Technologies

* **Python 3.10+**
* **Pandas & NumPy**
* **Jupyter Notebook**
* **DuckDB** (analytical SQL engine)
* **jupysql / ipython-sql**
* **Matplotlib / Seaborn** 

---

## Environment Setup

Install dependencies using:

```bash
pip install -r requirements.txt
```

The SQL notebooks assume:

* DuckDB database file: `sql/practice.duckdb`
* CSV datasets located in `sql/datasets/`

---

## Purpose of This Repository

In addition to supporting coursework, this repository is structured to:

* Demonstrate practical data science skills
* Showcase clean project organization
* Provide reproducible, well-documented analysis
* Serve as a portfolio artifact for entry-level data-focused roles

---

*CS 451/551 – Data Science | University of Alabama*
