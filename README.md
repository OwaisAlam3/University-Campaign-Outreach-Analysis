# 🎓 University Campaign Outreach Analysis

## 📘 Overview
This project explores the performance of university outreach campaigns to understand how effectively prospective students were contacted and converted. The data represents applicant information, outreach outcomes, and campaign performance metrics for admission-related activities.

## 🧩 Objectives
- Identify how many applicants were successfully connected by outreach specialists.
- Compare outreach effectiveness across campaigns and callers.
- Analyze geographic distribution of applicants.
- Visualize campaign performance through an interactive Power BI dashboard.

---

## 📊 Dataset Overview
**Columns:**
- `Applicant ID`
- `Phone Number`
- `Country`
- `University` (Illinois Institute of Technology)
- `Received At`
- `Caller Name`
- `Outcome`
- `Remarks`
- `Campaign ID`
- `Campaign Name`
- `Campaign Category` (Pre / Post Admission)
- `Campaign Start Date`
- `Application Date`

**Dataset Size:** 6,498 records (after cleaning)

---

## ⚙️ Data Cleaning (Excel)
Performed comprehensive cleaning before visualization:
- ✅ Fixed inconsistent date formats (`YYYY-MM-DD → Date only`)
- ✅ Removed invalid and non-numeric Applicant IDs
- ✅ Filtered out IDs with more than 6 digits or exponential formats
- ✅ Removed emails from `Country` column
- ✅ Standardized text casing and trimmed extra spaces
- ✅ Removed duplicate records
- ✅ Aligned Campaign and Applicant IDs for accuracy

---

## 📈 Exploratory Data Analysis (Excel)
Key analyses performed:
- Distribution of outreach outcomes (Connected vs Not Connected)
- Applications per campaign and outreach specialist
- Geographic distribution of applicants
- Conversion rate (Connected ÷ Total per Specialist)
- Summary metrics for campaign category (Pre vs Post Admission)

---

## 📊 Dashboard (Power BI)
### Layout
- **Top Title Bar:** Project title with slicers (Campaign, Category, Outcome)
- **Left Section:** KPI Cards
  - 🧾 Total Applicants
  - 🎯 Conversion Rate
  - 🌍 Countries Covered
- **Right Section:**  
  - 📊 Bar Chart — Calls handled per specialist  
  - 🗺️ Map — Applicants by Country  

### Interactivity
- Dynamic filters by campaign and outcome  
- Slicers sync visuals across the dashboard  
- Clean, minimal, and presentation-ready design  

---

## 🧠 Key Insights
- Total Applicants: **6,498**  
- Not Connected: **4,054 (62%)**  
- Conversion Rate: **~38% overall**
- Rudra and Prajwal managed the largest applicant volumes.
- Most applicants came from **India**, followed by other Asian and European countries.

---

## 🧰 Tools Used
- **Microsoft Excel** — Data cleaning, transformation, and pre-EDA
- **Microsoft Power BI** — Dashboard creation and visualization
- **GitHub** — Version control and public portfolio sharing

---
