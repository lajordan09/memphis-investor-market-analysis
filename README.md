# Memphis Investor Market Analysis

### Real Estate Analytics | Investor Behavior | Memphis, Tennessee

An exploratory real estate analytics project examining investor purchasing patterns across selected Memphis, Tennessee ZIP codes using a synthetic residential transaction dataset.

---

## Project Overview

Real estate professionals and investors can use data analytics to identify geographic patterns, pricing differences, and property characteristics associated with investor activity.

This project explores the following business question:

> **Can property characteristics and location help identify patterns in investor purchasing activity in Memphis, Tennessee?**

The analysis compares **investor** and **owner-occupant** purchases and examines differences in purchase volume, pricing, property size, bedrooms, year built, and price per square foot.

---

## Business Objective

The objective of this project is to demonstrate how residential transaction data can be transformed into useful market intelligence for real estate professionals and investors.

The analysis focuses on:

- Investor purchase activity by ZIP code
- Average investor purchase price
- Average investor price per square foot
- Average investor home size
- Average investor bedroom count
- Average investor property age

The broader goal is to explore how real estate analytics could support:

- Investor prospecting
- Market research
- Property targeting
- Lead generation
- Investment screening
- Future predictive analytics

---

## Dataset

The dataset contains **100 synthetic single-family residential transactions** across five Memphis ZIP codes.

| ZIP Code | Transactions |
|----------|-------------:|
| 38115 | 20 |
| 38116 | 20 |
| 38118 | 19 |
| 38127 | 20 |
| 38128 | 21 |
| **Total** | **100** |

### Variables

The dataset includes:

- `Property_ID`
- `ZIP_Code`
- `Sale_Price`
- `Bedrooms`
- `Bathrooms`
- `Sq_Ft`
- `Year_Built`
- `Sale_Date`
- `Buyer_Type`

### Buyer Types

Transactions are categorized as:

- **Investor**
- **Owner Occupant**

---

## Data Disclaimer

> **This project uses a synthetic dataset created for educational and portfolio purposes. The data is not actual MLS, public-record, or proprietary transaction data and should not be interpreted as a representation of actual Memphis market activity.**

The findings are therefore examples of analytical techniques rather than factual conclusions about the Memphis real estate market.

---

# Methodology

The project was developed using Microsoft Excel and PivotTables/PivotCharts.

### 1. Data Preparation

A structured transaction dataset was created containing property characteristics, transaction information, ZIP code, and buyer type.

### 2. Buyer Segmentation

Transactions were separated into:

- Investor
- Owner Occupant

This allowed purchasing behavior to be compared across geographic areas.

### 3. ZIP Code Analysis

PivotTables were used to calculate investor and owner-occupant purchase counts by ZIP code.

### 4. Price Analysis

Average investor purchase prices were calculated for each ZIP code.

### 5. Property Characteristics

Investor properties were analyzed using:

- Average square footage
- Average bedrooms
- Average year built
- Average price per square foot

### 6. Visualization

PivotCharts were created to communicate the results through an interactive-style dashboard.

---

# Key Findings

## Investor Activity

In the synthetic sample:

**59 of 100 transactions were classified as investor purchases**, representing **59% of the sample**.

Investor purchases therefore represented the larger buyer segment within this simulated dataset.

---

## Investor Purchase Volume by ZIP Code

| ZIP Code | Investor Purchases |
|----------|-------------------:|
| 38115 | 17 |
| 38116 | 2 |
| 38118 | 8 |
| **38127** | **19** |
| 38128 | 13 |

### Key Observation

**ZIP Code 38127 had the highest investor purchase volume with 19 transactions.**

This suggests that 38127 would be a ZIP code worth investigating further in a real-world dataset.

---

## Average Investor Purchase Price

The overall average investor purchase price in the synthetic sample was approximately:

### **$158,941**

| ZIP Code | Average Investor Purchase |
|----------|--------------------------:|
| 38115 | $184,088 |
| 38116 | $240,000 |
| 38118 | $210,625 |
| 38127 | $109,711 |
| 38128 | $153,731 |

The results demonstrate that average investor purchase prices can vary significantly between ZIP codes.

---

## Investor Price per Square Foot

The overall average investor price per square foot was approximately:

### **$106.18 / Sq. Ft.**

| ZIP Code | Average Investor $/Sq. Ft. |
|----------|---------------------------:|
| 38115 | $116.64 |
| 38116 | $109.11 |
| **38118** | **$135.47** |
| 38127 | $92.07 |
| 38128 | $94.67 |

### Key Observation

**ZIP Code 38118 had the highest average investor price per square foot at $135.47.**

Interestingly, **38127 had the highest investor purchase volume but the lowest average investor price per square foot at $92.07.**

This demonstrates why investor market analysis should consider both **purchase volume and pricing metrics** rather than relying on a single measure.

---

# Business Recommendations

