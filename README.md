<h1 align="center">🍔 Food Delivery Data Analysis</h1>

<p align="center">
  Combining food delivery data from multiple sources and formats into one dataset, then analysing it in Python.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white" alt="Jupyter">
</p>

---

## 🔎 Overview

Real-world business data rarely lives in one place or one format. This project works with food delivery data stored in **three different formats** (CSV, SQL and JSON), brings it together into a single dataset, and analyses it in a Jupyter notebook to understand orders, restaurants and customers.

## 📁 Repository Contents

| File | Description |
|------|-------------|
| [`Food_Delivery_Analysis.ipynb`](Food_Delivery_Analysis.ipynb) | Jupyter notebook with the analysis |
| [`orders.csv`](orders.csv) | Order data (CSV format) |
| [`restaurants.sql`](restaurants.sql) | Restaurant data (SQL format) |
| [`users.json`](users.json) | Customer data (JSON format) |
| [`final_food_delivery_dataset.csv`](final_food_delivery_dataset.csv) | The final dataset used for analysis |

## 🧭 Approach

```
Orders (CSV) + Restaurants (SQL) + Users (JSON) → Combine → Clean → Analyse → Insights
```

1. **Load** data from CSV, SQL and JSON sources
2. **Combine** the sources into one dataset
3. **Clean** the data (missing values, duplicates, inconsistencies)
4. **Analyse and visualise** the data in the notebook
5. **Draw insights** about orders, restaurants and customers

## 🏁 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/janvi-malve02/food-delivery-data-analysis.git
cd food-delivery-data-analysis

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch Jupyter and open the notebook
jupyter notebook Food_Delivery_Analysis.ipynb
```

## ⚠️ Limitations

- The analysis reflects only the data in this repository and may not represent the wider food delivery market
- Combining data from different sources can introduce inconsistencies that need careful cleaning
- Findings are descriptive and do not prove cause and effect

## 🚀 Future Work

- [ ] Build an interactive dashboard (Power BI, Tableau or Streamlit)
- [ ] Add predictive models, such as delivery time or order value prediction
- [ ] Automate the data loading and cleaning as a reusable pipeline

## 🛠️ Tech Stack

Python · Pandas · NumPy · Matplotlib · Seaborn · SQL · Jupyter Notebook

## 👩‍💻 Author

**Janvi Malve** | [GitHub](https://github.com/janvi-malve02) | [LinkedIn](https://www.linkedin.com/in/janvi-malve) | janvimalve12@gmail.com
