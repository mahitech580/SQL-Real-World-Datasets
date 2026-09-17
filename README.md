# SQL-Real-World-Datasets

Real-world datasets for **MySQL practice, SQL problem solving, database analysis, and relational database design**.

This repository contains large datasets from two different domains:

* 🛒 **Instacart** — e-commerce and grocery transactions
* 🎬 **MovieLens** — movies, ratings, tags, and movie-related metadata

The goal is to practice SQL using large, realistic datasets instead of small tutorial databases.

---

## 📂 Datasets

## 🛒 Instacart Market Basket Analysis

The Instacart dataset contains grocery shopping and ordering data, including:

* Orders
* Products
* Aisles
* Departments
* Product-order relationships
* Reordered products

### Files

```text
instacart/
├── aisles.csv
├── departments.csv
├── orders.csv
├── order_products__prior.csv
├── order_products__train.csv
└── products.csv
```

### Useful for practicing

* `SELECT`
* `WHERE`
* `ORDER BY`
* `GROUP BY`
* `HAVING`
* `JOIN`
* Subqueries
* CTEs
* Window functions
* Aggregations
* Customer analysis
* Product analysis
* Order analysis
* Reorder analysis
* E-commerce analytics

---

## 🎬 MovieLens

MovieLens is a large movie-rating dataset from **GroupLens Research**.

The Full dataset contains approximately:

* **33 million ratings**
* **2 million tag applications**
* **86,000 movies**
* **331,000 users**
* **14 million genome relevance scores**
* **1,100 tags**

### Files

```text
ml-latest/
├── movies.csv
├── ratings.csv
├── tags.csv
├── links.csv
├── genome-scores.csv
├── genome-tags.csv
└── README.txt
```

### Useful for practicing

* Multi-table `JOIN`s
* Aggregation
* Rating analysis
* User analysis
* Movie analysis
* Genre analysis
* Ranking
* Window functions
* Subqueries
* CTEs
* Recommendation-style SQL
* Large-scale analytical queries

### Source

MovieLens is provided by **GroupLens Research**.

Official source:

https://grouplens.org/datasets/movielens/

Please review and follow the original dataset provider's terms and licensing requirements when using or redistributing the dataset.

---

## 🗄️ MySQL Databases

The datasets are intended for use with **MySQL 8.0+**.

```text
MySQL
├── instacart_db
└── movielens_db
```

---

## 🧠 SQL Practice Levels

### Level 1 — Basics

```sql
SELECT
WHERE
ORDER BY
LIMIT
DISTINCT
LIKE
BETWEEN
IN
```

### Level 2 — Aggregation

```sql
COUNT()
SUM()
AVG()
MIN()
MAX()
GROUP BY
HAVING
```

### Level 3 — Joins

```sql
INNER JOIN
LEFT JOIN
RIGHT JOIN
SELF JOIN
```

### Level 4 — Intermediate SQL

```sql
CASE
Subqueries
Correlated subqueries
UNION
EXISTS
```

### Level 5 — Advanced SQL

```sql
CTEs
Window functions
RANK()
DENSE_RANK()
ROW_NUMBER()
LAG()
LEAD()
Running totals
Partitioned analysis
```

### Level 6 — Real-World Analysis

Example problems include:

* Most frequently ordered products
* Most active customers
* Product reorder rates
* Popular products by department
* Average order size
* Customer purchasing behavior
* Highest-rated movies
* Most-rated movies
* Ratings by genre
* User activity analysis
* Movie rankings by genre
* Recommendation-style queries

---

## 🛠️ Technology

* MySQL 8.0+
* SQL
* Git
* Git LFS
* CSV

---

## 📁 Repository Structure

```text
SQL-Real-World-Datasets/
│
├── instacart/
│   ├── aisles.csv
│   ├── departments.csv
│   ├── orders.csv
│   ├── order_products__prior.csv
│   ├── order_products__train.csv
│   └── products.csv
│
├── ml-latest/
│   ├── movies.csv
│   ├── ratings.csv
│   ├── tags.csv
│   ├── links.csv
│   ├── genome-scores.csv
│   ├── genome-tags.csv
│   └── README.txt
│
├── .gitattributes
└── README.md
```

Large CSV files are managed using **Git LFS**.

---

## 🎯 Project Goal

The purpose of this repository is to develop practical SQL skills by working with **millions of real-world records**.

The datasets can be used for:

* Data analysis
* Reporting
* Business intelligence
* Transaction analysis
* Customer analytics
* Product analytics
* Movie and rating analytics
* Recommendation-style analysis
* Database querying
* SQL interview preparation

---

## 📌 Dataset Sources

### Instacart

Instacart Market Basket Analysis dataset.

### MovieLens

GroupLens Research — MovieLens.

Official website:

https://grouplens.org/datasets/movielens/

Please follow the original dataset providers' terms and licensing requirements when downloading, using, or redistributing datasets.

---

## 🚀 Future Additions

This repository will be expanded with:

* MySQL table schemas
* CSV import scripts
* SQL practice problems
* Beginner-to-advanced SQL queries
* Real-world business questions
* Query optimization examples
* Indexing examples
* Window-function exercises
* CTE exercises
* SQL interview problems
* Database design examples
