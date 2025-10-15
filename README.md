# Insurance-Risk-Analysis
Perfect 👍 Bhagyashree!
Based on your uploaded files (**Business Requirements.docx** and **Insurance Risk Analysis.pdf**), here’s a **professional GitHub README** and a **Maven Analytics portfolio description** for your **Power BI project: “Insurance Risk & Claims Analysis”**.
 
## 🧾 **GitHub README – Insurance Risk & Claims Analysis (Power BI Project)**

### 🏠 Project Overview

The **Insurance Risk & Claims Analysis Dashboard** is an interactive Power BI report designed to help insurance companies gain insights into policyholder demographics, claim frequency, and risk patterns.
It centralizes policy and claim data from multiple sources, empowering stakeholders to make **data-driven business decisions**.

### 🎯 **Business Objective**

An insurance company wanted to understand:

* How many policies are active and how claims are distributed.
* Which demographics (age, gender, education, etc.) influence claim frequency and amounts.
* The relationship between car details and claim behavior.
* Regional and lifestyle-based risk patterns.

The goal was to create a **centralized analytical dashboard** with KPIs and charts that offer both a high-level overview and deep insights.

### 📊 **Key Performance Indicators (KPIs)**

* **Total Policies:** 37,542
* **Total Claim Amount:** $187.8M
* **Average Claim Frequency:** 0.51
* **Average Claim Amount:** $5,000

### 📈 **Dashboard Insights**

* **Car Use Analysis:** Commercial car users account for $37.41M of total claim amount, while private users contribute $150.4M.
* **Age Group Analysis:** The age group 56–65 recorded the highest total claim amount (~$36M).
* **Education & Marital Status:** Single policyholders with a Bachelor’s degree recorded the highest claim volume ($38.7M).
* **Geographical Coverage:** Urban and Highly Urban areas together account for nearly 40% of total claims.
* **Car Year Impact:** Older cars (pre-2005) have noticeably lower claim amounts compared to newer vehicles.


### 🧮 **Tools & Technologies**

| Tool            | Purpose                                 |
| --------------- | --------------------------------------- |
| **Power BI**    | Dashboard creation & data visualization |
| **Excel / CSV** | Data storage & preprocessing            |
| **DAX**         | Data modeling and measure creation      |
| **Power Query** | Data transformation and cleaning        |



### 🧠 **DAX Logic Example**

```DAX
Age Group =
SWITCH(
    TRUE(),
    insurance_data_car[Age] >= 15 && insurance_data_car[Age] <= 25, "15-25",
    insurance_data_car[Age] >= 26 && insurance_data_car[Age] <= 35, "26-35",
    insurance_data_car[Age] >= 36 && insurance_data_car[Age] <= 45, "36-45",
    insurance_data_car[Age] >= 46 && insurance_data_car[Age] <= 55, "46-55",
    insurance_data_car[Age] >= 56 && insurance_data_car[Age] <= 65, "56-65",
    insurance_data_car[Age] >= 66 && insurance_data_car[Age] <= 75, "66-75",
    insurance_data_car[Age] > 75, "76+",
    BLANK()
)

### 💡 **Key Learnings**

* Building dynamic visualizations in Power BI using DAX measures.
* Understanding insurance risk factors through multi-dimensional data.
* Designing dashboards that are visually insightful and business-relevant.
* Translating raw business requirements into meaningful analytics.


### 📷 **Dashboard Preview**

*(Attach a dashboard screenshot here or link to your Power BI service)*
Example:

<img width="1589" height="955" alt="image" src="https://github.com/user-attachments/assets/6364388d-6c3a-48e1-b96e-2ad21bfc47d0" />



---

### 🧑‍💻 **Developed by**

**Bhagyashree Dahima**
📊 Data Analyst | Excel • SQL • Power BI • Python
🔗 [LinkedIn Profile](https://www.linkedin.com/in/bhagyashree-dahima-337282291/)


## 🚀 **Next Steps**

* Predict claim probabilities using machine learning in Python.
* Add drill-through filters for deeper policy-level insights.
* Integrate policy renewal and premium optimization metrics.
