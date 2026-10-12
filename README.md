# 🛡️ Asiwaju Insurance Analytics Dashboard

> An interactive Power BI report that analyzes premiums, coverage, claims, policy status, and customer feedback for an insurance organization.

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Domain](https://img.shields.io/badge/domain-Insurance-0b8f6a)
![Pages](https://img.shields.io/badge/report%20pages-3-blue)

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Dashboard Preview](#-dashboard-preview)
- [Key Metrics](#-key-metrics)
- [Report Pages](#-report-pages)
- [Key Insights](#-key-insights)
- [Tools & Techniques](#-tools--techniques)
- [How to Use](#-how-to-use)
- [Author](#-author)

---

## 📖 Overview

This project is a three-page Power BI report built for **Asiwaju Insurance Pvt. Ltd.** It gives management a single view of business performance and customer sentiment, helping answer questions such as:

- How much premium is each policy type generating?
- Which age groups account for the most claim value?
- How many claims are settled, rejected, or still pending?
- What share of policies are active vs. inactive?
- What do customers say about the claims process and customer service?

---

## 🖼 Dashboard Preview

### Page 1: Policy & Claims Overview
![Policy and Claims Overview](./images/Ins1.png)

### Page 2: Customer Feedback & Sentiment Analysis
![Customer Feedback and Sentiment Analysis](./images/Ins2.png)

### Page 3: Table

---

## 📊 Key Metrics

| Metric | Value |
|--------|-------|
| Total Premium Amount | **5.98M** |
| Total Coverage Amount | **600.55M** |
| Total Claim Amount | **16.91M** |
| Total Policies | **10,004** |
| Active Policies | 5.82K (58.13%) |
| Inactive Policies | 4.19K (41.87%) |
| Customers by Gender | Female: 5,001 · Male: 5,003 |

---

## 📄 Report Pages

### 1️⃣ Policy & Claims Overview
Gives a high-level view of the business through KPI cards and these visuals:

- **Premium Amount by Policy Type** (bar chart): Travel, Health, Auto, Life, Home
- **Claim Amount by Age Group** (area chart): Young Adult, Adult, Elder
- **Claim Status** (area chart): Rejected, Settled, Pending
- **Status by Policy** (donut chart): Active vs. Inactive policies
- **Policy Type vs. Claim Status** (matrix): Pending, Rejected, and Settled values per policy type
- **Slicers** for `CustomerID`, `ClaimNumber`, and `PolicyNumber` to drill into specific records

### 2️⃣ Customer Feedback & Sentiment Analysis
Turns customer comments into insight:

- **Word cloud** that highlights the most frequent words and themes in feedback
- **Feedback table** listing each customer's comment, so every theme can be traced back to the original response

### 3️⃣ <Add page title>
<!-- Describe what the third page shows. -->

---

## 💡 Key Insights

- **Travel** is the largest source of premium (2.48M), followed by Health (1.20M) and Auto (0.96M). Home is the smallest (0.60M).
- **Adults** account for the highest claim amount (8.8M), followed by Elders (6.4M) and Young Adults (1.7M).
- About **58%** of policies are active, while roughly **42%** are inactive, which suggests an opportunity to improve retention and renewals.
- The customer gender split is nearly even (5,001 female, 5,003 male).
- **Positive feedback** often mentions easy website navigation, responsive customer support, convenient payments, and clear policy terms.
- **Negative feedback** often mentions a confusing or slow claims process and customer service that was unhelpful or lacked knowledge.

---

## 🛠 Tools & Techniques

- **Power BI Desktop** for data modelling and report design
- **DAX** for measures and calculations
- **Power Query** for data cleaning and transformation
- **Text analysis visuals** (word cloud) for customer sentiment

> Edit this list to match what you actually used.


## ▶️ How to Use

1. Clone the repository
```bash
   git clone https://github.com/<your-username>/<your-repo>.git
```
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows only).
3. Open `Insurance_Report.pbix`.
4. Click **Refresh** if the data source path needs updating, then explore the pages and slicers.

---

## 👤 Author

**Sunday Theophilus Oyelami**
GitHub: [@ST-Oyelami](https://github.com/ST-Oyelami)

---

⭐ If you found this project useful, please consider giving it a star.
