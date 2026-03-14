# fraud_detection_powerbi
Interactive Power BI dashboard analyzing bank transactions with fraud detection insights, featuring custom backgrounds, DAX measures, and 3-page navigation.

---

## 📊 Pages Overview

### 🏠 Home Page
Overview of all bank transactions with key metrics and trends.

### 🚨 Fraud Detection Page
Filtered view showing only flagged fraudulent transactions with breakdown by bandwidth group and network slice.

### 📋 Transaction Details Page
Detailed table of individual transactions with conditional formatting to highlight fraud status.

---

## 📈 Visuals Used

|    Visual    |                     Description                          |
|--------------|----------------------------------------------------------|
| KPI Cards    | Total Transactions & Total Transaction Amount            |
| Line Chart   | Transaction trend over time                              |
| Bar Charts   | Transaction status, Bandwidth groups, Network slices     |
| Donut Charts | Fraud flag %, Transaction type breakdown                 |
| Map          | Geographic distribution of transactions                  |
| Slicers      | Filter by type, status, device, network slice            |
| Table        | Detailed transaction records with conditional formatting |

---

## 🛠️ Tools & Techniques

-   Power BI Desktop   — Report building & visualization
-   Power Query        — Data cleaning (split coordinates, format timestamps)
-   DAX                — Calculated columns (bandwidth groups) & measures (Total Transactions, Transaction Amount)
-   PowerPoint         — Custom SVG backgrounds for all 3 pages
-   Page Navigator     — Button-based navigation across pages

---

## 📁 Files

|             File             |        Description       |
|------------------------------|--------------------------|
| `fraud_detection.pbix` | Power BI report file     |
| `bank_transactions.csv`      | Source dataset           |
| `screenshots/`               | Dashboard preview images |

---
