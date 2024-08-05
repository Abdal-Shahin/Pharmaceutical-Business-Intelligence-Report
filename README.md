# Pharmaceutical Business Intelligence Report

An in-depth project analyzing pharmaceutical business data from 2022 to June 2024, using SQL for data preparation and Power BI for visual storytelling. This project transforms raw data into actionable insights.

**Live Dashboard Link**: https://shorturl.at/35fKX

## COMPANY INFO & PROBLEM STATEMENT
This project focuses on a hypothetical pharmaceutical company seeking to enhance its business intelligence capabilities. The company operates in multiple markets, catering to a diverse customer base, including different age groups, genders, and buyer types.
The pharmaceutical company faced challenges in understanding key metrics, such as sales trends, market performance, customer segmentation, and regulatory compliance. The company needed a comprehensive business intelligence solution to derive actionable insights from their data to make informed strategic decisions.

## DATA
- **Sales Data**: Transactions from 2022 to June 2024.
- **Customer Data**: Demographics and segmentation information.
- **Product Data**: Details about drugs, including regulatory compliance.
- **Regulatory Data**: Compliance status and associated information.

## TRANSFORMATIONS PERFORMED

### In SQL:
1. **Data Cleaning**
   - Ensured 100% data integrity with zero missing values.

2. **Data Relationship**
   - Established Primary and Foreign Keys for robust data linkage.

3. **Data Enrichment**
   - Added a “Segment” column using `ALTER TABLE` and `UPDATE` functions.
   - Created a View for gross sales in millions.
   - Combined customer names into a "Full Name" column.

### In Power BI:
1. **Data Types**
   - Standardized data for seamless analysis.

2. **Calendar Table**
   - Generated a new table for time-based analysis.

3. **Customer Segmentation**
   - Categorized customers by age, enhancing demographic insights.

4. **Calculated Measures**
   - Developed over 20 DAX formulas for key insights, including MOM% revenue changes, compliance rates, and more.

5. **Data Modeling**
   - Built a robust data model for accurate and insightful reporting.

## METRICS
- **KPI Cards**: 
  - Quantity Sold: **251.37k**
  - Net Sales: **$66.39M**
  - Total COGS: **$12M**
  - Gross Revenue: **$54.38M**
- **MoM% Revenue Change**: Steady growth observed, with significant spikes towards the year's end.
- **Revenue Trends**: Peaks in 2023 with over $4M, steady between $4.4M and $4.2M.

<p align="center">
  <img src="https://github.com/user-attachments/assets/52805190-877d-4e7d-b07d-765973d3906e" width="800" />
</p>

## VISUALIZATIONS
- **KPI Cards** for key metrics.
- **Line Charts** to track revenue trends over time.
- **Bar Charts** for cost-benefit analysis.
- **Donut Charts** to represent market share by customer type, age group, and gender.
- **Tables** summarizing revenue by compliance status and market.
<p align="center">
  <img src="https://github.com/user-attachments/assets/30e93d15-ccfd-4d45-ac60-12de1b47ba37" width="500" />
  <img src="https://github.com/user-attachments/assets/cbc29731-f0eb-4301-bcb9-9ee042f6f774" width="500" />
  <img src="https://github.com/user-attachments/assets/6c844ea0-1181-4d50-b4cf-7564111e484a" width="500" />
</p>

## INSIGHTS
### Sales Insights:
- Doxycycline leads with a 95% gross revenue percentage, while Montelukast lags at 8%.

### Market/Customer Insights:
- Preferred customers contributed the highest revenue of **$19.39M**.
- Older adults (50-59) and adults (30-49) generated **53.29%** of gross revenue.
- Sellers outpaced users in revenue generation by a wide margin (**$47.8M** vs. **$6.6M**).
- Males held a **47%** share in sales, with females following at **32%**.

### Regulatory Insights:
- Only **23%** of drugs complied with regulatory standards.
- Non-compliant drugs, though fewer, drove the highest sales and revenue.

## INSIGHTS AND RECOMMENDATIONS
This comprehensive analysis provides crucial insights that can guide strategic decisions in the pharmaceutical industry. For instance:

1. **Focus on Top-Performing Drugs**: Doxycycline, with its 95% gross revenue percentage, should be prioritized in marketing and production strategies.
2. **Enhance Regulatory Compliance**: Improving compliance rates could reduce production costs from $60 to $51 on average, boosting overall profitability.
3. **Target Key Customer Segments**: With older adults and preferred customers generating significant revenue, targeted marketing campaigns can further enhance sales.
4. **Optimize Market Strategies**: Canada, being the highest revenue market at $24.3M, presents opportunities for deeper market penetration and tailored offerings.
5. **Address Gender Disparities**: The gender-based sales gap indicates potential for increasing female customer engagement, potentially expanding market share by focusing on their needs.

By leveraging these insights, stakeholders can make informed decisions to drive growth, ensure compliance, and optimize resource allocation effectively.

