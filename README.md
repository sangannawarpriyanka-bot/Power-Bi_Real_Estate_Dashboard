<img width="925" height="425" alt="real estate image2" src="https://github.com/user-attachments/assets/c883fb16-aaa0-42a5-ae45-5920232fc8fe" />
# 🏠 Real Estate Market Analytics – Power BI Dashboard

## 📌 Project Overview
This Power BI project provides an analytical dashboard for real estate market performance, enabling stakeholders to monitor pricing trends, property characteristics, neighborhood insights, and sales performance. The dashboard delivers data-driven decision-making support for investors, agents, and property managers.

---

## 🎯 Objectives
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
