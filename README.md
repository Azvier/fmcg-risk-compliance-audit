# FMCG Risk Compliance Audit

This project provides a framework for performing a risk and compliance audit for a fictional FMCG company, Azelia. The core of the project is centered around analyzing a dataset to uncover potential risks, ensure compliance with internal and external regulations, and validate business rules.

The primary analysis and audit activities are conducted within **Microsoft Excel**, leveraging its powerful data analysis and automation capabilities.

## 🚧 Project Status

**This project and its documentation are currently a work in progress.**

The audit is currently underway in Microsoft Excel. After completing the Excel-based audit, a Power BI dashboard will be developed to visualize key findings. The final phase will focus on completing and refining the overall project structure. Throughout each stage, the process will be thoroughly documented to ensure clarity and transparency.

## 🎯 Audit Objectives & Scope

The main goal is to perform a comprehensive audit to achieve the following:

*   **Validate Halal Compliance:** Verify that products marketed as Halal have valid, unexpired certifications.
*   **Ensure Promotional Integrity:** Check for inconsistencies in promotional mechanics, ensuring that promotions are applied correctly and do not overlap in ways that create financial risk.
*   **Verify Product Master Data:** Ensure the integrity and accuracy of the product master list.
*   **Analyze Sales Transactions:** Audit sales data for anomalies and compliance with promotional rules.

## 🛠️ Tools & Methodology

The audit process is designed to be performed primarily using Microsoft Excel and its associated toolset:

*   **Power Query:** Used for importing, cleaning, and transforming the raw data from CSV files into a structured data model within Excel.
*   **Excel Formulas:** Core data validation and lookups using functions like `XLOOKUP`, `SUMIFS`, etc.
*   **DAX & VBA:** Potentially used for more complex calculations within the data model (DAX) or for automating tasks (VBA).

## 📂 Project Structure

```
fmcg-risk-compliance-audit/
├── .gitignore
├── LICENSE
├── pdm.lock
├── pyproject.toml
├── README.md
├── misc/
├── datasets/
│   └── raw/
└── scripts/
    └── data-generation.py
```

*   **`datasets/`**: Contains the raw data files (CSV) to be used as the basis for the audit.
*   **`misc/`**: Contains project-related documents and instructions.
*   **`scripts/`**: Contains an optional Python script (`data-generation.py`) intended for developers who want to regenerate the source data.

> **Note:** The datasets and data generation scripts will be made available after the Excel audit implementation and documentation are finalized.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.