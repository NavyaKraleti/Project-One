| Project Name | Description                                          | Tools Used                        |
|--------------|------------------------------------------------------|-----------------------------------|
| Project 1    | Performed ETL testing on a data warehouse.           | SQL, Azure Databricks, Azure DevOps, ETL Testing |

# Healthcare Data Analytics Platform 🌟

Worked on a **data analytics platform** for the healthcare domain, designed to improve healthcare outcomes through efficient data management and analytics.

---

## Overview  
### Objective  
- Develop a modern data analytics platform for the healthcare industry, processing data from ERP systems into meaningful insights for business users.

### Data Pipeline Workflow  
1. **Source**: Extract data from ERP systems.  
2. **Storage**: Load data into **Azure Data Lake** for further processing.  
3. **Processing**: Transform data through multiple layers (Raw → Silver → Gold → Serve).  
4. **Output**: Deliver actionable business insights through analytics.

---

## My Role: QA Tester  

### Responsibilities:  
- **Test Scenario Identification**: Analyzed business requirements to define test scenarios.  
- **Test Case Preparation**: Developed test cases to validate data from the Raw layer through to the Serve layer.  
- **Test Execution**: Executed test scripts in **Azure Databricks** using **PySpark** & **SQL** to ensure data integrity.  
- **Data Validation**:  
  - Verified access to Azure Data Lake storage accounts.  
  - Conducted volume checks, record count validation, and data quality checks (e.g., nulls, duplicates, aggregates).  
  - Validated edge cases and negative scenarios to ensure system robustness.

### Tools & Technologies:  
- **Azure DevOps**: Managed test case preparation, defect tracking, and execution.  
- **Azure Databricks**: Developed and executed test scripts for data validation.  
- **Azure Synapse**: Used for pipeline execution and data transformation processes.  
- **PySpark**: Employed for processing and validating data files (CSV, XLS, TXT, Parquet) using DataFrames.

---

## Key Achievements & Challenges  

### Achievements:  
- Developed and executed comprehensive **end-to-end test strategies**.  
- Leveraged **PySpark** for efficient data processing and validation, converting data from raw files into SQL tables for easier validation.

### Challenges & Solutions:  
- **Challenge**: The lack of automation capabilities required manual testing, making the process more complex.  
  - **Solution**: Integrated **PySpark** into the testing framework to automate the reading and writing of source files directly within Databricks, improving efficiency.

---

## Defect Management Process  
1. **Bug Logging**: Defects are logged in **Azure DevOps (ADO Board)**.  
2. **Assignment**: Bugs are assigned to developers for resolution.  
3. **Retesting**: Once defects are resolved, they are reassigned for retesting. If validated, the defect is closed.

---

## Test Strategies  
- Verify access to **Azure Data Lake storage accounts** and ensure data availability.  
- Perform **volume and data quality checks** (nulls, duplicates, aggregates).  
- Prepare and execute **negative test scenarios** to ensure the system can handle edge cases.  
- Conduct **end-to-end testing** from the Raw layer through to the Serve layer to validate the entire data flow.

---

This project highlights my ability to work with **cloud data platforms** and **data pipelines**, ensuring the integrity of data and supporting **business analytics** in the healthcare domain. 🚀
