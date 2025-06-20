# Telecom Customer Churn Analysis

## Project Overview

This project focuses on analyzing customer churn within a telecommunications company to identify the key factors contributing to customers discontinuing their services. The goal is to provide actionable, data-driven recommendations to help the company enhance customer retention and reduce churn rates.

## Key Features & Components

* **Data Acquisition:** Sourcing a publicly available Telco Customer Churn dataset.
* **Professional Data Cleaning & Transformation:** Utilizing Microsoft Excel's Power Query for robust and auditable data preparation.
* **Exploratory Data Analysis (EDA):** In-depth analysis using Excel PivotTables to calculate and compare churn rates across various customer segments and service attributes.
* **Data Visualization:** Creation of insightful PivotCharts to visually represent churn patterns and trends.
* **Key Findings & Recommendations:** Deriving actionable insights from the analysis to propose strategies for churn reduction.
* **Comprehensive Project Report:** A detailed PDF report summarizing the methodology, findings, and recommendations.

## Dataset

The analysis is based on the "Telco Customer Churn" dataset, sourced from Kaggle.
* **Source:** [https://www.kaggle.com/datasets/blastchar/telco-customer-churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
* **Description:** Contains information on 7,043 telecom customers, including demographic data, services subscribed, billing information, and their churn status (whether they left the company or not).

## Tools Used

* **Microsoft Excel:** For data analysis (PivotTables, PivotCharts) and report generation.
* **Power Query (within Excel):** For advanced data cleaning, transformation, and maintaining an auditable data pipeline.

## Methodology

The project followed a structured approach:

1.  **Data Collection:** Downloaded the `WA_Fn-UseC_-Telco-Customer-Churn.csv` dataset.
2.  **Data Cleaning & Preprocessing (using Power Query):**
    * Imported data into Power Query.
    * Renamed query for clarity.
    * Transformed `TotalCharges` column to a numeric type, handling errors/blanks by replacing them with zeros.
    * Created a `Churn_Binary` column (1 for churn, 0 for no churn).
    * Removed irrelevant columns (`customerID`).
    * Trimmed and cleaned text fields to remove whitespace and non-printable characters.
    * Removed duplicate rows to ensure data uniqueness.
    * Loaded the cleaned data into a new Excel worksheet.
3.  **Exploratory Data Analysis (EDA):**
    * Calculated the overall churn rate.
    * Analyzed churn rates by various categorical features (e.g., Contract Type, Internet Service, Payment Method, Online Security, Tech Support, Paperless Billing, Senior Citizen, Partner, Dependents, Gender) using PivotTables and PivotCharts.
    * Analyzed churn rates by numerical features (`Tenure`, `MonthlyCharges`) by grouping them into bins and visualizing with PivotTables and PivotCharts.
4.  **Insight Generation & Recommendations:** Interpreted the visual findings to identify key churn drivers and formulated actionable strategies for customer retention.
5.  **Report Generation:** Documented the entire process, findings, and recommendations in a comprehensive project report.

## Key Findings & Insights

(Please refer to the full `Telecom_Churn_Analysis_Report.pdf` for detailed findings and visualizations.)

* **Contract Type:** [Summarize your main finding here, e.g., Month-to-month contracts exhibit significantly higher churn rates.]
* **Internet Service:** [Summarize your main finding here, e.g., Fiber optic customers have a higher propensity to churn.]
* **Customer Tenure:** [Summarize your main finding here, e.g., Churn is highest in the initial months and decreases with longer tenure.]
* **Add-on Services:** [Summarize your main finding here, e.g., Customers without Online Security or Tech Support services are more likely to churn.]
* **Payment Method:** [Summarize your main finding here, e.g., Electronic Check payment method is associated with higher churn.]
* ... (Add 2-3 more key summarized findings from your analysis) ...

## Recommendations

(Please refer to the full `Telecom_Churn_Analysis_Report.pdf` for detailed recommendations.)

* **Targeted Retention Programs:** [Briefly state a recommendation, e.g., Implement retention campaigns for month-to-month customers.]
* **Service Enhancement:** [Briefly state a recommendation, e.g., Improve reliability and support for Fiber Optic internet service.]
* **Onboarding & Early Engagement:** [Briefly state a recommendation, e.g., Develop robust onboarding for new customers to reduce early churn.]
* ... (Add 2-3 more brief, actionable recommendations) ...

## Files in This Repository

* `WA_Fn-UseC_-Telco-Customer-Churn.csv`: The original raw dataset.
* `Telecom_Churn_Analysis.xlsx`: The Excel workbook containing the cleaned data, PivotTables, and PivotCharts.
* `Telecom_Churn_Analysis_Report.pdf`: The comprehensive project report detailing the analysis, findings, and recommendations.
* `README.md`: This project overview file.

## Author

**  DHARSHINI

---