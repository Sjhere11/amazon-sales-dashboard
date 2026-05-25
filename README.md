# 📊 Amazon Sales Dashboard: Data Analysis Project

An end-to-end data analytics portfolio project built in PyCharm to extract actionable business intelligence from Amazon transactional data. This repository features a structured Python pipeline for data cleaning, feature engineering, and advanced data visualization.

---

## 🛠️ Tech Stack & Environment
* **IDE**: PyCharm Professional
* **Language**: Python 3.10+
* **Data Engineering**: Pandas, NumPy
* **Visualization**: Matplotlib, Seaborn
* **Notebook Engine**: Jupyter Notebook

---

## 📂 Project Architecture
```text
amazon-sales-dashboard/
├── data/                  # Raw Kaggle CSV storage (Securely gitignored)
├── notebooks/             # Advanced EDA & Chart Generation
│   └── analysis.ipynb     # Main analytical playground & visualizations
├── src/                   # Production-ready operational scripts
│   └── clean_data.py      # Automated data ingestion & schema formatting
├── .gitignore             # Strict directory masking control
└── README.md              # Project portfolio profile
```

---

## 🔍 Key Insights & Analysis
* **Monthly Revenue Performance**: A chronological time-series line chart tracking monthly sales growth and trend volatility.
* **Category Contribution**: A horizontal bar chart identifying top-grossing retail categories to optimize inventory focus.
* **Logistical Health Breakdown**: A categorical operational check evaluating total counts of delivered vs. canceled or returned orders.
* **Customer Payment Channels**: A percentage distribution pie chart detailing preferred payment modes (UPI, Credit Card, etc.) utilized at checkout.

---

## 🚀 How to Run the Project
1. Clone this repository: `git clone https://github.com`
2. Place the Kaggle `amazon.csv` file inside the `data/` directory.
3. Install dependencies: `pip install pandas numpy matplotlib seaborn jupyter`
4. Open PyCharm and run the cells inside `notebooks/analysis.ipynb` sequentially.
