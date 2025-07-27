# 🧼 Entropi Supermarkets Dataset – Cleaned Edition

## 🌍 Regional Context
This dataset simulates weekly retail performance across supermarkets in **Eastern and Southern Africa**, focusing on realistic regional patterns. All monetary values have been standardized to **US Dollars (USD)** to ensure global consistency and comparability.

---

## 📘 Project Overview
Welcome to the cleaned version of the Entropi Supermarkets dataset, crafted specifically for showcasing data cleaning expertise. This repository highlights key preprocessing steps using Python, including missing value treatment, temporal structuring, and categorical normalization.

> **Note:** This project focuses purely on cleaning and preparation—no visualizations or machine learning included. Future repos may extend analytical insights from this base.

---

## 🎯 Objectives
- ✅ Demonstrate robust **EDA and cleaning logic** with pandas
- ✅ Simulate real-world retail inconsistencies for portfolio realism
- ✅ Create a **freelance-ready deliverable** suitable for Fiverr and GitHub

---

## 🔍 EDA Summary
Exploratory steps prior to cleaning included:
- `.shape`, `.info()`, `.describe()` for general structure and distribution
- Visual inspection of missingness, numeric outliers, and categorical spread
- Confirmed **no duplicate rows** in the raw dataset

---

## 🧹 Cleaning Workflow
- **Data Types**: Optimized columns for numeric and datetime processing
- **Missing Values**:
  - `Weekly_Sales`: Imputed using store-level weekly average
  - `CPI`: Filled with regional monthly CPI trends
  - Categorical Features: Missing values replaced with `"Unknown"`
- **Currency Conversion**:
  - All monetary values converted to **USD**
  - Conversion based on historical exchange rates during data window
- **Temporal Engineering**:
  - Added `YearMonth`, `Month`, and `Week` columns from `Date`
- **Export**:
  - Cleaned file saved as `entropi_supermarkets_data.csv`

---

## 🧾 Dataset Schema

| Column Name        | Description                                                   |
|--------------------|---------------------------------------------------------------|
| `Store`            | Store identifier                                              |
| `Date`             | Week-ending date (`YYYY-MM-DD`)                               |
| `YearMonth`        | Year–Month composite (`YYYY-MM`)                              |
| `Month`            | Calendar month extracted from `Date`                          |
| `Week`             | Week number (ISO) from `Date`                                 |
| `Weekly_Sales`     | Total weekly revenue in **USD**                               |
| `Holiday_Flag`     | `1` if holiday week, else `0`                                  |
| `Temperature`      | Regional temperature (°C)                                     |
| `Fuel_Price`       | Average fuel price in **USD per litre**                       |
| `CPI`              | Consumer Price Index                                          |
| `Unemployment`     | Regional unemployment rate (%)                                |
| `Product_Category` | Group (e.g. Electronics, Beverages)                                |
| `Profit`           | Weekly profit in **USD**                                      |
| `Quantity`         | Units sold per week                                           |
| `Mode_of_Sale`     | Sales channel (`Online`, `In-store`, etc.)                    |
| `Mode_of_Payment`  | Payment method (`Cash`, `Card`, `Mobile Money`, `Voucher`)    |

---

## 🛠 Tools Used
- Python 3.x
- pandas
- Jupyter Notebook

---

## 🧳 Portfolio Use
This project represents a sample freelance-ready cleaning job tailored for:
- ⚡ Showcasing practical cleaning workflows
- 📈 Preparing retail datasets for modeling or dashboarding
- 🌍 Representing East/Southern African data nuances

---

## 📬 Contact
Love to collaborate on freelance data prep, cleaning logic, or retail datasets with real-world impact.

- GitHub: (https://github.com/Mati-Ds))
- Fiverr: (https://www.fiverr.com/martin_mati/buying?source=avatar_menu_profile)
- Email: [martin.g.mati@gmail.com] 

---
