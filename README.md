<img width="925" height="425" alt="real estate image2" src="https://github.com/user-attachments/assets/c883fb16-aaa0-42a5-ae45-5920232fc8fe" />

## 🏡 Real Estate Data Analytics Dashboard | Power BI

## 📌 Project Overview:
  This Power BI dashboard provides data-driven insights for the Real Estate industry. It helps analyze market performance, property trends, pricing insights, and neighborhood details to support strategic decision-making for agents, investors, and real estate managers.

---

## 🎯 Objectives:

- 📈 Analyze market value, listed price, and property sales trends
- 🏘️ Compare property performance by location and neighborhood
- 👨‍💼 Evaluate agent, office, and property type efficiency
- 📍 Understand real estate market condition status
- 💹 Support investment decisions with KPI insights

---

## 📊 Key Features & Visuals

### **Dashboard Highlights**
| Visual Description | Metrics / Insights |
|--------------------|--------------------|
| 💰 Market Value Trend | Sum & Avg MarketValue by SoldDate |
| 🏙️ Neighborhood Overview | Crime Rate, Income, Walkability Score |
| 🏠 Property Distribution | Count of PropertyType, ParkingSpaces |
| 👤 Agent Performance | Count of PropertyID by Agent & Region |
| 🏢 Office Analytics | Manager-wise property count, establishment year |
| 🎯 KPI Cards | Target, trend axis & variance indicators |
| 📍 Map Visual | Property locations and density |

---
## 📊 Dashboard Preview:

<img width="590" height="335" alt="Real_Estate_Performance_Insight_Dashboard" src="https://github.com/user-attachments/assets/489e3dd2-298a-43e7-8f24-269cc82074bd" />



# 📌 Key Performance Indicators (KPIs):

- 💵 Total Market Value
- 🧾 Total Listed Price
- 🏠 Count of Properties
- 👨‍💼 Total Agents
- 🏘️ Average Neighborhood Walkability & Income
- 🎯 Sales Target Achievement Gauge
---

## 📂 Dataset Structure
### **Property Table**
- PropertyID, Address, City, State, zipcode
- ListedPrice, MarketValue, SoldDate
- SquareFeet, ParkingSpaces, PropertyType, FurnishingStatus
- ConditionStatus, NeighborhoodID

### **Neighborhood Table**
- NeighborhoodID, NeighborhoodName
- City, CrimeRate, SchoolingRate, WalkabilityScore, AvgIncome

### **Agents**
- AgentID, FullName, Region, Phone, ExperienceYears

### **Offices**
- OfficeID, OfficeName, ManagerName, City, State, EstablishedYear

---

## 🧠 Insights Provided
- 📈 Market growth over time and peak sales periods
- 🏡 Best performing neighborhoods for investment
- 🏗️ Preferred property types and size trends
- 📞 Top-performing agents & offices
- 💡 Improvement areas based on condition status & crime rate

---

## 🔧 Tools & Technology
| Tool | Purpose |
|------|---------|
| Power BI | Dashboard & Visualizations |
| SQL / Excel | Data Cleaning & Modeling |
| DAX | Calculated Measures & KPIs |
| GitHub | Version control & sharing project |

---

## 🧾 Example DAX Measures
```DAX
Total Market Value = SUM(Property[MarketValue])
Average Listed Price = AVERAGE(Property[ListedPrice])
Total Properties = COUNT(Property[PropertyID])
