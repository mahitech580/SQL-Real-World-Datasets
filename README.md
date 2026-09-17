# SQL-Real-World-Datasets

Real-world datasets for **MySQL practice, database analysis, SQL problem solving, and relational database design**.

This repository contains datasets from two different domains:

* 🛒 **Instacart** — e-commerce and grocery transactions
* 🎬 **MovieLens** — movies, ratings, tags, and recommendation-related data

The goal is to practice SQL on large datasets instead of small tutorial databases.

---

## 📂 Datasets

### 🛒 Instacart Market Basket Analysis

The Instacart dataset represents grocery shopping activity and contains information about:

* Customers
* Orders
* Products
* Aisles
* Departments
* Products added to orders
* Reordered products

#### Files

```text
instacart/
├── aisles.csv
├── departments.csv
├── orders.csv
├── order_products__prior.csv
├── order_products__train.csv
└── products.csv
```

#### Useful for practicing

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

### 🎬 MovieLens

MovieLens is a large movie-rating dataset from **GroupLens Research**.

The Full dataset contains approximately:

* **33 million ratings**
* **2 million tag applications**
* **86,000 movies**
* **331,000 users**
* **14 million genome relevance scores**
* **1,100 tags**

#### Dataset files

```text
movielens/
├── movies.csv
├── ratings.csv
├── tags.csv
├── links.csv
├── genome-scores.csv
├── genome-tags.csv
└── README.txt
```

#### Useful for practicing

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

> **MovieLens note:** The raw MovieLens files are downloaded directly from GroupLens. This repository provides the SQL practice structure and documentation rather than redistributing the raw MovieLens dataset.

Official source:
https://grouplens.org/datasets/movielens/

---

## 🗄️ MySQL Databases

The datasets are designed to be imported into MySQL 8.0+.

```text
MySQL
├── instacart_db
└── movielens_db
```

---

## 🧠 SQL Practice Levels

The datasets will be used progressively:

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

Examples include:

* Most frequently ordered products
* Most active customers
* Reorder rates
* Popular products by department
* Average order size
* Customer purchasing behavior
* Highest-rated movies
* Most-rated movies
* Ratings by genre
* User activity analysis
* Movie ranking by genre
* Recommendation-style queries

---

## 🛠️ Technology

* MySQL 8.0+
* SQL
* Git
* Git LFS
* CSV datasets

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
├── movielens/
│   ├── README.md
│   ├── schema.sql
│   ├── import.sql
│   └── queries/
│
├── .gitattributes
└── README.md
```

---

## 🎯 Project Goal

The purpose of this repository is to build practical SQL skills using **large, realistic datasets**.

Instead of solving only small SQL exercises, the goal is to work with millions of records and understand how SQL is used for:

* Data analysis
* Reporting
* Business intelligence
* Transaction analysis
* Customer analytics
* Product analytics
* Recommendation systems
* Database querying

---

## 📌 Dataset Sources

### Instacart

Instacart Market Basket Analysis dataset.

### MovieLens

GroupLens Research — MovieLens.

Official website:

https://grouplens.org/datasets/movielens/

Please follow the original dataset providers' licensing and usage terms when downloading, using, or redistributing datasets.

---

## 🚀 Future Additions

This repository will be expanded with:

* MySQL table schemas
* CSV import scripts
* SQL practice problems
* Beginner → advanced queries
* Real-world business questions
* Query optimization examples
* Indexing examples
* Window-function exercises
* CTE exercises
* Interview-style SQL problems
