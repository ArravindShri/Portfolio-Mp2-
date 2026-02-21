# Portfolio-Mp2-
Second Mock Project for the Portfolio- NYC Taxi Analytics 
# 🚕 NYC Taxi Analytics Dashboard

End-to-end data analytics project analyzing **1.4 million NYC taxi trips** using SQL Server and Power BI.

## 🔗 [View Live Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTAyOTc3NWUtNzFjOS00NDM0LWJmMWEtY2Y5MGRhZGQ3MTIyIiwidCI6ImZlZjEwZjBjLTVkY2MtNDU5OC05N2VkLTY2M2MyYmNlNDJhNSJ9&pageName=c0779445acdec480371d)

---

## 🛠️ Tech Stack
- **Database:** SQL Server
- **Visualization:** Power BI (Desktop + Service)
- **Languages:** SQL, DAX
- **Data Modeling:** Star Schema

---

## 🚀 What I Built

**Data Pipeline:**
1. Imported 1.45M trip records from Kaggle dataset
2. Cleaned data (removed 9,480 invalid records)
3. Created 4 derived tables using SQL transformations
4. Built star schema with fact/dimension relationships
5. Designed 6 DAX measures for dynamic calculations
6. Created 4-page interactive dashboard

**Tables Created:**
- `time_dimension` - Parsed datetime into components (hour, day, month, time categories)
- `trip_metrics` - Enhanced trip data with calculated fields
- `daily_summary` - Aggregated daily performance metrics
- `zones` - Geographic grouping into 12 NYC zones with real names

**DAX Measures:**
- Total Trips, Avg Duration, Total Passengers, Weekend %, Max Duration

---

## 🔍 Key SQL Techniques
✅ Data Cleaning with complex WHERE conditions  
✅ Window Functions (RANK, LAG, LEAD)  
✅ Date/Time parsing and categorization  
✅ Multi-level aggregations (GROUP BY)  
✅ CASE statements for conditional logic  
✅ CTEs for readability  
✅ Star schema design

---

## 📈 Key Insights
- **Peak month:** March 2016 (254K trips)
- **Busiest hours:** 6-8 PM evening rush
- **Top zone:** "Other NYC Areas" (661K trips, 46%)
- **Avg trip:** 15.95 minutes
- **Weekend trips:** 28.53% of total
- **Solo riders dominate:** 73% of trips had 1 passenger

---

## 👤 Author
**Arravind Shri**  
Aspiring Data Analyst | Transitioning from Customer Success to Analytics  
📧 shri@arravindportfolio.tech

---

**Dataset:** NYC Taxi & Limousine Commission (Jan-Jun 2016)  
**Project Type:** Mock Project #1 of 10-project portfolio series
