## 🏡 Real Estate Data Analytics Dashboard | Power BI
---

<img width="1200" height="630" alt="image" src="https://github.com/user-attachments/assets/89f032f7-6809-45e0-81fe-8d13ed727702" />


---

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

## 📊 Key Features & Visuals:

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

<img width="790" height="435" alt="Real_Estate_Performance_Insight_Dashboard" src="https://github.com/user-attachments/assets/489e3dd2-298a-43e7-8f24-269cc82074bd" />




---

<img width="790" height="435" alt="Real Estate Sales Performance Dashboard" src="https://github.com/user-attachments/assets/25b381ca-9785-40c5-90d0-37eaad5bde04" />




---

<img width="790" height="435" alt="Market Performance Dashboard" src="https://github.com/user-attachments/assets/fae4ff3c-c618-481a-9a10-b12cef06bbf0" />




---

<img width="790" height="435" alt="Listing Overview Dashboard" src="https://github.com/user-attachments/assets/a4efd5e1-21bb-446c-b2db-a256aa69fe27" />




---

<img width="790" height="435" alt="Real Estate Sales Performance Dashboard" src="https://github.com/user-attachments/assets/6ab253a0-e196-4a8a-9909-daf8920da8d8" />




---

<img width="790" height="435" alt="Owners   Agents Dashboard" src="https://github.com/user-attachments/assets/f801e563-3b1f-452b-a926-e35b92d9fbf1" />




---

<img width="790" height="435" alt="Owners   Properties Dashboard" src="https://github.com/user-attachments/assets/743cffb8-226d-455b-b4d3-395d18ab5ba1" />




---

<img width="790" height="435" alt="Property   Sales Dashboard" src="https://github.com/user-attachments/assets/d2ff3c2c-9d07-4e45-bbc9-a5676f607b20" />




---

<img width="790" height="435" alt="Property   Neighborhood Dashboard" src="https://github.com/user-attachments/assets/dc8a84bd-101d-44c6-92e1-095778a5667a" />




---

<img width="790" height="435" alt="Agent Dashboard" src="https://github.com/user-attachments/assets/1677d71a-8919-4432-b515-fdf49e3fa742" />




---

<img width="790" height="435" alt="Owner Insight Dashboard" src="https://github.com/user-attachments/assets/a50075b6-6859-46e3-aad4-69b1c44792d0" />




---

<img width="790" height="435" alt="Office Insight Dashboard" src="https://github.com/user-attachments/assets/19a52536-c633-4249-8e2f-7a0aaedcc389" />




---

<img width="790" height="435" alt="Neighborhood Insight Dashboard" src="https://github.com/user-attachments/assets/2a8ae07e-ef69-418e-9d21-f25d6a9a01ba" />




---

<img width="790" height="435" alt="Location Insight   Neighborhood Dashboard" src="https://github.com/user-attachments/assets/f9cfb87d-00c7-4217-a35d-3586fcfce343" />




---

<img width="790" height="435" alt="Property Features Impact Dashboard" src="https://github.com/user-attachments/assets/f1cf1fcf-7c04-45d8-9f12-d1a4d5c395d7" />





---

# 📌 Key Performance Indicators (KPIs):

- 💵 Total Market Value
- 🧾 Total Listed Price
- 🏠 Count of Properties
- 👨‍💼 Total Agents
- 🏘️ Average Neighborhood Walkability & Income
- 🎯 Sales Target Achievement Gauge
---

# 🗂️ Dataset Structure:
This project includes 5 relational tables:

- 🏠 Property — Property details (ID, Type, Listed Price, Market Value, Sold Date, Condition, SqFt, AgentID, OfficeID, OwnerID, NeighborhoodID)
- 👨‍💼 Agent — Agent info (ID, Name, Region, Phone, Experience, OfficeID)
- 🏢 Office — Office data (ID, Name, Manager, City, State, Zip, Established Year)
- 🧑‍💼 Owner — Owner details (ID, Name, Email, Phone)
- 🏘️ Neighborhood — Area details (ID, Name, City, Crime Rate, Average Income, Walkability, Schooling Rate)

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
