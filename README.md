# Bank Customer Retention & Churn Analytics Dashboard

## 📊 Live Interactive Dashboard
Explore and interact with the live project on the cloud:
👉 **[View My Live Tableau Public Dashboard](https://tableau.com)**

---

## 🔍 Project Overview & Objective
This Business Intelligence solution was engineered to diagnose, track, and analyze bank customer churn rates across core market segments. The dataset spans over **10,000 corporate records** capturing critical banking benchmarks. The objective is to identify demographic vulnerabilities and financial behaviors correlated with customer attrition, helping risk management teams implement targeted retention frameworks.

## 🛠️ Data Architecture & Technical Scope
- **File Structure:** Built on a production-ready Tableau Packaged Architecture (`.twbx`) housing a `.hyper` data extraction database.
- **Data Modeling:** Established a star-schema relationship by executing inner data joins between a transactional central Fact layer (`Account_Fact.csv`) and contextual Dimension layers (`Customer_Dim.csv`) using unique user identifiers (`customer_id`).
- **Core Parameters Analyzed:** Credit Evaluation Evaluation (`credit_score`), Transactional Capital (`balance`), Account Status (`active_member`), Regional Attributes (`country`), Tenure, Demographics (`gender`, `age`), and Estimated Earnings.

## 📈 Key Dashboard Features & Insights
- **Fluid Cross-Filtering Actions:** Implemented map actions where interacting with global geographic clusters dynamically updates adjacent metric tracking widgets, bar charts, and asset distributions.
- **Risk Discovery UI:** Segmented customer drop-off trends, revealing that the highest localized retention risks are concentrated within specific geographic locations and demographic criteria.

---

## 📁 Repository Structure
- `practice.1123_QoAanU.twbx`: The raw Tableau Packaged Workbook containing full visual layers and offline hyper-extract database.
- `README.md`: Project documentation and architecture details.

## 👨‍💻 Connect with Me
- **LinkedIn:** [Your LinkedIn Profile Link]
- **Tableau Public:** [Your Tableau Public Profile Link]
