
# ShopNow Customer Behavior & Sales Analytics

**Data Analytics Portfolio Project | Mayerfeld Consulting Data Analytics Practicum (2026)**

An end-to-end analysis of customer behavior, sales transactions, website engagement, and marketing campaign performance using Python, statistical analysis, and Tableau.

## 1. Project Overview

This project examines customer purchasing patterns, transaction performance, website engagement, and marketing campaign outcomes for a fictional retail business, ShopNow.

The objective is to transform raw business data into actionable insights that can support customer engagement, conversion optimization, sales performance, and marketing decisions.

## 2. Business Objectives

- Understand customer purchasing behavior and transaction patterns.
- Examine website engagement, bounce behavior, and conversion.
- Evaluate marketing campaign engagement and conversion outcomes.
- Investigate relationships between customer characteristics and purchasing behavior.
- Use statistical methods to assess selected business hypotheses.
- Present key findings through an interactive Tableau dashboard.

## 3. Datasets

The analysis uses four related CSV datasets:

| Dataset | Records | Description |
|---|---:|---|
| `customers.csv` | 10,000 | Customer profiles and characteristics |
| `transactions.csv` | 45,000 | Purchase transactions and sales information |
| `web_sessions.csv` | 70,100 | Website visits and engagement |
| `campaign_touchpoints.csv` | 10,000 | Marketing interactions and conversion outcomes |

## 4. Tools and Technologies

- **Python:** Data analysis and processing
- **pandas and NumPy:** Data cleaning, transformation, and exploration
- **Statistical analysis:** Hypothesis testing, correlation analysis, and interpretation
- **Jupyter Notebook:** Reproducible analytical workflow
- **Tableau:** Interactive dashboards and data visualization

## 5. Analytical Methodology

### Data Preparation

- Imported and inspected the four datasets.
- Reviewed data types, missing values, and data quality.
- Explored customer, transaction, website, and marketing variables.
- Combined related information where appropriate for analysis.

### Exploratory Data Analysis

- Examined customer demographics and purchasing behavior.
- Investigated transaction values and discount usage.
- Explored website sessions, bounce behavior, and conversion.
- Compared marketing campaign engagement and outcomes.

### Statistical Analysis

- Applied statistical hypothesis testing to selected business questions.
- Examined associations between categorical variables.
- Compared group-level purchasing and conversion patterns.
- Distinguished statistical significance from practical business importance.

### Dashboard Development

Developed a Tableau dashboard to communicate key customer behavior and sales insights.

## 6. Selected Analytical Findings

The analysis identified several patterns worth investigating further:

- **Device conversion:** Approximately 13.3% for desktop, 13.1% for mobile, and 13.0% for tablet sessions.
- **Bounce behavior:** Non-bounced sessions showed approximately 13.5% conversion compared with 11.5% for bounced sessions.
- **Purchase value:** Average purchase values were relatively similar across the examined gender categories, at approximately $234–$236.
- **Discount usage:** Approximately 30% of transactions involved discounts.

These findings describe observed relationships in the dataset and should not automatically be interpreted as causal effects.

## 7. Business Recommendations

1. **Improve website engagement:** Investigate high-bounce customer journeys and potential friction points.
2. **Monitor conversion by device:** Continue tracking device-specific performance, even where observed differences are relatively small.
3. **Evaluate discount effectiveness:** Assess whether promotions improve incremental revenue and customer retention.
4. **Strengthen customer segmentation:** Use purchasing and engagement patterns to inform targeted marketing.
5. **Monitor business KPIs:** Track conversion rate, average transaction value, engagement, and campaign performance.

## 8. Project Files

```text
shopnow-customer-sales-analytics/
│
├── Notebooks/
│   ├── 01_exploratory_data_analysis.ipynb
│   └── 02_statistical_analysis.ipynb
│
├── data/
│   ├── customers.csv
│   ├── transactions.csv
│   ├── web_sessions.csv
│   └── campaign_touchpoints.csv
│
├── dashboards/
│   ├── ShopNow Customer Behavior and Sales Analytics.twbx
│   └── ShopNow Customer Behavior and Sales Analytics.pdf
│
├── .gitignore
├── .gitattributes
└── README.md
```

## 9. How to Explore This Project

1. Open `Notebooks/01_exploratory_data_analysis.ipynb` to review the exploratory analysis.
2. Open `Notebooks/02_statistical_analysis.ipynb` to examine the statistical methods and findings.
3. Review the PDF report in `dashboards/` for the visual presentation.
4. Open the `.twbx` file using Tableau Desktop or a compatible Tableau application to explore the dashboard.

## 10. Project Context

This project was developed as part of the Mayerfeld Consulting Data Analytics Practicum in 2026 and is presented as evidence of practical data analysis, statistical reasoning, and business intelligence skills.

## Author

**Isabirye Augustine**  
Data Analyst | Business Intelligence | Operations Analytics

[GitHub Profile](https://github.com/isabiryeaugustine)
