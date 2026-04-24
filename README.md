# DashBoard_project
# Fraud Detection Dashboard — Power BI

A comprehensive **Fraud Detection Analytics Dashboard** built using Power BI as part of a college project. The dashboard provides deep insights into fraud patterns, victim profiles, and transaction-level anomalies through interactive visualizations.

---

##  Dashboard Overview

The report consists of **2 interactive pages**:

### Page 1 — Fraud Overview
Provides a high-level summary of fraud activity including:
- Total fraud cases and amounts via KPI cards
- Fraud trends over time (Area Chart)
- Fraud distribution by category (Clustered Column Charts)
- Fraud type breakdown (Donut Chart)
- Top fraud categories (Clustered Bar Chart)
- Interactive slicers for dynamic filtering

### Page 2 — Victim Profile
Dives deep into who is being targeted including:
- Victim demographic KPIs
- Age and gender-based fraud analysis (Column & Bar Charts)
- Geographic and category-level victim breakdown
- Interactive filters for slice-and-dice analysis

---

## Tools & Technologies

| Tool | Usage |
|---|---|
| **Power BI Desktop** | Dashboard creation & visualization |
| **Power Query** | Data transformation & cleaning |
| **DAX** | Calculated measures & KPIs |

---

##  Project Structure

```
fraud-detection-dashboard/
│
├── dashboard/
│   └── int387_final_dashboard.pbix   # Main Power BI file
│
├── dataset/
│   └── fraud_data.csv                # Raw dataset
│
└── README.md
```

---

##  How to Run

1. Clone this repository
```bash
git clone https://github.com/yourusername/fraud-detection-dashboard.git
```

2. Open **Power BI Desktop** (free download from Microsoft)

3. Open the `.pbix` file from the `dashboard/` folder

4. If prompted, reconnect the dataset:
   - Go to **Home → Transform Data → Data Source Settings**
   - Update the path to the dataset file in the `dataset/` folder

5. Click **Refresh** and explore! 

---

##  Key Insights

-  Identified peak fraud periods and high-risk timeframes
-  Profiled most targeted victim demographics
-  Categorized fraud types by frequency and financial impact
-  Enabled dynamic filtering for deep-dive analysis

---

## About

This project was developed as part of a **college curriculum** to apply data analytics and visualization skills to a real-world problem — financial fraud detection.

---

## Connect

Feel free to connect with me on [LinkedIn](#) or raise an issue if you have suggestions!

>  If you found this project helpful, please give it a star!
