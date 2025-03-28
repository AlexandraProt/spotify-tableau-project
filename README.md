# Spotify Tableau Project: Revenue, Costs, and User Growth Analysis

## 📦 Description

A Tableau project analyzing Spotify's revenue, user growth, and cost structure from 2017–2023. Includes dashboards, KPIs, and stakeholder insights for strategy, revenue, and operations.

---

## 📋 Features

- 📈 Revenue breakdown: Total, Premium vs. Ad Revenue
- 👥 User growth analysis: MAUs, Premium vs. Ad
- 💰 ARPU and monetization trends
- 💡 Operational cost efficiency insights
- 📊 Clean and interactive Tableau dashboards
- 🧠 Executive summary with recommendations

---

## 🗂️ Repository Structure

```
spotify-tableau-project/
├── README.md                  # Project summary and instructions
├── Spotify Dataset.xlsx       # Cleaned dataset with calculated metrics
├── Tableau Dashboards/
│   ├── Revenue & Profit.twbx
│   ├── User Growth.twbx
│   └── Cost Structure.twbx
├── Screenshots/
│   ├── revenue_chart.png
│   ├── user_growth.png
│   └── cost_analysis.png
└── Report.pdf                 # Final report with key insights
```

## 📊 Project Summary

This project simulates a Spotify BI analyst sprint. Based on 17 key metrics from 2017–2023, dashboards were built for three internal stakeholders:

- **Sarah (Strategy)** – user growth trends
- **Mark (Revenue)** – revenue streams & ARPU
- **Olivia (Operations)** – cost efficiency & margin insights

The dashboards are designed to be interactive, business-focused, and presentation-ready.

---

## 🔗 Live Tableau Preview (optional)

...will be added soon

---

# Spotify Tableau Project

## 📄 Introduction

This project simulates a real-world BI analyst task at **Spotify**, focusing on financial and user data from **2017 to 2023**. You will analyze Spotify's **revenue streams**, **cost structure**, and **user engagement** through Tableau visualizations to deliver actionable insights to key stakeholders.

---

## 🔢 Dataset Overview

The dataset includes 17+ columns such as:

- `Date`, `Quater`, `Quarter Number`
- `Total Revenue`, `Cost of Revenue`, `Gross Profit`
- `Premium Revenue`, `Premium Cost Revenue`, `Premium Gross Profit`
- `Ad Revenue`, `Ad Cost of Revenue`, `Ad Gross Profit`
- `MAUs`, `Premium MAUs`, `Ad MAUs`
- `Premium ARPU`
- `Sales and Marketing Cost`, `Research and Development Cost`, `General and Administrative Cost`



---

## 🚀 Project Phases

### Phase 1: Planning and KPI Definition

1. **Dataset Exploration**

   - Explore Google Sheets or Excel dataset
   - Review revenue vs. cost trends, premium vs. ad segmentation

## Data Preparation

