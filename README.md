# Customer Segmentation using RFM Analysis & K-Means Clustering

## Project Overview

This project focuses on analyzing customer purchasing behavior and identifying meaningful customer segments using **RFM Analysis** and **K-Means Clustering**.

RFM Analysis is used to measure customers based on **Recency, Frequency, and Monetary value**. These features are standardized and used for clustering customers into different behavioral segments.

The final results are presented through an interactive **Power BI Dashboard** for better visualization and business understanding.

---

## Objectives

* Clean and preprocess the retail transaction dataset
* Perform Exploratory Data Analysis (EDA)
* Calculate customer-level **RFM metrics**
* Analyze relationships between RFM features
* Standardize RFM features
* Determine the suitable number of clusters using the **Elbow Method**
* Apply **K-Means Clustering**
* Identify meaningful customer segments
* Visualize the results using **Power BI**

---

## Project Workflow

```text
Raw Transaction Dataset
        ↓
Data Cleaning & Preprocessing
        ↓
Feature Engineering
        ↓
RFM Analysis
        ↓
Exploratory Data Analysis
        ↓
Feature Standardization
        ↓
Elbow Method
        ↓
K-Means Clustering
        ↓
Customer Segmentation
        ↓
Power BI Dashboard
```

---

## Dataset

The project uses a retail transaction dataset containing customer purchase information.

**Main Dataset:**
[View Dataset](https://docs.google.com/spreadsheets/d/1wa7qTUZjjHJ7ES8J2TwVdqCakWqEDCT2/edit?usp=sharing&ouid=108227675483635770351&rtpof=true&sd=true&utm_source=chatgpt.com)

* **Total Transactions:** 541,908
* **Final Customers:** 2,997
* **RFM Features:** Recency, Frequency, Monetary
* **Number of Clusters:** 4

### Main Features

* Invoice Number
* Stock Code
* Description
* Quantity
* Invoice Date
* Unit Price
* Customer ID
* Country
* Total Amount

---

## RFM Analysis

### Recency

Measures how recently a customer made a purchase.

### Frequency

Measures how frequently a customer made purchases.

### Monetary

Measures the total amount spent by a customer.

These three metrics are combined to understand individual customer purchasing behavior.

---

## Customer Segmentation

After preprocessing and RFM analysis, **K-Means Clustering** was applied to the standardized RFM features.

The analysis identified four customer segments:

| Segment           | Customers |
| ----------------- | --------: |
| Regular Customers |     2,083 |
| Lost Customers    |       862 |
| Champions         |        49 |
| VIP Customers     |         3 |

These segments represent different patterns of customer purchasing behavior.

---

## Power BI Dashboard

An interactive **Power BI Dashboard** was created using the segmented customer data.

The dashboard provides insights into:

* Customer segment distribution
* RFM metrics
* Customer purchasing behavior
* Segment-wise analysis
* Customer personas
* Key business insights

### Dashboard Demo

[Watch Dashboard Video](https://drive.google.com/file/d/1IoJtdjKxdgwD6mjTm6qOSwlhsLWwnsC4/view?usp=drive_link&utm_source=chatgpt.com)

---

## Technologies Used

**Programming:** Python, Pandas, NumPy

**Data Visualization:** Matplotlib, Seaborn, Power BI

**Machine Learning:** Scikit-learn, K-Means Clustering, StandardScaler, Elbow Method

**Environment:** Jupyter Notebook / Google Colab

---

## Project Structure

```text
Customer-Segmentation/
│
├── Dataset/
│   └── Final Mon-2 Dataset.xlsx
│
├── Notebooks/
│   ├── M2-Week1.ipynb
│   └── M2_Week2.ipynb
│
├── RFM/
│   ├── RFM_Dataset.csv
│   ├── RFM_Clustered.csv
│   └── RFM_Segmented_Dataset.csv
│
├── PowerBI/
│   └── Customer_Segmentation_Dashboard.pbix
│
└── README.md
```

---

## Key Result

The project transforms raw transaction data into **customer-level RFM insights and four customer segments** using K-Means Clustering.

The segmented results are presented through an interactive **Power BI Dashboard**, providing a clear view of customer behavior and segment characteristics.

---

## Future Scope

* Customer churn prediction
* Customer Lifetime Value analysis
* Advanced clustering techniques
* Automated customer segmentation
* Real-time Power BI reporting
* Personalized customer recommendations
