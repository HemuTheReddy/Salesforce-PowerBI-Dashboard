<a id="readme-top"></a>

# Salesforce Financial Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

A Power BI dashboard project that analyzes Salesforce's financial performance, focusing on revenue pipeline, profitability, and expense efficiency using SEC filing data scraped from the EDGAR database using the edgartools Python library.
---

## Table of Contents
- [Project Overview](#project-overview)
- [Tech-Stack](#tech-stack)
- [ER Diagram](#er-diagram)
- [Dashboard](#dashboard)
- [Insights](#insights)
- [Usage](#usage)
- [Challenges](#challenges)
- [Conclusion](#conclusion)

---

## Project Overview

This project provides a comprehensive blueprint of Salesforce's financial performance, translating raw SEC filings from the EDGAR database into an actionable, analytical dashboard. The data was programmatically acquired using the `edgartools` Python library. All SEC filing forms (10-K and 10-Q) were given as a string from the library, so text extraction using Regex was the method I used to gather and consolidate all of the data I needed to build this dashboard.

The dashboard follows a deliberate narrative path, structured across three key pages. It begins with a high-level **Executive Summary** for a consolidated business overview. From there, it guides the user through the **SaaS Revenue Engine**, connecting the "North Star" metric of future pipeline (RPO) to the "Execution Engine" of current billings. Finally, the story lands on **Profitability and Expense**, deconstructing how top-line revenue is converted into tangible operating profit, net income, and cash flow.

The dashboard features interactive features, allowing the user to filter each chart by a specific quarter, or by a specific year in the yearly view for a higher level overview of company's metrics.

[<p align="right">(Back to Top)</p>](#readme-top)

---

## Dashboard

The dashboard is organized into three main pages, flowing from a high-level executive summary to a deep dive into revenue and, finally, profitability.

### Executive Summary

This page provides a top-level, consolidated view of the most critical KPIs across the entire business, allowing executives to understand the company's overall health at a single glance. It summarizes performance from pipeline growth to expense management.

![Executive Summary Page](assets/ExecSum.png)

### SaaS Revenue Engine

This page analyzes the "top of the funnel," focusing on the future revenue pipeline (RPO), its conversion into new billings (the 'Execution Engine'), and the quality of the resulting subscription revenue.

![SaaS Revenue Engine Page](assets/SaasRev.png)

### Profitability and Expense

This page drills down into the "bottom line," analyzing operational efficiency, expense management (S&M, R&D, G&A as a % of revenue), and overall profitability (Operating Income, Net Income, and Cash Flow).

![Profitability and Expense Page](assets/ProfExp.png)

[<p align="right">(Back to Top)</p>](#readme-top)

---

## Tech-Stack

| Category | Tools |
| :--- | :--- |
| **Data Collection** | `edgartools` (Python) |
| **Data Processing** | `Pandas`, `Microsoft Excel` |
| **Data Modeling & Analysis** | `DAX` |
| **Data Visualization** | `PowerBI` |
| **UI Design** | `Powerpoint` |

[<p align="right">(Back to Top)</p>](#readme-top)

---

## ER Diagram

*(Insert the image of your data model / ER diagram here. Briefly explain the relationships between your fact tables (Qdata, FYdata) and dimension tables (DimDate).)*

[<p align="right">(Back to Top)</p>](#readme-top)

---

## Insights

*(List the key insights you discovered from the dashboard. What are the main takeaways from the story you're telling?)*

* **Insight 1:** ...
* **Insight 2:** ...
* **Insight 3:** ...

[<p align="right">(Back to Top)</p>](#readme-top)

---

## Usage

*(Explain how a user should interact with this dashboard. Is there a recommended "flow"? How should they use the slicers?)*

[<p align="right">(Back to Top)</p>](#readme-top)

---


## Challenges

*(What were the main difficulties you faced during this project? This could be DAX-related (like time-intelligence), data modeling (ambiguous paths), or data cleaning.)*

[<p align="right">(Back to Top)</p>](#readme-top)

---

## Conclusion

*(Summarize the project. What was the final result? What are potential future improvements?)*

[<p align="right">(Back to Top)</p>](#readme-top)
