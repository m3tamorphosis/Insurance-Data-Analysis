# Prism Insurance Analytics Dashboard 📊

<img width="1025" height="577" alt="image" src="https://github.com/user-attachments/assets/9afb9f1e-72d8-46bc-862d-1e8e63682d55" />


## 📌 Overview
This project presents an interactive **Insurance Analytics Dashboard** developed using **SQL Server and Power BI**.  
It analyzes insurance data to track premiums, coverage, claims, and policy activity, helping stakeholders make data-driven decisions.

The project demonstrates the complete data analytics workflow:
- Data storage and querying using SQL
- Data modeling and transformation
- DAX measures and KPIs
- Interactive dashboard design in Power BI

---

## 🛠 Tools & Technologies
- **SQL Server** – Data storage, querying, and preparation  
- **Power BI** – Data modeling, DAX, and visualization  
- **DAX** – Measures and calculated metrics  
- **Power Query** – Data transformation  

---

## 📂 Dataset Description
The dataset includes insurance-related information such as:
- Customer details (Customer ID, Gender, Age, Age Group)
- Policy information (Policy Number, Policy Type, Policy Status)
- Financial metrics (Premium Amount, Coverage Amount, Claim Amount)
- Claim status (Pending, Rejected, Settled)

---

## 📊 Dashboard Features

### 🔹 Key Performance Indicators (KPIs)
- **Total Premium Amount**
- **Total Coverage Amount**
- **Total Claim Amount**

### 🔹 Visual Insights
- Premium Amount by Policy Type  
- Claim Amount by Age Group  
- Number of Claims by Status (Rejected, Settled, Pending)  
- Active vs Inactive Policies  
- Gender-based customer distribution  

### 🔹 Interactivity
- Filters by:
  - Policy Number
  - Customer ID
  - Claim Number
- Dynamic visuals that update based on selections

---

## 🧠 Business Insights
- Travel and Health policies contribute the highest premium revenue  
- Adult customers generate the highest claim amounts  
- Majority of policies are active  
- Rejected claims are higher compared to pending claims

- Data Transformation (Power Query)
🧑‍🤝‍🧑 Age Group (Conditional Column)

The Age Group column was created using a Conditional Column in Power Query to categorize customers based on age.
This enables demographic-based analysis and improves dashboard clarity.

Logic applied:

Young Adult → Age < 25

Adult → Age between 25 and 59

Elder → Age ≥ 60

🔁 Policy Status (Active / Inactive)

The Policy Status column was derived using a Conditional Column in Power Query to classify policies as Active or Inactive.

Logic applied:

Active → Policy is currently valid

Inactive → Policy is expired or closed

📌 Why Conditional Columns Were Used

Improves data quality during preparation

Reduces DAX complexity

Enhances report performance

Ensures consistent categorization

🚀 Conclusion
This project showcases an end-to-end analytics solution using Excel, SQL Server, and Power BI, including data transformation, DAX calculations, and interactive dashboard development.
It demonstrates practical skills suitable for Data Analyst and Business Intelligence Analyst roles.



