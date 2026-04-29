# 📦 Supply Chain Analysis
## 📌 Project Overview

This project focuses on analyzing supply chain data to uncover key insights related to **demand, supply efficiency, logistics, and product performance**.

The goal is to identify:

* Demand-supply imbalances
* Operational inefficiencies
* High-performing products and locations
* Bottlenecks in the supply chain

---

## 📂 Dataset

* Dataset contains **100 rows and 24 columns**
* Includes features like:

  * Product Type, SKU
  * Price, Availability
  * Order Quantities, Sales
  * Revenue Generated
  * Shipping Costs, Defect Rates
  * Transportation Modes, Location

---

## ⚙️ Tech Stack

* **Python**
* **Pandas, NumPy** → Data manipulation
* **Matplotlib, Seaborn** → Visualization

---

## 🔍 Data Analysis Steps

### 1. Data Loading & Inspection

* Loaded dataset using Pandas
* Checked:

  * Data types
  * Missing values
  * Unique values
  * Shape and structure

---

### 2. Descriptive Statistics

* Generated statistical summary of key numerical features
* Observed distribution of:

  * Price
  * Sales
  * Revenue
  * Stock levels

---

### 3. Feature Engineering

Created custom business metrics to better understand supply chain performance:

* **Demand Pressure Index**
  → Measures demand vs available supply

* **Fill Proxy**
  → Indicates how much demand is fulfilled

* **Efficiency Index**
  → Revenue generated relative to operational costs

* **Quality Adjusted Efficiency**
  → Efficiency adjusted by defect rates

* **Composite Market Index**
  → Combined metric representing overall performance

---

### 4. Exploratory Data Analysis (EDA)

#### 📍 Demand Analysis

* Demand pressure analyzed by:

  * Location
  * Product type

👉 Identified cities and categories with highest demand stress

---

#### 🚚 Logistics Efficiency

* Compared transportation modes:

  * Sea (highest efficiency)
  * Air, Rail, Road

---

#### 🏆 Performance Analysis

* Top locations based on composite index:

  * Mumbai
  * Kolkata
  * Delhi

* Identified **top-performing SKUs**

---

#### ⚠️ Bottleneck Detection

Detected problematic SKUs using:

* High demand pressure
* Low fulfillment
* High defect rates

---

#### 🔗 Correlation Analysis

* Analyzed relationship with **Composite Market Index**
* Key drivers:

  * Quality-adjusted efficiency
  * Revenue
  * Sales

---

## 💡 Key Insights

* High demand does not always translate to high fulfillment
* Sea transport shows better efficiency compared to others
* Some SKUs suffer from **high demand but low supply fulfillment**
* Defect rates significantly impact overall efficiency

---

## 🚀 Business Recommendations

* Increase supply for high-demand locations
* Improve quality control for high-defect SKUs
* Optimize transportation strategy (focus on efficient modes)
* Scale high-performing products and regions

---

## 📊 Conclusion

This project demonstrates how data-driven insights can help:

* Improve supply chain efficiency
* Reduce bottlenecks
* Enhance decision-making

---

## 📁 How to Run

```bash
1. Clone the repository
2. Install dependencies:
   pip install pandas numpy matplotlib seaborn
3. Run the notebook:
   jupyter notebook supply_chain.ipynb
```

---

## 👤 Author

**Shubham Chaurasia**

---