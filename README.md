Here is the complete, properly formatted Markdown code for your `README.md` file. You can copy this code block directly and replace the contents of your `README.md` file in your repository:

```markdown
<div align="center">

# 📊 CUSTOMER CHURN ANALYSIS

### Power BI • Data Analytics • Customer Retention • Business Intelligence

<br>

<img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Excel-Dataset-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white"/>
<img src="https://img.shields.io/badge/Power%20Query-Data%20Transformation-742774?style=for-the-badge"/>
<img src="https://img.shields.io/badge/DAX-Analytics-512BD4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Data%20Analytics-Business%20Intelligence-4B0082?style=for-the-badge"/>

<br><br>

<p>
<b>Turning Customer Data Into Actionable Retention Insights</b>
</p>

<p>
An interactive Power BI analytics project designed to understand customer churn,
identify high-risk customer segments, analyze behavioral patterns,
and transform customer data into meaningful business insights.
</p>

</div>

---

# 📌 Table of Contents

- [📊 Project Overview](#-project-overview)
- [🎯 Problem Statement](#-problem-statement)
- [💡 Project Objectives](#-project-objectives)
- [📂 Dataset Overview](#-dataset-overview)
- [🧾 Dataset Attributes](#-dataset-attributes)
- [🔄 Analytical Workflow](#-analytical-workflow)
- [🧹 Data Preparation](#-data-preparation)
- [🧠 Data Modeling](#-data-modeling)
- [🧮 DAX & KPI Development](#-dax--kpi-development)
- [📊 Dashboard Architecture](#-dashboard-architecture)
- [🔥 Customer Churn Dashboard](#-customer-churn-dashboard)
- [⚠️ Customer Risk Analysis Dashboard](#-customer-risk-analysis-dashboard)
- [🔍 Key Findings](#-key-findings)
- [💼 Business Interpretation](#-business-interpretation)
- [🎯 Customer Segmentation](#-customer-segmentation)
- [📈 Analytical Dimensions](#-analytical-dimensions)
- [🛠️ Technology Stack](#️-technology-stack)
- [📁 Repository Structure](#-repository-structure)
- [▶️ How to Run the Project](#️-how-to-run-the-project)
- [📚 Skills Demonstrated](#-skills-demonstrated)
- [🚀 Possible Future Improvements](#-possible-future-improvements)
- [🎯 Project Takeaway](#-project-takeaway)
- [👨‍💻 Author](#-author)

---

# 📊 Project Overview

Customer retention is an important business problem for subscription-based and service-oriented organizations.

When customers discontinue their services, businesses can experience:

- Loss of recurring revenue
- Increased customer acquisition costs
- Reduced customer lifetime value
- Higher pressure on marketing teams
- Increased requirement for customer acquisition
- Difficulty maintaining a stable customer base

However, simply knowing the number of customers who churned is not enough.

A business needs to understand:

```text
WHO is leaving?
        ↓
WHEN are they leaving?
        ↓
WHAT characteristics do they share?
        ↓
WHICH services are associated with churn?
        ↓
WHICH customer segments require investigation?
        ↓
HOW can the insights support retention decisions?

```

This project uses Microsoft Power BI, Power Query, DAX and Excel to analyze customer-level data and convert it into an interactive business intelligence solution.

The project contains two major dashboards:

* **🔥 Customer Churn Dashboard:** A detailed analytical view of customers who have churned, focusing on their demographics, subscription characteristics, services, payment methods, tenure and financial information.
* **⚠️ Customer Risk Analysis Dashboard:** A broader view of the customer population designed to identify patterns and segments associated with higher levels of customer churn.

---

# 🎯 Problem Statement

How can customer-level data be analyzed to identify churn patterns, understand high-risk customer segments, and provide actionable insights that support customer retention decisions?

The problem is not limited to calculating a churn percentage. A useful churn-analysis system should allow a business analyst to investigate multiple dimensions simultaneously.

```text
Customer
   │
   ├── Demographics
   │
   ├── Contract
   │
   ├── Internet Service
   │
   ├── Payment Method
   │
   ├── Tenure
   │
   ├── Monthly Charges
   │
   ├── Total Charges
   │
   ├── Technical Support
   │
   └── Additional Services

