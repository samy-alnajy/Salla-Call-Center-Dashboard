# 📞 Salla Call Center Dashboard

A **Power BI** dashboard for analyzing call center performance across multiple projects, built on real operational data covering agent activity, call handling efficiency, and service level metrics.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard & visualizations |
| CSV | Raw data source |
| DAX | Calculated measures & KPIs |

---

## 📁 Repository Structure

```
Salla-Call-Center-Dashboard/
│
├── Salla_Project.pbix          # Power BI dashboard file
├── Sallah_Call_Center_DB.csv   # Dataset (267 records)
└── README.md                   # Project documentation
```

---

## 📊 Dataset Overview

**File:** `Sallah_Call_Center_DB.csv`  
**Records:** 267 rows | **Period:** 2022  
**Projects:** Multiple (Project A, B, C ...)

### Columns

| Column | Description |
|--------|-------------|
| `Project` | Project/team name |
| `Date` | Date of the record |
| `Month` | Month label |
| `Forecasted Calls` | Expected call volume |
| `Calls Offered` | Total calls received |
| `Calls Handled` | Calls successfully answered |
| `Calls Handled Within Threshold` | Calls answered within SLA time |
| `Calls Abandon` | Calls dropped before being answered |
| `ASA` | Average Speed of Answer (seconds) |
| `Answer Time` | Total answer time |
| `Agent Name` | Handling agent |

---

## 📈 Key KPIs Tracked

- ✅ **Service Level** — % of calls handled within threshold
- 📉 **Abandon Rate** — % of calls dropped by customers
- ⏱️ **ASA (Average Speed of Answer)** — How fast agents respond
- 📋 **Calls Handled vs Offered** — Efficiency ratio per day/agent
- 👤 **Agent Performance** — Calls handled per agent

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `Salla_Project.pbix` in **Power BI Desktop**
3. If prompted, update the data source path to point to `Sallah_Call_Center_DB.csv`
4. Refresh the data and explore the dashboard

> ⚠️ **Note:** Power BI Desktop is required to open `.pbix` files. Download it free from [Microsoft](https://powerbi.microsoft.com/desktop/).

---

## 👨‍💻 Author

**Samy Mohamed Alnajy**  
Data Analyst | Computer Science & AI Student  
📧 Connect on [LinkedIn](#) <!-- Add your LinkedIn URL here -->
