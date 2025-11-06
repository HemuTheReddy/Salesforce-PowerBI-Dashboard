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
- [Full Report](#full-report)
- [Challenges](#challenges)
- [Conclusion](#conclusion)

---

## Project Overview

*(Provide a high-level summary of the project. What was the goal? What problem does it solve? What data sources were used?)*

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

## Full Report

*(If you have a separate, more detailed PDF or written report, you can link to it or embed it here. Otherwise, you can use this section to expand on your insights in more detail.)*

[<p align="right">(Back to Top)</p>](#readme-top)

---

## Challenges

*(What were the main difficulties you faced during this project? This could be DAX-related (like time-intelligence), data modeling (ambiguous paths), or data cleaning.)*

[<p align="right">(Back to Top)</p>](#readme-top)

---

## Conclusion

*(Summarize the project. What was the final result? What are potential future improvements?)*

[<p align="right">(Back to Top)</p>](#readme-top)
