# Supply Chain Emission Factors Analysis (US Industries, 2015)

This project analyzes a dataset containing supply chain emission factors for various U.S. industries and commodities, based on 2015 summary data.

## 📁 Dataset Overview

- **Source:** U.S. industry and commodity-level emission factors (2015)
- **Target Variable:** `Supply Chain Emission Factors with Margins` (kg CO₂e per $)
- **Format:** CSV

The dataset includes industry names, sector classifications, and emission factor estimates.

---

## 📊 Objectives

1. Load and clean the dataset
2. Remove irrelevant, null, or duplicate rows
3. Perform exploratory data analysis (EDA)
4. Visualize emissions by industry and sector
5. Prepare for predictive modeling

---

## 🧹 Data Cleaning Steps

- Removed rows with null values in `Supply Chain Emission Factors with Margins`
- Dropped duplicate rows
- Removed irrelevant rows (e.g., containing 'spf')
- Removed unnamed and unwanted columns by index or name

---

## 📈 Visualizations

- **Top 10 Industries by Emissions:** Bar chart
- **Distribution of Emissions:** Histogram
- **Outlier Detection:** Boxplot
- **Cumulative Emission Contribution:** Line chart

All visualizations use **Matplotlib** and **Seaborn** for effective analysis.

---

## 🔬 Additional Analyses

- Summary statistics (mean, median, std)
- Sector-wise average emissions
- Outlier detection and removal
- Cumulative distribution showing Pareto-like emission contribution

---

## 🔧 Technologies Used

- **Python 3.x**
- **Pandas** – Data manipulation
- **Seaborn** / **Matplotlib** – Data visualization
- **Jupyter Notebook** – Analysis and reporting

---

## 🚀 How to Run

1. Clone the repository or open the Jupyter Notebook.
2. Place the dataset CSV in the same directory.
3. Run each cell step-by-step in `supply_chain_emissions_analysis.ipynb`.

---

## 📌 Project Ideas

- Build a regression model to predict emissions
- Sector-level emission forecasting
- Build a dashboard (using Streamlit or Plotly Dash)

---

## 📬 Contact

For questions or suggestions, feel free to reach out or raise an issue.

---