### Spotify Project Data (`New coloumns Spotify Project `)   
📥 [Download cleaned CSV]([New coloumns Spotify Project .xlsx)](https://github.com/AlexandraProt/spotify-tableau-project/blob/main/New%20coloumns%20Spotify%20Project%20.xlsx)

2. **Define Stakeholder Goals**

| Stakeholder         | Goals                                       |
| ------------------- | ------------------------------------------- |
| Sarah (Strategy)    | User growth insights by type                |
| Mark (Revenue)      | Revenue breakdown and ARPU trend            |
| Olivia (Operations) | Cost structure & optimization opportunities |

3. **Key KPIs**

- Revenue Growth Rate
- Premium vs Ad Revenue Share
- ARPU Dynamics
- Gross Margin (Total, Premium, Ad)
- Cost % of Revenue (S&M, R&D, G&A)
- Premium MAU Share

4. **Plan Visualizations**

- Line Charts (Revenue, ARPU, User Growth)
- Bar Charts (Cost Breakdown)
- Pie / Area Charts (User Segmentation)

---

Вот финальная версия секции **Dashboards Overview** для `README.md` в Markdown формате с учётом всех 11 визуализаций (файлов):

---

### 📊 Dashboards Overview

This project includes three dashboards analyzing Spotify's business performance from 2017 to 2023. Each dashboard provides visual insights for a specific stakeholder: Strategy, Revenue, or Operations.

---

#### ✅ Dashboard 1: Revenue & Profit Overview

Focus: Revenue growth trends, premium vs ad monetization, and profitability over time.

| Chart | Description |
|-------|-------------|
| ![01_total_revenue_trend](./01_total_revenue_trend.png) | **Total Revenue over Time (Yearly)** – Displays annual growth of total revenue from 2017 to 2023. |
| ![02_quarterly_revenue_trend](./02_quarterly_revenue_trend.png) | **Total Revenue by Quarter** – Compares revenue performance across Q1–Q4. |
| ![03_gross_margin_per_quarter](./03_gross_margin_per_quarter.png) | **Total Gross Margin by Quarter** – Highlights average gross margin fluctuations per quarter. |
| ![04_dual_axis_premium_vs_ad](./04_dual_axis_premium_vs_ad.png) | **Premium Revenue vs Ad Revenue (Dual-Axis)** – Compares revenue streams side-by-side across all quarters. |

---

#### ✅ Dashboard 2: User Growth & Segmentation

Focus: User acquisition, segmentation by subscription type, and monetization.

| Chart | Description |
|-------|-------------|
| ![05_user_growth](./05_user_growth.png) | **User Growth Over Time** – Shows growth of total MAUs, Premium MAUs, and Ad MAUs. |
| ![06_mau_share_stacked](./06_mau_share_stacked.png) | **MAU Share (Stacked Area Chart)** – Visualizes Premium vs Ad user share per quarter. |
| ![07_premium_arpu](./07_premium_arpu.png) | **Premium ARPU Trend** – Tracks average revenue per Premium user over time. |

---

#### ✅ Dashboard 3: Cost & Efficiency

Focus: Operational cost breakdown, departmental spending, and margin efficiency.

| Chart | Description |
|-------|-------------|
| ![08_cost_breakdown_bar](./08_cost_breakdown_bar.png) | **Cost % of Revenue (Bar Chart)** – Tracks spending in Sales, R&D, and Admin as a share of revenue. |
| ![09_cost_donut_chart](./09_cost_donut_chart.png) | **Cost Distribution (Donut Chart)** – Visual comparison of Sales, R&D, and Admin costs. |
| ![10_premium_ad_gross_margin](./10_premium_ad_gross_margin.png) | **Gross Margin: Premium vs Ad** – Tracks profitability by revenue stream over time. |
| ![11_cost_breakdown_quarters](./11_cost_breakdown_quarters.png) | **Cost Breakdown by Quarter** – Compares how costs shift between Q1, Q2, Q3, and Q4. |

---

### 📊 Final Dashboards

Each dashboard below is designed for a specific stakeholder at Spotify and summarizes key insights using visual data from 2017 to 2023.

---

#### 👨‍💼 Dashboard 1: Revenue & Profit Overview  
**Stakeholder:** Mark – *Focused on revenue performance, monetization models, and profit trends.*

![Revenue Dashboard](./dashboard_1_revenue_mark.png)

- Tracks **quarterly revenue trends**
- Compares **Premium vs Ad revenue**
- Highlights **average gross margin by quarter**

---

#### 👩‍💼 Dashboard 2: User Growth & Segmentation  
**Stakeholder:** Sarah – *Focused on user acquisition, growth segmentation, and monetization potential.*

![User Growth Dashboard](./dashboard_2_users_sarah.png)

- Shows **total MAUs, Premium, and Ad-based users**
- Visualizes **user type share** over time
- Tracks **Premium ARPU** trend per quarter

---

#### 🛠 Dashboard 3: Cost & Efficiency  
**Stakeholder:** Olivia – *Focused on operational costs, departmental efficiency, and profitability.*

![Cost Efficiency Dashboard](./dashboard_3_costs_olivia.png)

- Breaks down **Sales, R&D, and Admin costs**
- Compares **cost distribution and share per quarter**
- Analyzes **gross margin by segment (Premium vs Ad)**

---

## 📌 Executive Summary & Recommendations

This analysis of Spotify’s business performance from 2017 to 2023 reveals key trends across revenue, user growth, and operational efficiency. The dashboards were tailored to address the needs of three stakeholders: Strategy, Revenue, and Operations.

### 🔍 Key Findings

- **Revenue Trends**: Spotify's total revenue has grown steadily year over year. Premium subscriptions remain the dominant source of revenue, although Ad revenue is increasing gradually.
- **Profitability**: Premium services consistently deliver higher gross margins than Ad-based models. However, overall gross margin has fluctuated slightly by quarter.
- **User Base**: The platform saw significant growth in Monthly Active Users (MAUs), especially in Ad-supported users, indicating strong market expansion potential.
- **ARPU Stability**: Despite user growth, Premium ARPU remained relatively flat, suggesting pricing pressure or expansion into lower-paying markets.
- **Cost Structure**: Sales and R&D account for the largest share of operating costs. Operational efficiency shows moderate improvement over time.

### ✅ Recommendations

1. **Diversify Monetization**: Invest further in growing Ad-supported revenue streams while exploring hybrid models (e.g., freemium).
2. **Improve ARPU**: Consider localized pricing strategies, bundling, and upsell offers to boost ARPU without alienating users.
3. **Optimize Operational Spend**: Analyze departmental spending efficiency—especially in G&A—by benchmarking against industry peers.
4. **Strategic User Segmentation**: Leverage insights from MAU trends to tailor acquisition campaigns and improve retention for each user type.
5. **Prioritize High-Margin Segments**: Focus on Premium segment profitability while keeping an eye on scalable Ad revenue opportunities.

---
