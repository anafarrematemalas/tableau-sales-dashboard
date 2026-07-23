# 🧸 ToysAreWe Sales Performance Dashboard

Interactive **Tableau** dashboard analyzing the sales performance of the fictional company **ToysAreWe** over the period **2023–2025**.

Project by **Adrien Dalibert & Ana Farre**.

![Dashboard preview](docs/dashboard_preview.png)

## 📌 Project context

The goal of this project is to turn raw transactional sales data into an interactive dashboard that supports business understanding and decision-making.

- **Audience:** primarily aimed at top business managers and company executives, who are not necessarily data experts. The focus is therefore on clarity, key performance indicators (KPIs), and intuitive visualizations rather than complex statistical outputs.
- **Goal:** provide a clear overview of sales performance, identify trends over time, and highlight the best-performing products and periods to support monitoring and strategic decisions.
- **Limitations:** the dashboard relies only on historical sales data and does not include external factors such as marketing campaigns, seasonality drivers, or customer behavior.

## 🗂️ Dataset composition

The dataset contains sales transactions from 2023 to 2025, with the following columns:

| Block | Content |
|---|---|
| Transaction | Sale date, transaction ID |
| Customer | Customer category, account type, age |
| Store | Name, ID, category, size, and location (7 columns) |
| Product | Name, ID, unit price, cost price, discount, etc. (9 columns) |

## 📊 Dashboard structure

The `.twbx` file includes the following tabs/sheets:

- **TOPIC** – overview of the project context, audience, dataset, goals, and challenges.
- **TOYS WE ARE** – main dashboard with KPIs (Sales Revenue, Total Profit, Profit margin), monthly revenue trend, revenue by country, sales by store, and top products.
- **KPI** – key performance indicators.
- **LINE** – revenue trend over time.
- **MAP** – revenue by country map.
- **store** – sales analysis by store.
- **product** – sales analysis by product.

## 🔍 Main KPIs

- **Sales Revenue**
- **Total Profit**
- **Profit margin**

With interactive filters by **year**, **region**, **customer category**, and **product category**.

## 🛠️ Tools used

- [Tableau Desktop Public Edition](https://public.tableau.com/)

## 🚀 How to open the dashboard

1. Download the [`toysarewe-sales-dashboard.twbx`](./toysarewe-sales-dashboard.twbx) file from this repository.
2. Open it with **Tableau Desktop** (or the free **Tableau Public**).
3. Navigate between tabs using the bottom bar to explore the full analysis.

> 💡 You can also publish the file to [Tableau Public](https://public.tableau.com/) to share an interactive version via link, without requiring viewers to install Tableau.

## ⚠️ Project challenges

- Identifying the data most relevant to the target audience (the executive committee).
- Coordinating teamwork, since Tableau does not support real-time collaboration.
- Balancing clarity, information hierarchy, and visual coherence in the dashboard design.

## 📁 Repository structure

```
├── toysarewe-sales-dashboard.twbx     # Tableau dashboard file
├── docs/
│   └── dashboard_preview.png          # Dashboard screenshot
└── README.md
```

---

*Academic Data Visualization project.*
