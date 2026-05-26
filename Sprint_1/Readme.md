# DMart Retail Sales Analytics Project

## Project Overview

The DMart Retail Sales Analytics Project is initiated by the Business Intelligence & Analytics Department to improve the accuracy, consistency, and reliability of retail sales reporting across multiple stores and regions.

The organization identified several inconsistencies in the existing sales reports generated from raw billing system exports. Due to poor data quality, management is facing challenges in monitoring business performance and making data-driven decisions.

The primary objective of this project is to clean, transform, and prepare retail sales data for advanced analytics and dashboard development using Business Intelligence tools such as Power BI.

---

## Business Problem Statement

Senior management at DMart observed inconsistencies in retail sales reports generated from different regional stores. The current raw sales data contains multiple quality issues that directly affect reporting accuracy and business insights.

```
Key Challenges
1. Missing values in important columns
2. Duplicate transaction records
3. Incorrect and inconsistent date formats
4. Null profit values
5. Invalid discount percentages
6. Inconsistent category and sub-category naming
7. Data entry errors from billing systems
8. Unstructured raw datasets
```

Because of these issues, the analytics team cannot directly use the dataset for reporting, KPI tracking, or dashboard creation.

---

## Project Objectives

The project aims to build a structured and reliable analytics workflow that helps management monitor and improve business performance.

```
Primary Objectives
1. Analyze overall sales performance
2. Measure profitability across regions and products
3. Identify customer purchasing trends
4. Track product demand and sales patterns
5. Evaluate regional business performance
6. Improve data quality and reporting accuracy
7. Prepare datasets for dashboard development
```
---

## Common Excel Functions Used for Data Cleaning

```
| Function                     | Purpose                          | Example                                      |
| ---------------------------- | -------------------------------- | -------------------------------------------- |
| `TRIM()`                     | Removes extra spaces             | `=TRIM(A2)`                                  |
| `UPPER()`                    | Converts text to uppercase       | `=UPPER(B2)`                                 |
| `LOWER()`                    | Converts text to lowercase       | `=LOWER(B2)`                                 |
| `PROPER()`                   | Capitalizes first letter         | `=PROPER(C2)`                                |
| `LEN()`                      | Checks text length               | `=LEN(D2)`                                   |
| `IF()`                       | Logical condition checking       | `=IF(E2<0,"Invalid","Valid")`                |
| `ISBLANK()`                  | Detects blank cells              | `=ISBLANK(F2)`                               |
| `COUNTIF()`                  | Detects duplicates               | `=COUNTIF(A:A,A2)`                           |
| `IFERROR()`                  | Handles formula errors           | `=IFERROR(A2/B2,0)`                          |
| `TEXT()`                     | Standardizes date format         | `=TEXT(G2,"DD-MM-YYYY")`                     |
| `VALUE()`                    | Converts text to number          | `=VALUE(H2)`                                 |
| `SUBSTITUTE()`               | Replaces inconsistent text       | `=SUBSTITUTE(A2,"Electrnics","Electronics")` |
| `CLEAN()`                    | Removes non-printable characters | `=CLEAN(A2)`                                 |
| `LEFT()`, `RIGHT()`, `MID()` | Extracts specific text           | `=LEFT(A2,3)`                                |
| `AND()` / `OR()`             | Multiple condition validation    | `=AND(B2>0,C2<=50)`                          |

```
---
