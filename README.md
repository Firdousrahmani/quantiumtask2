# quantiumtask2


##  Project Title: Trial Store Layout Analysis & Sales Uplift Evaluation
dashboard![insights](https://github.com/Firdousrahmani/quantiumtask2/blob/main/barchart.png)

This project is part of the **Quantium Virtual Internship** offered on Forage. In Task 2, I stepped into the role of a **Retail Data Analyst**,
tasked with evaluating the performance of **trial store layouts** and determining whether they resulted in an **uplift in sales**.

---

##  Objective

Quantium ran a trial in stores **77, 86, and 88** to test a new layout.  
My goal was to assess the trial's success by:

- Selecting suitable **control stores** for each trial store
- Comparing **pre- and post-trial performance**
- Recommending whether the trial layout should be rolled out further

---

## 🔧 Tools & Libraries Used

- **Python 3.10+**
- **Pandas** for data wrangling and aggregation
- **Seaborn & Matplotlib** for visualizations
- **Numpy** for numerical ops
- **Jupyter Notebook** for exploratory analysis

---

## 📁 Dataset Used

`QVI_data.csv` – Contains sales transaction-level data with fields:
- `DATE`
- `STORE_NBR`
- `LYLTY_CARD_NBR` (Customer ID)
- `TXN_ID`
- `TOT_SALES`
- `PROD_QTY`

---

##  Steps & Methodology

###  1. **Data Cleaning & Monthly Aggregation**
- Converted dates, extracted `MONTH_YEAR`
- Grouped sales, customers, and quantities at a monthly level per store

###  2. **Control Store Selection**
- Chose stores with **similar pre-trial trends** based on:
  - Total Sales correlation (Pearson)
  - Visual sales pattern matching
  - Total sales volume check to avoid low-performing stores

| Trial Store | Control Store | Correlation |
|-------------|----------------|--------------|
| Store 77    | Store 41        | 0.76         |
| Store 86    | Store 109       | 0.64         |
| Store 88    | Store 201       | 0.73         |

###  3. **Sales & Customer Behavior Analysis**
- Compared:
  - 💰 Total Sales
  - 📦 Product Quantity Sold
  - 👥 Repeat Customer Counts
  - 💳 Avg Transactions per Customer

- Plotted each trial vs control pair using:
  - Line graphs (sales & quantity)
  - Bar charts (average transaction metrics)

---

##  Key Insights

- All 3 trial stores showed a **clear uplift in performance** compared to their controls
- Uplift was visible in both **sales and product quantity**
- Repeat customer behavior improved slightly in trial stores

---

##  Final Recommendation

> “Roll out the new layout to more stores, and re-evaluate in 3 months to ensure the uplift sustains over time.”

---

## 🧠 What I Learned

- Practical application of **experimental design in business**
- Using **correlation** and **visual patterns** to select control groups
- Balancing **statistical rigor** with **business logic**
- Presenting results through clean visuals and metrics

---

## 🔗 www.linkedin.com/in/firdousrahmani






`#DataAnalytics` `#Python` `#Pandas` `#Seaborn` `#A/BTesting` `#RetailAnalytics` `#Quantium` `#GitHubPortfolio` `#VirtualInternship`

