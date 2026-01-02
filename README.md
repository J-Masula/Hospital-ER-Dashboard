# Hospital-ER-Dashboard
A PBI dashboard that analyzes ER patient flow, wait times, referrals, and demographics to support operational insights and decision-making.

## Dashboards Overview

### **Dashboard 1: Monthly View**
**Objective:**  
Monitor ER performance on a **month-by-month basis** to identify trends, peak periods, and areas requiring improvement.
**Key Visuals:**
- Patient Admission Status (Admitted vs. Non-Admitted)
- Patient Age Distribution (10-year age intervals)
- Department Referrals
- Timeliness (% of patients seen within 30 minutes)
- Gender Distribution
- Racial Demographics
- Patient Volume by Day and Hour

---
### **Dashboard 2: Consolidated View**
**Objective:**  
Provide a **holistic summary of hospital performance** across a **selected date range**.

**Key Features:**
- Aggregated metrics from the Monthly View
- Date range slicers for flexible analysis
- Trend analysis over longer time periods

---
### **Dashboard 3: Patient Details**
**Objective:**  
Enable **granular, patient-level analysis** for detailed investigation and operational troubleshooting.

**Fields Included:**
- Patient ID  
- Patient Full Name  
- Gender  
- Age  
- Admission Date  
- Patient Race  
- Wait Time  
- Department Referral  
- Admission Status  

This dashboard supports detailed review and validation of individual patient records.

---

### **Dashboard 4: Key Takeaways**
**Objective:**  
Summarize insights from all dashboards and translate them into **clear, actionable recommendations** for stakeholders.

**Focus Areas:**
- Key patterns and trends
- Operational bottlenecks
- Anomalies in wait times and patient volume
- Data-driven recommendations to optimize ER operations and patient care

---

## 📈 Key Performance Indicators (KPIs)

### **Number of Patients**
- Measures total ER visits per day
- Displayed using an **area sparkline** to highlight daily trends and peak periods

### **Average Wait Time**
- Calculates the average time patients wait before being attended
- Visualized with an **area sparkline** to identify days with higher operational pressure

### **Patient Satisfaction Score**
- Tracks daily average patient satisfaction
- Helps correlate service quality with wait times and patient volume

### **Number of Patients Referred**
- Counts daily referrals to specific hospital departments
- Highlights departments with consistently high demand

---
## 🛠 Tools & Technologies
- **Power BI Desktop**
- **DAX** for KPIs and measures
- **Data Modeling** using fact and dimension tables
- Interactive slicers and drill-through functionality

