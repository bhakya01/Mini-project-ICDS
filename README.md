Here's a professional **GitHub README** version of your **ICDS Nutrition Dashboard** with concise sections and **key insights**.

---

# 📊 ICDS Nutrition Dashboard | Power BI Project

## 📌 Project Overview

The **ICDS (Integrated Child Development Services) Nutrition Dashboard** is an end-to-end data analytics project developed using **Microsoft Excel, Power Query, and Power BI**. The project focuses on cleaning, transforming, modeling, and visualizing government nutrition data to monitor Anganwadi Centre performance and beneficiary coverage.

The dashboard enables stakeholders to analyze nutrition, infrastructure, workforce, and health indicators through interactive visualizations for better decision-making.

---

# 🎯 Project Objectives

* Improve monitoring of nutrition programmes for children (0–6 years), pregnant women, and lactating mothers.
* Track Anganwadi Centre operational performance.
* Analyze nutrition and health indicators.
* Monitor beneficiary coverage across states and districts.
* Support evidence-based policy and operational decisions using Power BI.

---

# 📂 Data Source

| Category | Details                                 |
| -------- | --------------------------------------- |
| Dataset  | POSHAN Statistics (Government of India) |
| Source   | Google Dataset Search                   |
| Year     | 2025–2026                               |
| Domain   | ICDS Nutrition & Child Development      |

---

# 🛠️ Tools & Technologies

* Microsoft Excel
* Power Query
* Power BI Desktop
* DAX (Data Analysis Expressions)
* Data Modeling
* CSV Files

---

# 📊 Dataset Information

* Government Nutrition Dataset
* Three CSV Files

  * ANG1
  * Health
  * State

### Dataset contains

* Anganwadi Centres
* Anganwadi Workers
* Anganwadi Helpers
* Beneficiary Information
* Health IDs
* Nutrition Indicators
* Infrastructure Details
* Maternal Health
* Child Nutrition
* Aadhaar Verification
* THR & HCM Distribution

---

# 🔄 Data Preprocessing

Performed using **Excel** and **Power Query**

✔ Removed unnecessary columns

✔ Promoted headers

✔ Changed data types

✔ Merged Queries

✔ Expanded related tables

✔ Renamed columns

✔ Data validation

✔ Relationship creation

---

# 🧩 Data Model

### Relationships

| From   | Relationship | To    |
| ------ | ------------ | ----- |
| Health | Many-to-Many | State |
| Health | One-to-One   | ANG1  |
| State  | One-to-One   | ANG1  |

---

# 📈 DAX Measures

### ANG1

* Aadhaar Verified
* Eligible Beneficiaries
* Total Workers
* Worker per Centre

### Health

* AWC Open Rate %
* Children (0–2 Years)
* Children (3–6 Years)
* Functional Toilet %
* Total AWC
* Total Health IDs
* Total Urban AWC

### State

* Total Anganwadi Workforce

---

# 📊 Dashboard Features

### KPI Cards

* Total Anganwadi Workers
* AWC Open Rate
* Children (0–6 Months)
* Children (0–2 Years)
* Children (3–6 Years)
* Eligible Beneficiaries

---

### Visualizations

* Column Chart
* Clustered Column Chart
* Stacked Bar Chart
* Stacked Area Chart
* Pie Chart
* Donut Chart
* Funnel Chart
* Gauge Chart
* Area Chart
* Map
* Matrix
* Table
* Interactive Slicers

---

# 📌 Key Dashboard Metrics

| Metric                  |          Value |
| ----------------------- | -------------: |
| Total Anganwadi Workers |  **6 Million** |
| Children (3–6 Years)    | **11 Million** |
| Eligible Beneficiaries  |      **2,048** |
| Target Beneficiaries    |      **4,096** |
| AWC Open Rate           |        **27%** |
| Dashboard Years         |  **2025–2026** |

---

# 💡 Key Insights

### 👶 Beneficiary Coverage

* More than **11 million children (3–6 years)** are covered under ICDS nutrition services.
* The dashboard monitors children, pregnant women, lactating mothers, and adolescent girls across multiple states.

---

### 👩‍🏫 Workforce Analysis

* Around **6 million Anganwadi Workers** support ICDS programme implementation.
* Workforce distribution varies significantly across states and districts.

---

### 🏢 Infrastructure Analysis

* Availability of **functional toilets**, **drinking water**, and **own buildings** differs across states.
* Infrastructure gaps indicate areas requiring additional investment.

---

### 🏥 Health & Digital Services

* Aadhaar verification and Health ID creation improve beneficiary identification and digital tracking.
* Digital coverage enables more effective monitoring of nutrition programmes.

---

### 📍 Operational Performance

* The **AWC Open Rate of approximately 27%** highlights opportunities to improve service delivery and operational efficiency.
* State-wise comparisons help identify underperforming regions.

---

### 🍲 Nutrition Monitoring

* Dashboard tracks:

  * Underweight children
  * Stunted children
  * Wasting (SAM/MAM)
  * Obesity
  * Pregnant women
  * Lactating mothers
  * THR distribution
  * Hot Cooked Meal distribution

---

# 📈 Analytics Used

### 📊 Descriptive Analytics

Summarizes workforce, beneficiaries, infrastructure, and nutrition indicators across India.

### 🔍 Diagnostic Analytics

Identifies reasons for regional performance differences using workforce, infrastructure, and health metrics.

### 📉 Predictive Analytics

Supports forecasting of beneficiary growth, workforce demand, and nutrition programme requirements.

### ✅ Prescriptive Analytics

Helps decision-makers prioritize infrastructure improvements, workforce allocation, and beneficiary verification.

---

# 🏆 Project Outcomes

* Built an interactive Power BI dashboard.
* Created a scalable data model using three related datasets.
* Developed reusable DAX measures.
* Enabled dynamic filtering using slicers.
* Improved reporting with interactive visualizations.
* Supported evidence-based monitoring of ICDS nutrition programmes.

---

# 📌 Conclusion

The **ICDS Nutrition Dashboard** provides a comprehensive view of Anganwadi operations, beneficiary coverage, nutrition indicators, and infrastructure across multiple states. By combining Excel, Power Query, Power BI, DAX, and data modeling, the project enables stakeholders to monitor programme performance, identify service gaps, and make informed, data-driven decisions to strengthen child and maternal nutrition services in India.
