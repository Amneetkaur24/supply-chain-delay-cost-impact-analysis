# Supply Chain Shipment Delay Prediction

Predicting car shipment delays and estimating financial impact using machine learning and supply chain analytics.

---

# Business Problem

Automotive manufacturing depends heavily on timely delivery of critical components such as engines, transmissions, brakes, suspension systems, and infotainment modules.

Delays in any of these components can halt assembly lines and create significant financial losses.

This project analyzes supply chain shipment data to:

• Predict whether a shipment will be delayed  
• Estimate how many days the delay will last  
• Forecast the financial cost of the delay  

These insights can help supply chain managers take proactive decisions and reduce operational risk.

---
# Dashboard Preview

<img width="873" height="489" alt="image" src="https://github.com/user-attachments/assets/51355b48-5e98-4e89-8eac-e6a5bd453234" />

# Dataset Overview

The dataset contains **1010 car shipments with 65+ operational features**, including:

Supplier Information
- Supplier region
- Supplier reliability score
- Supplier performance score

Logistics Data
- Transport mode
- Route type
- Distance
- Traffic severity

Operational Factors
- Production shift
- Order urgency
- Inventory buffer usage
- Strike notices
- Weather conditions

Part-Level Information
- Engine
- Transmission
- Brake System
- Suspension
- Infotainment

Target Variables

- `Car_Delayed` (classification)
- `Delay_Days` (regression)
- `Financial_Impact_USD` (regression)

---

# Project Workflow

### 1 Data Cleaning
- Parsed date columns
- Handled categorical variables
- Feature type conversion

### 2 Exploratory Data Analysis
- Delay distribution analysis
- Financial impact distribution
- Supplier reliability analysis
- Seasonal trends

### 3 Feature Engineering
- Supplier reliability scores
- Delay flags per component
- Traffic severity index
- Supplier groups
- Reliability aggregations

### 4 Machine Learning Models

Classification Model
Predict if shipment will be delayed

Algorithms tested:
- Random Forest
- XGBoost
- CatBoost

Regression Model 1
Predict delay duration (days)

Regression Model 2
Predict financial loss due to delay

Evaluation Metrics
- Accuracy
- MAE
- RMSE
- R² Score

---

# Power BI Dashboard

The project includes an **interactive Power BI dashboard** used to explore delay patterns and operational insights.

Dashboard Highlights

• Shipment delay rate  
• Delay distribution by car component  
• Financial impact of delays  
• Seasonal shipment patterns  
• Supplier reliability analysis  

---

# Key Business Insights

Major findings from the analysis:

• **62% of shipments experienced delays**, indicating major supply chain inefficiencies.

• **Engine reliability is the strongest driver of financial loss.** Lower reliability scores lead to higher delays and costs.

• **Q1 (Jan–Mar) shows the highest delay frequency**, suggesting seasonal operational challenges.

• **Urgent orders are delayed more often**, indicating planning inefficiencies.

• **Inventory buffers are rarely used and do not significantly reduce delays.**

• **Evening production shifts show higher delay frequency and cost spikes.**

• **Transmission and suspension components show lower reliability scores**, suggesting supplier performance issues.

• **Financial impact increases sharply with delay days**, showing a near linear relationship.

---

# Tools & Technologies

Python  
Pandas  
Scikit-Learn  
CatBoost  
XGBoost  
Matplotlib  
Seaborn  
Power BI  
Jupyter Notebook  

---

# Repository Structure

```
project-name
│
├── data
│
├── notebooks
│   └── EDA_and_Modeling.ipynb
│
├── dashboard
│   └── car_shipment_dashboard.pbix
│
├── images
│   └── dashboard_screenshot.png
│
├── insights.md
│
└── README.md
```

---

# Author

Amneet Kaur  
Data Analyst | Supply Chain Analytics | Machine Learning

LinkedIn  
https://linkedin.com/in/amneetkaur24
