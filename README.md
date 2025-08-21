---

# 🏥 Sports Injury Analytics Report (Power BI)

This Power BI report provides a **comprehensive analysis of sports injuries**, focusing on injury trends, causes, treatments, and player recovery outcomes. The goal is to transform raw injury data into **actionable insights** for coaches, analysts, and medical teams.

---

## 📊 Report Overview

The report is designed across **5 interactive pages** with drilldowns, KPIs, and advanced DAX measures to uncover hidden insights:

### **Page 1 – Injury Overview & Trends**

* Timeline Area Chart showing injuries over time
* Drilldowns by **Body Part → Injury Type → Injury Cause → Surface Type**
* KPI cards for **Total Injuries, Recovery Days, Fully Recovered %**
<img width="1499" height="847" alt="Screenshot_41" src="https://github.com/user-attachments/assets/342e037d-a22c-4bb8-923d-9436bf400d2b" />

### **Page 2 – Player Risk and Performance Factor**

* Scatter Plot: **Avg Recovery Days vs. Treatment Cost**
* Breakdown by Treatment Method, Injury Type, Cause, and Surface
* Measures to identify the **most effective treatment methods** (highest fully recovered outcome)
* Median vs. Average recovery day comparisons
<img width="1502" height="846" alt="Screenshot_42" src="https://github.com/user-attachments/assets/cf4dee21-9994-4f13-ab45-0d440d294515" />

### **Page 3 – Outcome and Effectiveness**

* Visuals showing **Sports with the most injuries**
* Breakdown of injuries by **Body Part** and **Injury Cause**
* Insights into which **sports pose the highest risk** for certain injuries
<img width="1500" height="845" alt="Screenshot_43" src="https://github.com/user-attachments/assets/61895304-72ec-46f0-aae3-51f7958b153c" />

### **Dipe Dive Page 1 – Body Part Visual Insights**

* Human body image displaying:

  * Total injuries by body part
  * % contribution to total injuries
  * Most affected sport for that body part
  * Most effective treatment method for recovery
<img width="1501" height="847" alt="Screenshot_45" src="https://github.com/user-attachments/assets/aed83681-cf12-4b6d-91b7-68cc86786e48" />

### **Dipe Dive Page 2 – Player Breakdown**

* Matrix with **detailed injury history per player**
* Columns include: Player Name, Body Part, Injury Type, Cause, Recovery Days, Outcome, Treatment Method, and Sport
* Useful for **player-level monitoring and decision-making**
<img width="1499" height="845" alt="Screenshot_44" src="https://github.com/user-attachments/assets/026722c4-a30b-4902-9d6f-3dff878edffa" />

---

## ⚙️ Key Measures & Calculations

Some of the DAX measures created for this report include:

* **Median Days to Recovery**

  ```DAX
  Median Days to Recovery = MEDIAN(FactInjury[DaysToRecovery])
  ```

  → Identifies the midpoint of recovery times, giving a more reliable insight than averages (which can be skewed by extreme values).

* **Most Effective Treatment**
  → Returns the treatment method with the highest proportion of *fully recovered* outcomes.

* **Sport with Most Knee Injuries**
  → Identifies the sport most associated with knee-related injuries.

* **Most Affected Body Part & Injury Cause**
  → Separate measures to highlight which body parts and causes account for the majority of injuries.

---

## 🧠 Insights Derived

* Certain **sports are more prone to specific body part injuries** (e.g., knees in football).
* Some **treatment methods are consistently more effective** in achieving full recovery.
* **Median recovery days** is often more realistic than average when assessing timelines.
* Injuries are concentrated around a few **high-risk causes and surfaces**, providing a focus area for prevention strategies.

---

## 🎯 Use Cases

This report can be used by:

* **Sports Analysts** – to monitor injury patterns and compare across sports.
* **Medical Teams** – to evaluate treatment effectiveness and recovery timelines.
* **Coaches & Management** – to make data-informed decisions on player fitness and availability.

---

## 🛠️ Tools & Techniques

* **Power BI** for data modeling and visualization
* **DAX** for advanced calculations
* **Interactive Tooltips** for deeper insights within visuals
* **Drilldowns & Hierarchies** for multi-level exploration

### VIEW REPORT HERE: [CLICK HERE](https://app.powerbi.com/view?r=eyJrIjoiYWJjZDYxY2EtM2I3Yy00ZDIwLTgzMGQtNWU3ZWEwZDVjYWZmIiwidCI6IjQ2NTRiNmYxLTBlNDctNDU3OS1hOGExLTAyZmU5ZDk0M2M3YiIsImMiOjl9)
---

## 📌 Next Steps

* Incorporate **predictive modeling** to forecast injury risks.
* Add **player workload and performance data** for more holistic analysis.
* Enhance **real-time monitoring** by connecting with live injury tracking systems.

---

✅ This project highlights the **power of data storytelling in sports analytics**—turning injury records into **strategic insights for performance and prevention**.

---