```

The project therefore focuses on creating an analytical environment where these dimensions can be explored interactively.

---

# 💡 Project Objectives

#### 01 — Measure Customer Churn

Calculate the number and proportion of customers who have discontinued their services.

#### 02 — Understand Customer Characteristics

Analyze churn across demographic and customer-profile dimensions such as Gender, Senior Citizen status, Partner status, Dependents, and Tenure.

#### 03 — Analyze Subscription Behavior

Investigate how churn varies according to Contract type, Internet service, Phone service, Multiple lines, Streaming services, Online security, Online backup, Device protection, and Technical support.

#### 04 — Analyze Payment Behavior

Study the relationship between churn and payment-related characteristics such as Electronic Check, Mailed Check, Bank Transfer, Credit Card, and Paperless Billing.

#### 05 — Analyze Financial Impact

Examine Monthly Charges, Total Charges, Yearly Charges, Revenue associated with customers, and Financial characteristics of churned customers.

#### 06 — Analyze Customer Risk

Identify customer groups where churn is comparatively concentrated to provide analytical evidence that helps teams determine where further investigation is useful.

#### 07 — Build Interactive Dashboards

Create Power BI dashboards that allow users to filter customer segments, compare churn patterns, examine KPIs, investigate customer characteristics, explore relationships between services and churn, and understand customer risk patterns.

---

# 📂 Dataset Overview

The project uses a customer-level dataset stored in **`02 Customer Churn-Dataset.xlsx`**.

| Metric | Value |
| --- | --- |
| 👥 **Total Customers** | 7,043 |
| 🚪 **Churned Customers** | 1,869 |
| 📊 **Overall Churn Rate** | 26.54% |

```text
Customer Demographics
        +
Account Information
        +
Service Information
        +
Payment Information
        +
Financial Information
        +
Support Activity
        +
Churn Status

```

---

# 🧾 Dataset Attributes

### 👤 Customer Information

* **Customer ID:** Unique identifier assigned to each customer.
* **Gender:** Customer gender.
* **Senior Citizen:** Indicates whether the customer belongs to the senior-citizen category.
* **Partner:** Indicates whether the customer has a partner.
* **Dependents:** Indicates whether the customer has dependents.

### ⏳ Customer Tenure

* **Tenure:** Represents the number of months the customer has remained with the service. Helps investigate whether churn behavior changes throughout the customer lifecycle.

### 📱 Telephone & Internet Services

* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies

### 📄 Contract Information

* **Contract:** Categorized by contract duration (e.g., Month-to-month, One year, Two year).

### 💳 Payment Information

* **Payment Method:** Electronic Check, Mailed Check, Bank Transfer, Credit Card.
* **Paperless Billing:** Indicates billing preference.

### 💰 Financial Information

* **Monthly Charges:** Recurring monthly amount associated with the customer's services.
* **Total Charges:** Total amount charged to the customer over the observed relationship.

### 🎫 Support Activity

* Administrative Tickets
* Technical Tickets

### 🚪 Churn

* Indicates whether the customer discontinued the service (Primary target dimension).

---

# 🔄 Analytical Workflow

```text
                    RAW DATA
                       │
                       ▼
              Excel Customer Dataset
                       │
                       ▼
              Data Quality Inspection
                       │
                       ▼
                Power Query
                       │
                       ▼
             Data Transformation
                       │
                       ▼
                Data Modeling
                       │
                       ▼
                 DAX Measures
                       │
                       ▼
             KPI Development
                       │
                       ▼
              Exploratory Analysis
                       │
             ┌─────────┴─────────┐
             ▼                   ▼
     Customer Churn        Customer Risk
       Dashboard             Dashboard
             │                   │
             └─────────┬─────────┘
                       ▼
              Business Insights
                       │
                       ▼
             Retention Analysis

```

---

# 🧹 Data Preparation

Power Query is used as the primary data-transformation layer:

* **🔹 Data Type Validation:** Ensuring numerical, categorical, and date-related fields are represented correctly.
* **🔹 Data Cleaning:** Handling missing values, invalid values, inconsistent categories, duplicate records, and formatting inconsistencies.
* **🔹 Column Preparation:** Organizing relevant fields for effective use within Power BI visuals and calculations.
* **🔹 Analytical Readiness:** Structuring the final dataset to support filtering, aggregation, segmentation, KPI calculations, visualization, and customer-level analysis.

---

# 🧠 Data Modeling

```text
                    CUSTOMER DATA
                         │
       ┌─────────────────┼─────────────────┐
       │                 │                 │
       ▼                 ▼                 ▼
  Demographics       Services          Account
       │                 │                 │
       ▼                 ▼                 ▼
 Gender              Internet         Contract
 Senior Citizen      Phone            Tenure
 Partner             Security         Billing
 Dependents          Support          Payment
       │                 │                 │
       └─────────────────┼─────────────────┘
                         ▼
                       CHURN
                         │
                         ▼
                  BUSINESS INSIGHTS