Because this project uses synthetic data, these recommendations should be treated as **analytical hypotheses rather than investment recommendations**.

## 1. Monitor High-Volume Investor ZIP Codes

The analysis identifies **38127** as the ZIP code with the highest investor purchase volume in the sample.

A real-world analysis could investigate whether this pattern continues using actual transaction data.

---

## 2. Separate Investor Volume from Pricing

Investor activity should not be evaluated solely by transaction count.

For example:

**38127**
- Highest investor purchase volume
- Lowest average investor $/Sq. Ft.

**38118**
- Lower investor purchase volume
- Highest average investor $/Sq. Ft.

This demonstrates the importance of evaluating multiple metrics when analyzing investor behavior.

---

## 3. Analyze Property Characteristics

Future analysis could combine:

- ZIP code
- Sale price
- Square footage
- Year built
- Bedrooms
- Price per square foot

to identify property profiles that appear more frequently among investor purchases.

This could eventually support an investor-focused property scoring model.

---

## 4. Develop an Investor Prospecting Workflow

A potential real estate analytics workflow could be:

**Market Data → Identify Investor Patterns → Identify Properties → Research Ownership → Investor Outreach → Track Relationships**

This creates a connection between real estate analytics, business development, and PropTech.

---

# Limitations

### Synthetic Dataset

The dataset was created for educational purposes and does not represent actual Memphis transactions.

### Sample Size

The dataset contains only 100 transactions across five ZIP codes.

### Limited Variables

The current dataset does not include several important investment metrics, including:

- Rental income
- Renovation costs
- Property taxes
- Insurance
- Vacancy
- Cap rate
- Cash-on-cash return
- Financing
- After-repair value (ARV)
- Days on market

### No Causal Analysis

The analysis identifies patterns within the sample but does not establish that a specific property characteristic causes an investor to purchase a property.

---

# Future Improvements

## Version 2 — Real Market Data

Replace the synthetic dataset with actual publicly available or properly licensed transaction data.

Potential additional variables could include:

- Days on market
- Listing price
- Sale-to-list ratio
- Rental estimate
- Property taxes
- Ownership duration
- Investor ownership history

---

## Version 3 — Investor Scoring Model

Develop an:

> **Investor Purchase Probability Score**

Potential inputs could include:

- ZIP-level investor activity
- Sale price
- Price per square foot
- Property age
- Square footage
- Bedroom count
- Market inventory
- Historical investor activity

---

## Version 4 — Interactive Power BI Dashboard

The Excel analysis could be migrated into Power BI to create an interactive dashboard.

Potential filters:

**ZIP Code | Buyer Type | Price Range | Year Built | Property Size**

Potential dashboard components:

- Investor purchase volume
- Investor market share
- Average investor purchase price
- Average investor $/Sq. Ft.
- Investor activity by ZIP
- Property characteristic comparisons

---

## Version 5 — Predictive Analytics

A future version of this project could explore:

> **Can investor purchasing patterns in Memphis be predicted using property characteristics and market conditions?**

A predictive model could estimate the probability that a property matches historical investor purchasing patterns.

---

# Tools & Skills

### Tools

- Microsoft Excel
- PivotTables
- PivotCharts
- Data Visualization

### Skills Demonstrated

- Data preparation
- Exploratory data analysis
- Real estate market analysis
- Segmentation
- Geographic analysis
- KPI development
- Data visualization
- Business insight generation
- Analytical storytelling

---

# Project Dashboard

The final Excel dashboard summarizes the analysis using KPI cards and visualizations.

### Dashboard Metrics

- **100** Total Transactions
- **59%** Investor Share
- **$158,941** Average Investor Purchase
- **$106.18** Average Investor Price/Sq. Ft.

### Dashboard Visualizations

1. Investor vs. Owner-Occupant Purchases by ZIP Code
2. Average Investor Price per Square Foot by ZIP Code

---

# Portfolio Takeaway

This project demonstrates how real estate transaction data can be transformed into actionable insights using data preparation, segmentation, PivotTables, and visualization.

The analysis highlights geographic differences in investor activity and pricing while demonstrating how analytics could support investor prospecting, market research, and future PropTech applications.

The project also provides a foundation for moving from **descriptive analytics** toward **predictive real estate analytics**.

---

# Repository Structure

```text
memphis-investor-market-analysis/
│
├── README.md
│
├── data/
│   └── Memphis_Investor_Data.csv
│
├── excel/
│   └── Memphis_Investor_Data.xlsx
│
├── dashboard/
│   └── Memphis_Investor_Dashboard.png
│
├── documentation/
│   └── methodology.md
│
└── screenshots/
    └── dashboard.png
```
# Author

**LaQuita Jordan**

Data Analytics Graduate Student
Residential Real Estate Professional
Trelora Realty | Home Boss Team
Memphis, Tennessee

This project represents an exploration of the intersection of:

**Real Estate + Data Analytics + Investor Behavior + PropTech**
