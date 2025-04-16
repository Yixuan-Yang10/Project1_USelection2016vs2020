# Project1_USelection2016vs2020
# US Election Contribution Analysis (2016 & 2020)

## 📊 Project Overview

This project analyzes campaign contribution data from the **2016 and 2020 U.S. Presidential Elections**, focusing on the contribution amounts to Democratic and Republican parties across all U.S. states. The goal is to explore financial support patterns and detect changes over time using SQL-based data warehousing and visual analytics.

---

## 🧹 Data Preparation

- **Dataset Size:** ~5 GB
- **Source Format:** CSV files containing detailed contribution data.
- **Cleaning Tools:**
  - [`CSVkit`](https://csvkit.readthedocs.io/en/latest/) (used in Unix Shell for data filtering and transformation)
  - **Trifacta** (for advanced data cleaning and profiling)
  
We ensured consistency in data types, checked null values, and extract the relevant variables before loading the data into the database.

---

## 🛠️ Database Design & Setup

- **Platform:** AWS EC2
- **Schema:** Star schema designed to support efficient analytical queries.
- **Implementation:**
  - Created two separate data warehouses for **2016** and **2020** election data.

---

## 🔍 Sample Analytical Queries

We developed SQL queries to investigate key questions, such as:

- **Geographic insights:**  
  _How many cities in Virginia contributed to Hillary Clinton vs. Donald Trump in 2016?_

- **Time-based behavior shifts:**  
  _Did committee contributions to the Republican Party increase after Trump announced reopening plans on May 1st, 2020?_

These queries helped uncover political, regional, and behavioral trends in election funding.

---

## 📈 Data Visualization

To present our findings, we used:

- **Tableau:** for interactive dashboards and state-level visual summaries
- **Python + Matplotlib:** for generating charts and visual analytics programmatically

---

## 💡 Key Takeaways

- Built two robust, scalable data warehouses from raw CSV files.
- Leveraged cloud infrastructure (AWS EC2) for hosting and querying large datasets.
- Integrated multiple tools (Unix shell, Trifacta, SQL, Tableau, Python) for a full data engineering and analytics pipeline.
- Identified trends and patterns in campaign funding across two election cycles.

---

## 🧠 Tools & Technologies Used

- `CSVkit` (Unix command-line)
- `Trifacta`
- `AWS EC2` (PostgreSQL/MySQL)
- `SQL`
- `Python` (Matplotlib)
- `Tableau`

---

