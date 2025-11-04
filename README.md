# Power-BI-project-in-45-min
A Power BI dashboard project analyzing hospital admissions, demographics, and medical conditions using DAX and Power Query. Built in 45 minutes, this report transforms raw healthcare data from Kaggle into actionable insights for data-driven healthcare management.

## View Presentation Slides
https://gamma.app/docs/Healthcare-Analytics-Dashboard-Transforming-Data-into-Actionable--cwotslal3ubbikf

# Healthcare Analytics Dashboard – Power BI Project

## 📊 Overview
This Power BI project analyzes hospital admissions, patient demographics, and medical conditions using a synthetic healthcare dataset from Kaggle. The dashboard provides data-driven insights to help improve decision-making and healthcare efficiency.

## ⚙️ Tools & Technologies
- **Power BI** for visualization  
- **DAX (Data Analysis Expressions)** for measures and KPIs  
- **Power Query** for data cleaning and transformation  

## 🧮 Key DAX Measures
- `Total Admissions = COUNTROWS(healthcare_dataset)`  
- `Average Age = AVERAGE(healthcare_dataset[Age])`  
- `Top Hospital Admissions = RANKX(ALL(healthcare_dataset[Hospital]), [Total Admissions], , DESC)`  
- `Male %` and `Female %` for gender distribution  
- `Patients per Condition` to analyze top medical cases  

## 📈 Dashboard Features
- KPI cards for total admissions and average age  
- Bar and pie charts for condition and gender breakdowns  
- Line chart for yearly admissions  
- Interactive slicers for hospital and year filters  

## 🔍 Insights
- Over **55,500 total admissions** and **40,235 unique patients** analyzed  
- Identified top 5 hospitals and frequent medical conditions  
- Balanced gender ratio and steady yearly admission trends  

## 🚀 Recommendations
- Automate annual data refresh for real-time insights  
- Add KPIs like average stay duration and treatment costs  
- Use analytics to improve hospital capacity planning and preventive care  

---

🕒 **Built in 45 minutes** | 💡 *Empowering healthcare decisions through data visualization*
