# MTA Daily Ridership Analysis & Forecasting 🚇 🚌

## 📌 Project Overview

This project focuses on analyzing and forecasting the daily ridership data of the **Metropolitan Transportation Authority (MTA)** in New York City. The study covers the period from March 2020 (the start of the COVID-19 pandemic) through late 2024. Our goal is to provide data-driven insights into the recovery of the world's largest transportation network and predict future ridership volumes to assist in urban planning and decision-making.

---

## 📂 Project Resources
*Click the links below to view the project files directly on GitHub:*

* 📊 **[Main Dataset](Data/mta_ridership_data.csv)** - Contains daily ridership counts and pre-pandemic comparisons.
* 📖 **[Data Dictionary](Data/data_dictionary.csv)** - Descriptions of all fields and columns used in the dataset.
* 📜 **[Technical Overview](Data/technical_notes.pdf)** - Official MTA documentation regarding methodology and data collection.

---

## 🛠️ Tech Stack

* **Data Processing:** SQL, Python (Pandas, NumPy)
* **Statistical Analysis:** Python (Scipy, Statsmodels)
* **Machine Learning:** Scikit-learn (Time Series Forecasting)
* **Data Visualization:** Tableau, Matplotlib, Seaborn

---

## 📅 4-Week Project Roadmap

### **Week 1: Data Model & Preprocessing** 🧹

* **Focus:** Cleaning the raw dataset and handling missing values (especially for LIRR/Metro-North records).
* **Deliverables:** Cleaned dataset and a preprocessing Jupyter Notebook.

### **Week 2: Analysis Questions Phase** 📊

* **Focus:** Identifying trends such as "Which transit mode recovered fastest?" and "How do holiday patterns differ post-pandemic?".
* **Deliverables:** SQL queries and Python-based statistical summaries.

### **Week 3: Forecasting Questions Phase** 🔮

* **Focus:** Building a model to predict ridership for the **next month** based on historical trends and seasonality.
* **Deliverables:** Predictive visualization plots and model accuracy metrics.

### **Week 4: Dashboard & Final Presentation** 🖥️

* **Focus:** Designing an interactive **Tableau Dashboard** and compiling the final project report.
* **Deliverables:** Interactive Dashboard link and Project Presentation.

---

## 👥 The Team (6 Members)

| Name | Primary Role | Responsibilities |
| --- | --- | --- |
| **Member 1** | **Data Engineer** | Data cleaning, type conversion, and handling null values. |
| **Member 2** | **Database Specialist** | Managing SQL queries and structuring the data model. |
| **Member 3** | **Data Analyst** | Performing EDA and answering business questions from Week 2. |
| **Member 4** | **ML Engineer** | Developing the forecasting models and time-series predictions. |
| **Member 5** | **BI Developer** | Designing the interactive Tableau Dashboard and KPIs. |
| **Member 6** | **Project Coordinator** | Technical writing, final reporting, and presentation design. |

---

## 🚀 How to Run

1. **Clone the Repo:** `git clone https://github.com/your-username/mta-ridership-analysis.git`
2. **Environment Setup:** Install requirements via `pip install -r requirements.txt`
3. **Execution:** Run the Notebooks in order: `Preprocessing` -> `Analysis` -> `Forecasting`.
