# Road Accidents Analysis


<p align="center">  <img src="https://i.pinimg.com/1200x/64/e1/b7/64e1b78dea313afc046ca87a92bcc87a.jpg"
       alt="Road Accidents Dashboard"
       width="400" hight="400"></p>


- It analysis UK road accidents and casualties (2021–2022).  
- It includes KPIs, trend analysis, and breakdowns by **severity, vehicle type, road type, area (urban/rural), and time (day/night)**.



---

## Objectives

This report aims to:

- Display **total casualties and accidents (CY vs PY)**  
- Show breakdowns by **severity, vehicle type, road type, and area**  
- Compare **monthly casualty trends**  
- Visualize **urban vs rural** and **day vs night** proportions  
- Enable drill-downs for **location-level insights**

---

## Dashboard Components

1. **Executive Overview** — KPIs and YoY performance  
2. **Vehicle & Road Analysis** — by vehicle and road type  
3. **Monthly Trends** — CY vs PY trend visualization  
4. **Area & Day/Night** — donut charts for distribution  
5. **Map View** — casualties and accidents by location  

---

## Data Model

### Tables
- **Accidents** — Accidents information 
- **Calendar** — For date

### Relationship
`Calendar[Date]` → `Accidents[Date]` (one-to-many)

---

## How to Use
1. Clone this repo.
2. Open Road Accidents Analysis.pbix in Power BI Desktop.
3. Update the data source path to Road Accident Data.xlsx.
4. Refresh the data (Transform → Close & Apply → Refresh).
5. Explore the interactive visuals and slicers.

---
## Insights

- Compare Casualties CY vs PY and analyze YoY % change.
- Identify top vehicle types and road types causing most casualties.
- Observe monthly casualty fluctuations.
- Analyze urban vs rural and day vs night distribution.