```

---

# 🧮 DAX & KPI Development

### Key DAX Metrics

* **👥 Total Customers:** Measures the total number of customers in the dataset.
* **🚪 Churned Customers:** Measures the number of customers who have left.
* **📊 Churn Rate:**

$$\text{Churn Rate} = \frac{\text{Churned Customers}}{\text{Total Customers}} \times 100$$


$$\frac{1,869}{7,043} \times 100 \approx 26.54\%$$



### 💰 Financial Metrics

* Monthly Charges
* Total Charges
* Yearly Charges
* Average Charges

---

# 📊 Dashboard Architecture

```text
┌───────────────────────────────────────┐
│       CUSTOMER CHURN DASHBOARD        │
├───────────────────────────────────────┤
│ Churned Customers                     │
│ Demographics                          │
│ Contract                              │
│ Internet Service                      │
│ Payment Method                        │
│ Tenure                                │
│ Charges                               │
│ Support Tickets                       │
└───────────────────────────────────────┘

                    +

┌───────────────────────────────────────┐
│    CUSTOMER RISK ANALYSIS DASHBOARD   │
├───────────────────────────────────────┤
│ Total Customers                       │
│ Churn Rate                            │
│ Risk Segments                         │
│ Contract Analysis                     │
│ Internet Analysis                     │
│ Payment Analysis                      │
│ Tenure Analysis                       │
│ Financial Analysis                    │
└───────────────────────────────────────┘

```

---

# 🔥 Customer Churn Dashboard

Focuses specifically on customers who have churned, providing detailed views on demographics, contract characteristics, internet services, payment methods, tenure, charges, and support tickets.

---

# ⚠️ Customer Risk Analysis Dashboard

Provides a broader view of customer churn patterns across the wider customer population to investigate characteristics associated with risk.

---

# 🔍 Key Findings

* **📌 Baseline Churn:** Overall churn rate stands at **26.54%** (1,869 out of 7,043 total customers).
* **📌 Contract Type:** Month-to-month contracts represent the highest churn segment compared to longer-term commitments.
* **📌 Internet Service:** Fiber Optic customers exhibit a **41.89%** churn rate vs **18.96%** for DSL and **7.40%** for No Internet Service.
* **📌 Payment Method:** Electronic Check users represent a significantly higher churn concentration.
* **📌 Customer Tenure:** Churn is heavily concentrated in early tenure stages.
* **📌 Support & Financial Context:** Higher rates of administrative/technical tickets and specific monthly charge brackets correlate with elevated churn risk.

---

# 💼 Business Interpretation

1. **1️⃣ Early Customer Engagement:** Focus onboarding interventions on high-vulnerability early-tenure months.
2. **2️⃣ Month-to-Month Customer Analysis:** Create retention incentives to migrate short-term contract holders to annual plans.
3. **3️⃣ Fiber-Optic Customer Investigation:** Audit service quality, competition, pricing, and support experience for Fiber Optic users.
4. **4️⃣ Payment Behavior Analysis:** Identify and reduce payment friction associated with electronic check processes.
5. **5️⃣ Support Experience:** Address issues driving high technical and administrative support ticket frequency.

---

# 🎯 Customer Segmentation

```text
                    CUSTOMER BASE
                         │
          ┌──────────────┼──────────────┐
          │              │              │
          ▼              ▼              ▼
      CONTRACT       INTERNET       PAYMENT
          │              │              │
          ▼              ▼              ▼
    Month-to-month     DSL        Electronic Check
    One Year           Fiber      Mailed Check
    Two Year           None       Bank Transfer
                                  Credit Card
          │              │              │
          └──────────────┼──────────────┘
                         ▼
                      TENURE
                         │
                         ▼
                     CHURN

