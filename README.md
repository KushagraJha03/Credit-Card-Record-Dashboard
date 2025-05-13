# 💳 Credit Card Records Dashboard  
**🛠️ Tool Used:** Power BI & MySQL  


---

🎯 **Objective**  
To create a weekly credit card dashboard that helps track and analyze credit card revenue, interest earned, customer satisfaction, and segment-wise performance. This dashboard enables banks to identify growth opportunities, improve customer engagement, and optimize revenue generation strategies.

---

🧩 **Problem Statement**  
Banks accumulate vast amounts of credit card transaction data weekly. However, without proper visualization and segmentation, extracting valuable insights becomes challenging.  
This dashboard combines transactional and demographic data to answer crucial business questions such as:

- Which customer segments generate the most revenue?
- What is the average Customer Satisfaction Score (CSS)?
- Which card types perform best?
- How are revenue and interest trending week-over-week?

---

🔧 **Steps Followed**

1. **Data Importation**  
   - Imported customer and credit card transaction datasets from **MySQL** into Power BI using **Power Query**.

2. **Data Cleaning & Transformation**  
   - Merged datasets on Customer ID  
   - Removed duplicates and handled missing values  
   - Ignored <1% nulls in interest values for cleaner insights  

3. **Data Modeling & Column Engineering**  
   - Created custom columns to group customers by **age ranges**, **education**, and **profession** for segmentation  
   - Built relationships between fact and dimension tables  

4. **DAX Measures Created**  
   - Total Revenue  
   - Interest Earned  
   - Customer Satisfaction Score (CSS)  
   - Total Customers  
   - Weekly Transaction Volume  

5. **Dashboard Design**  
   - 📊 **Bar charts** for revenue comparison across gender, education, and profession  
   - 📈 **Line chart** for weekly revenue and interest trends  
   - 🧮 **Card visuals** for KPIs: Revenue, Interest, CSS  
   - 🥧 **Pie charts** for card type and demographic distribution  
   - 📌 **Slicers** for Region, Gender, Education, Card Type  

 

---

📊 **Key KPIs & Metrics**

| Metric                      | Value         |
|----------------------------|---------------|
| Total Revenue              | $55M+         |
| Total Interest Earned      | $7.8M         |
| Weekly Transactions Tracked| $45M+         |
| Customer Satisfaction Score| 3.19 / 5      |
| Total Customers Analyzed   | ~130,000      |

---

📌 **Key Insights**

- 🎓 Graduates generated **$22M+** in revenue, leading all education segments  
- 🧑‍💼 Businessmen contributed **$17.4M**, the most profitable profession segment  
- 👨 Male customers generated **$31M+**, outperforming female customers  
- 💳 **47%** of customers hold personal cards, contributing the most revenue  
- ⚠️ **57%** of users are neutral or dissatisfied, highlighting room for service improvement  
- 🧑‍🦱 The **25–50 age group** was the most engaged and profitable demographic  

---

✅ **Conclusion**

This Credit Card Records Dashboard empowers banking analysts and decision-makers to:

- Track revenue, interest, and satisfaction trends in real time  
- Segment performance by demographics and card type  
- Identify underperforming customer groups for targeted action  
- Support strategic decisions in marketing, retention, and credit offerings  

---
**📎 Dashboard:**![Image](https://github.com/user-attachments/assets/37e5cda5-ba3e-4eef-9f51-30e2e95a50f5)

