# ARTI 303 — Lab Assignment 1: Pandas vs. Polars

**Course:** ARTI 303 — Programming for AI  
**Group:** Group 7  

---

## 📌 Project Overview
This project benchmarks performance between **Pandas** and **Polars** across seven core tabular operations on a large dataset (>100,000 rows):
1. **Reading the file**
2. **Filtering rows**
3. **Creating new columns**
4. **Group by and aggregations**
5. **Sorting and selecting top N**
6. **Chained Lazy execution pipeline**
7. **Joining two tables**

---

## 📊 Dataset Information
- **Dataset:** Spotify Tracks Dataset (114,000 rows, 21 columns)
- **Source:** Public CSV dataset
- *Note:* The dataset file (`dataset.csv`) is excluded from version control via `.gitignore` due to file size constraints.

---

## ⚙️ Requirements & Setup
To reproduce the environment and benchmark results, install dependencies using:

```bash
pip install -r requirements.txt