```

---

# 📈 Analytical Dimensions

| Dimension | Analytical Purpose |
| --- | --- |
| 👤 **Gender** | Demographic comparison |
| 👴 **Senior Citizen** | Customer demographic segmentation |
| ❤️ **Partner** | Household/customer profile |
| 👨‍👩‍👧 **Dependents** | Customer profile analysis |
| ⏳ **Tenure** | Customer lifecycle analysis |
| 📱 **Phone Service** | Service analysis |
| 📡 **Multiple Lines** | Service segmentation |
| 🌐 **Internet Service** | Service/churn comparison |
| 🔐 **Online Security** | Service adoption |
| ☁️ **Online Backup** | Service adoption |
| 🛡️ **Device Protection** | Service adoption |
| 🧑‍💻 **Tech Support** | Customer support analysis |
| 📺 **Streaming TV** | Service analysis |
| 🎬 **Streaming Movies** | Service analysis |
| 📄 **Contract** | Subscription behavior |
| 🧾 **Paperless Billing** | Billing behavior |
| 💳 **Payment Method** | Payment segmentation |
| 💰 **Monthly Charges** | Financial analysis |
| 💵 **Total Charges** | Revenue/customer-value analysis |
| 🎫 **Support Tickets** | Customer experience context |
| 🚪 **Churn** | Primary analytical outcome |

---

# 🛠️ Technology Stack

| Technology | Role |
| --- | --- |
| 🟨 **Microsoft Power BI** | Dashboard and visualization development |
| 🟩 **Microsoft Excel** | Source dataset |
| 🟪 **Power Query** | Data cleaning and transformation |
| 🔵 **DAX** | Measures and analytical calculations |
| 📊 **Power BI Visuals** | Interactive data storytelling |

---

# 📁 Repository Structure

```text
Customer-Churn-Analysis/
│
├── 📄 02 Customer Churn-Dataset.xlsx
├── 📊 Customer Churn Dashboard.pbix
├── 📊 Customer Risk Analysis Dashboard.pbix
├── 🖼️ Customer Churn Dashboard.png
├── 🖼️ Customer Risk Analysis.png
└── 📘 README.md

```

### 📄 File Descriptions

* **`02 Customer Churn-Dataset.xlsx`**: Excel file containing customer-level source data.
* **`Customer Churn Dashboard.pbix`**: Power BI Desktop file containing the customer churn analysis dashboard.
* **`Customer Risk Analysis Dashboard.pbix`**: Power BI Desktop file containing the broader customer-risk analysis dashboard.
* **`Customer Churn Dashboard.png`**: Static preview image of the Customer Churn Dashboard.
* **`Customer Risk Analysis.png`**: Static preview image of the Customer Risk Analysis Dashboard.

---

# ▶️ How to Run the Project

1. **Clone the Repository:**
```bash
git clone [https://github.com/keshavkapill/Customer-Churn-Analysis.git](https://github.com/keshavkapill/Customer-Churn-Analysis.git)

```


2. **Navigate to the Directory:**
```bash
cd Customer-Churn-Analysis

```


3. **Open Power BI:** Launch Microsoft Power BI Desktop.
4. **Open Dashboard Files:** Open `Customer Churn Dashboard.pbix` or `Customer Risk Analysis Dashboard.pbix`.
5. **Relink Data Source:** If prompted, point the data source path to `02 Customer Churn-Dataset.xlsx`.

---

# 📚 Skills Demonstrated

* **💻 Technical Skills:** Power BI, Dashboard Development, Power Query, Data Modeling, DAX Calculations, Excel Data Structuring.
* **🧠 Analytical Skills:** Exploratory Data Analysis, Customer Churn & Segmentation Analysis, Business Intelligence, Data Storytelling, KPI Development.

---

# 🚀 Possible Future Improvements

* 🔮 **01 — Machine Learning Churn Prediction:** Implement predictive modeling (Logistic Regression, Random Forest, XGBoost) to estimate individual customer churn probability.
* 🔮 **02 — Customer Churn Prediction Score:** Assign automated risk levels to existing active customers.
* 🔮 **03 — Automated Refresh Pipelines:** Connect dashboards to live cloud data connectors.
* 🔮 **04 — Advanced Customer Lifetime Value (CLV) Analysis:** Integrate churn risk with customer valuation models to prioritize retention efforts.
* 🔮 **05 — Cohort Analysis:** Track retention behavior across specific customer acquisition cohorts over time.

---

# 🎯 Project Takeaway

```text
DATA ──> CLEANING ──> TRANSFORMATION ──> MODELING ──> DAX ──> KPI DEVELOPMENT ──> VISUALIZATION ──> SEGMENTATION ──> INSIGHTS ──> BUSINESS INTERPRETATION

```

---

# ⭐ Project Highlights

| 📊 Analysis | 📈 Insight |
| --- | --- |
| **Customer Churn** | Overall churn measurement |
| **Contract Analysis** | Subscription behavior |
| **Internet Service** | Service-level churn patterns |
| **Payment Analysis** | Payment-method segmentation |
| **Tenure Analysis** | Customer lifecycle |
| **Financial Analysis** | Charges and customer value |
| **Support Analysis** | Customer experience context |
| **Risk Analysis** | Identification of high-churn segments |

---

# 👨‍💻 Author

### Keshav Kapil

*BTech Computer Science Engineering Student*

Interested in Data Analytics, Cloud Computing, Full-Stack Development & Software Engineering.
