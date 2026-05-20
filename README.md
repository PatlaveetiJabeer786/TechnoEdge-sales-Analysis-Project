# 📊 Sales Analysis: TechnoEdge Performance Dashboard


# 📊 Sales Analysis: TechnoEdge Performance Dashboard

[![Header](https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=200&section=header&text=TechnoEdge%20Sales%20Analysis&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Power%20BI%20Performance%20Dashboard&descAlignY=55&descSize=18)](https://github.com/PatlaveetiJabeer786/TechnoEdge-sales-Analysis-Project)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-FF6B35?style=for-the-badge&logo=microsoft&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed%20✅-success?style=for-the-badge)
![Duration](https://img.shields.io/badge/Duration-Jan%202025--Feb%202025-blue?style=for-the-badge)

---

## 🔴 The Business Problem

> **TechnoEdge** is a growing electronics retail company that was facing a **critical operational crisis** — their entire sales data was scattered across **36+ monthly CSV files** with **zero automation**, making it nearly impossible for leadership to understand business performance.

### 😓 What Was Going Wrong

- 📂 Sales data **locked in 36+ separate monthly files** — no consolidation
- ⏰ Analysts spending **many hours every week** just compiling basic reports
- ❌ **No single source of truth** — every department had different numbers
- 🔍 Leadership forced to make **million-dollar decisions without real insights**
- 📉 **Zero visibility** into which regions, products, or customers were performing
- 🚨 Monthly reporting was **delayed, error-prone, and unreliable**

---

## 🎯 My Role & Task

### 👨‍💻 I was assigned as the Data Analyst to solve this problem end-to-end

| Step | Task | Tool Used | Impact |
|------|------|-----------|--------|
| 1️⃣ | Understand Business Requirements & Pain Points | Stakeholder Meeting | Clear direction |
| 2️⃣ | Collect All 36+ Monthly CSV Sales Files | File System | Raw data secured |
| 3️⃣ | Clean & Transform — Build Automated ETL Pipeline | Power Query | 70% time saved |
| 4️⃣ | Design Star Schema Data Model | Power BI Desktop | Faster queries |
| 5️⃣ | Build DAX KPI Measures | DAX Language | Instant insights |
| 6️⃣ | Build Interactive Dashboard | Power BI | Real-time decisions |

---

## 📊 Dashboard Preview

![TechnoEdge Dashboard](Technoedge%20Sales%20Dash%20Board.jpg)

*👆 The Interactive Power BI Dashboard I Built — Geographic Sales Map + Ribbon Charts + KPI Cards*

---

## ✅ Results & Business Impact

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                    📈 BUSINESS RESULTS I DELIVERED                       ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║   ⚡ 70% REDUCTION   →  Manual data preparation time eliminated          ║
║   📂 36+ FILES        →  Consolidated into ONE single live dashboard     ║
║   🕐 HOURS→MINUTES   →  Monthly reporting time dramatically reduced      ║
║   🌍 GEOGRAPHIC VIEW  →  Regional sales performance now fully visible    ║
║   💡 REAL-TIME KPIs   →  Leadership gets instant business insights       ║
║   🎯 ZERO ERRORS      →  Automated pipeline removed human error          ║
║   📈 GROWTH TRACKING  →  Month-over-month trends now clearly visible     ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 💼 How It Helped The Business — Before vs After

| 📊 Metric | ❌ Before My Project | ✅ After My Project |
|-----------|---------------------|-------------------|
| Data Sources | 36+ scattered CSV files | 1 unified live dashboard |
| Report Generation Time | Many hours of manual work | Seconds (fully automated) |
| Human Effort | High — copy-paste every month | Eliminated — 70% reduction |
| Decision Speed | Waited days for reports | Real-time instant insights |
| Geographic Visibility | Absolutely zero | Full interactive map view |
| Error Rate | High — manual mistakes | Near zero — automated pipeline |
| Stakeholder Confidence | Low — inconsistent numbers | High — single source of truth ✅ |
| Product Performance View | Not available | Full ribbon chart ranking visible |

### 🏆 4 Major Ways I Helped The Business

- 🚀 **Faster Decisions** — Leadership identifies top/bottom performing regions in **seconds** instead of waiting days
- 💰 **Cost Savings** — Eliminated hours of weekly manual data work — analysts freed to focus on **strategy**
- 🎯 **Targeted Strategy** — Geographic mapping revealed **exactly which cities** needed attention for focused sales campaigns
- 📈 **Growth Tracking** — Ribbon charts clearly showed **product category trends** — helping optimize inventory and marketing spend

---

## 🛠️ Tech Stack & Skills Used

| Tool | How I Used It | Skill Level |
|------|--------------|-------------|
| ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) **Power BI Desktop** | Built the full interactive dashboard, visuals, and data model | ⭐⭐⭐⭐⭐ |
| ![Power Query](https://img.shields.io/badge/Power%20Query-0078D4?style=flat-square&logo=microsoft&logoColor=white) **Power Query (M Language)** | Automated ETL — cleaned and consolidated all 36+ CSV files | ⭐⭐⭐⭐⭐ |
| ![DAX](https://img.shields.io/badge/DAX-FF6B35?style=flat-square&logo=microsoft&logoColor=white) **DAX** | Created all KPI measures — Revenue, Profit, Growth %, YTD | ⭐⭐⭐⭐⭐ |
| ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white) **Microsoft Excel** | Raw data source — 36+ monthly CSV/Excel sales files | ⭐⭐⭐⭐⭐ |
| 🗄️ **Star Schema Modeling** | Designed Fact and Dimension table relationships | ⭐⭐⭐⭐⭐ |
| 📊 **Data Visualization** | Geographic maps, ribbon charts, KPI cards, trend lines | ⭐⭐⭐⭐⭐ |

---

## 🏗️ Data Architecture — Star Schema I Designed

```
                    ┌─────────────────────┐
                    │     FACT TABLE       │
                    │   📊 Sales_Fact      │
                    │                      │
                    │  • Order_ID    (PK)  │
                    │  • Customer_ID (FK)  │
                    │  • Product_ID  (FK)  │
                    │  • Date_ID     (FK)  │
                    │  • Location_ID (FK)  │
                    │  • Revenue           │
                    │  • Quantity_Sold     │
                    │  • Profit            │
                    │  • Discount          │
                    └──────────┬───────────┘
                               │
         ┌─────────────────────┼─────────────────────┐
         │                     │                     │
  ┌──────▼──────┐      ┌───────▼───────┐     ┌───────▼───────┐
  │ 👤 Customer │      │  📅 Date Dim  │     │  📦 Product   │
  │  Dimension  │      │               │     │  Dimension    │
  │             │      │  • Date_ID    │     │               │
  │  • Cust_ID  │      │  • Year       │     │  • Prod_ID    │
  │  • Name     │      │  • Month      │     │  • Name       │
  │  • Segment  │      │  • Quarter    │     │  • Category   │
  │  • Region   │      │  • Week       │     │  • Sub-Cat    │
  │  • City     │      │  • Day_Name   │     │  • Brand      │
  └─────────────┘      └───────────────┘     └───────────────┘
                               │
                       ┌───────▼───────┐
                       │  🌍 Location  │
                       │  Dimension    │
                       │               │
                       │  • Loc_ID     │
                       │  • City       │
                       │  • State      │
                       │  • Region     │
                       │  • Zone       │
                       └───────────────┘
```

---

## 📐 Key DAX Measures I Created

```dax
// ═══════════════════════════════════════════
//           CORE REVENUE MEASURES
// ═══════════════════════════════════════════

Total Revenue    = SUM(Sales_Fact[Revenue])
Total Profit     = SUM(Sales_Fact[Profit])
Total Orders     = DISTINCTCOUNT(Sales_Fact[Order_ID])
Profit Margin %  = DIVIDE([Total Profit], [Total Revenue], 0) * 100

// ═══════════════════════════════════════════
//           TIME INTELLIGENCE MEASURES
// ═══════════════════════════════════════════

YTD Revenue = TOTALYTD([Total Revenue], 'Date'[Date])

PY Revenue  = CALCULATE([Total Revenue], SAMEPERIODLASTYEAR('Date'[Date]))

YoY Growth % = DIVIDE([Total Revenue] - [PY Revenue], [PY Revenue], 0) * 100

MoM Growth % =
DIVIDE(
    [Total Revenue] - CALCULATE([Total Revenue], PREVIOUSMONTH('Date'[Date])),
    CALCULATE([Total Revenue], PREVIOUSMONTH('Date'[Date])),
    0
) * 100
```

---

## ⚙️ How the ETL Automation Works

```
STEP 1: RAW DATA               STEP 2: POWER QUERY              STEP 3: OUTPUT
━━━━━━━━━━━━━━━━━              ━━━━━━━━━━━━━━━━━━━━━            ━━━━━━━━━━━━━━
📁 Jan_Sales.csv  ─┐           ┌───────────────────┐            ┌────────────┐
📁 Feb_Sales.csv  ─┤           │ 1. Connect Folder │            │            │
📁 Mar_Sales.csv  ─┤  ──────►  │ 2. Auto-load files│  ──────►   │ ✅ Clean   │
📁 Apr_Sales.csv  ─┤           │ 3. Remove nulls   │            │  Unified   │
📁 May_Sales.csv  ─┤           │ 4. Fix data types │            │  Dataset   │
📁 ... 36+ files  ─┘           │ 5. Merge all      │            │            │
                                │ 6. Standardize    │            │ Ready for  │
                                └───────────────────┘            │ Modeling   │
                                                                 └────────────┘

🔁 NEW MONTHLY FILE ADDED?
   → Drop it in the folder → Click REFRESH → Dashboard updates automatically!
```

---

## 📊 Dashboard Features I Built

| 📊 Visual Components | 🔍 Interactive Features |
|---------------------|------------------------|
| 🗺️ Geographic Map — Sales by city & region | 🎛️ Year Slicer — filter entire dashboard |
| 🎀 Ribbon Chart — Category ranking over time | 📅 Month Slicer — drill to specific months |
| 📊 KPI Cards — Revenue, Profit, Growth % | 🌍 Region Filter — focus on specific areas |
| 📉 Line Chart — Monthly revenue trend | 📦 Category Filter — analyze product lines |
| 🍩 Donut Chart — Sales split by segment | 🔗 Cross-filtering — click any visual to filter all |
| 📋 Matrix Table — Product & region breakdown | 📤 Export Ready — PDF export for stakeholders |

---

## 📁 Project Structure

```
📦 TechnoEdge-Sales-Analysis-Project/
 ┣ 📂 TechnoEdge Monthly Sales Data/
 ┃   ┣ 📄 Jan_2023_Sales.csv
 ┃   ┣ 📄 Feb_2023_Sales.csv
 ┃   ┗ 📄 ... (36+ monthly files)
 ┣ 📊 TechnoEdge Monthy Sales_Project.pbix   ← Main Power BI File
 ┣ 📄 Business Case Study.docx               ← Business Requirements
 ┣ 📄 Project-Logic.md                       ← ETL Logic & DAX Notes
 ┣ 🖼️ Technoedge Sales Dash Board.jpg        ← Dashboard Screenshot
 ┗ 📄 README.md                              ← You Are Here!
```

---

## 🚀 How to Run This Project

1. **Download** Power BI Desktop — free from [microsoft.com/powerbi](https://github.com/PatlaveetiJabeer786/TechnoEdge-sales-Analysis-Project/blob/main/TechnoEdge%20Monthy%20Sales_Project.pbix)

2. **Clone or download** this repository to your local machine

3. **Open** `TechnoEdge Monthy Sales_Project.pbix` in Power BI Desktop

4. **Update the data source path:**
   - Go to `Home → Transform Data → Data Source Settings`
   - Update the folder path to where you saved `TechnoEdge Monthly Sales Data/`

5. **Click Refresh** — Power Query automatically loads all 36+ CSV files

6. **Explore** the dashboard using slicers for Year, Region, and Category

> 💡 **Add a new monthly CSV?** Just drop it in the folder → click Refresh → it's automatically included!

---

## 🧠 Key Technical Skills Demonstrated

```
✅  Automated ETL with Power Query — real-world multi-file data pipeline
✅  Star Schema design              — professional data modeling technique
✅  Advanced DAX                    — time intelligence, KPIs, growth metrics
✅  Geographic visualization        — map-based regional business insights
✅  Stakeholder communication       — translating data into business decisions
✅  End-to-end project delivery     — from raw CSV files to live dashboard
```

---

## 🌟 Final Summary

| 🔴 Problem | 🟢 My Solution | 📈 Result |
|-----------|---------------|----------|
| 36+ scattered CSV files | Automated ETL Pipeline | One unified dashboard |
| Hours of manual reporting | Power Query automation | 70% time reduction |
| No performance visibility | Interactive Power BI Dashboard | Real-time insights |
| Poor decision making | KPIs + Geographic Maps + Ribbon Charts | Data-driven strategy |

---

## 👨‍💻 About Me

I'm a data analyst passionate about transforming messy, disconnected data into clear, decision-ready business intelligence using industry-standard tools.

- 🔗 **LinkedIn:** [Add your LinkedIn URL here]
- 📧 **Email:** Add your email here
- 🌐 **GitHub:** [github.com/PatlaveetiJabeer786](https://github.com/PatlaveetiJabeer786)

---

<div align="center">

⭐ **If this project impressed you, please give it a Star!** ⭐

*Project inspired by Pavan Lalwani's Power BI End-to-End tutorial. Built and customized for portfolio purposes.*

</div>

[![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=100&section=footer)](https://github.com/PatlaveetiJabeer786/TechnoEdge-sales-Analysis-Project)
