# OneStop Electronics E-Commerce Analysis

## Company Background

![OneStopElectronics Logo](https://github.com/user-attachments/assets/f8007ef5-afd6-4cf1-8cf0-3dc63c9ae42a)

Founded in 2018, OneStop Electronics is a global e-commerce company specializing in popular electronics products. Initially focused on selling through its online platform, the company has rapidly grown, attracting customers worldwide. With a product portfolio that includes high-demand brands such as Apple, Samsung, and Lenovo, OneStop Electronics has become a go-to destination for electronics enthusiasts. The company leverages multiple marketing channels—email campaigns, search engine optimization (SEO), and affiliate partnerships—to reach its expanding customer base. As the business scales, OneStop Electronics continues to strive for excellence in delivering cutting-edge products and customer satisfaction.

# Find Out More!

<details open>
  <summary>Project Goals</summary>
<br /> 
OneStop Electronics has been collecting data on a variety of key elements, including orders, order statuses, customer information, products, and geographic data. However, the data is currently unrefined and underutilized, presenting both challenges and opportunities for unlocking valuable insights.
<br /> 
<br /> 
In cleaning and analyzing OneStop's data, meaningful insights can be extracted from the dataset to support the company’s various teams—including finance, sales, product, and marketing. By providing actionable data insights, our aim is to improve operational efficiencies and drive better decision-making, ultimately helping OneStop Electronics optimize its processes and deliver superior products globally. 
</details>

<details>
  <summary>About Our Data</summary>
<br /> 
Prior to analyzing the data, a series of actions were taken to ensure the dataset was understood and ready for analysis.
<br /> 
<br /> 
  
**For more details about the dataset and the data cleaning process see below:** <br /> 
- Dataset Summary & Issue Log [here](https://drive.google.com/file/d/16kxh6qG9sHhr-ZR1ZikRC5AjvIbR3Uq5/view?usp=sharing) <br /> 
- Check out the ERD [here](https://github.com/user-attachments/assets/31778750-444f-4955-b73f-fc152ed77e35)
</details>

<details>
  <summary>Stakeholder Questions</summary>
<br /> 
1. What were the overall sales trends from 2019 to 2022? <br /> 
2. What were the company's yearly and monthly growth rates? <br /> 
3. How has the new loyalty program performed? Should we keep using it? <br /> 
4. What was the company's refund rate and average order value (AOV)? <br /> 
<br /> 

**Notes:**
- Focus on sales revenue, AOV, and order counts
- Look at trends over yearly and monthly periods 
- For refunds and AOV specifically compare across Apple products
</details>

# Executive Summary

OneStop Electronics' total sales from 2019 to 2022 reached $28M, with 108K total orders. The company's average order value (AOV) across all years stands at $260 per order.

- In 2020, the company experienced a significant spike in sales across all metrics. Sales revenue more than doubled to $10M, driven by a twofold increase in order volume (34K orders). The average order value also saw a 30% year-over-year (YoY) increase, reaching $300. March 2020 marked the highest month-over-month (MoM) growth in the company's history, with a 50% increase in sales. This surge can likely be attributed to the impact of COVID-19 and the resulting lockdowns.

- However, since 2020, the company has struggled to sustain the high sales levels seen during the pandemic. As global activities returned to normal, OneStop Electronics experienced a decline in YoY growth, with sales revenue dropping by 10% in 2021 and a sharper decline of 46% in 2022. AOV and order count have also followed a similair trend.

<p align="center" width="100%">
<img src="https://github.com/user-attachments/assets/8af24b46-5e93-4d26-87cb-f435ac9304ce"> 
</p>

The following analysis will provide key insights to help guide the company’s strategy moving forward, focusing on areas like geographical trends, product mix, and loyalty program performance. These insights will enable OneStop Electronics to take informed action and identify new opportunities for growth and efficiency as the company navigates post-pandemic challenges.

# Summary of Insights

## Sales Trends

### Historical

> <details open>
>  <summary>Graph - Monthly Sales Trends</summary>
> <p align="center" width="100%">
> <img src="https://github.com/user-attachments/assets/ef05defe-018d-46bf-8e2f-f60b3855d3c0">
> </p>
> </details>

#### Sales Revenue
- From January 2019 to December 2020, OneStop Electronics saw steady growth in sales revenue, averaging a 7% monthly increase. The company reached a peak of $1.2M in December 2020, compared to a company-wide average monthly growth of just 1.4% from 2019-2022. On average, the company generated $585K in monthly revenue.
- Following this peak, the company experienced two consecutive months of decline: -18% in January 2021 and -31% in February 2021. Since December 2020, sales have generally declined, with the largest drop occurring in October 2022 (-55%), where sales fell to $178K.
- Despite the overall downward trend, there were moments of recovery. From June to September 2021, sales grew by 10% monthly on average, and a 36% spike occurred from November to December 2021.

#### AOV
- In contrast to sales revenue, AOV has remained relatively stable. From 2019 to 2022, the average monthly AOV was $253, with a modest average monthly growth rate of 0.3%.
- AOV peaked at $322 per order in October 2020 but dropped to a low of $217 by October 2022. After this dip, AOV grew by 4% in November 2022 and 3% in December 2022.

#### Order Count
- Order count trends closely followed sales revenue. From 2019-2022, the average monthly growth rate for orders was 1.1%, with an average of 2K orders per month.
- The company saw its highest order volume in December 2020, with 4K orders, and its lowest in October 2022, with 825 orders.

---

### Seasonal

> <details open>
>  <summary>Pivot Table - Seasonal Analysis</summary>
> <p align="center" width="100%">
> <img src="https://github.com/user-attachments/assets/2368b333-720c-44e5-961b-ea3f1fb1b32d" height="75%" width="75%">
> </p>
> </details>

- Jan, Sep, and Dec bring in the most revenue on average, generating 25% of total company sales in these 3 months alone.
- Conversely, sales typically slump in Feb, June, and Oct. 
- The data show a seasonal uptick in AOV over the fall season with average AOVs of $263 in Aug, $268 in Sep, and $272 in Oct. 

## Geographic Trends

### Regional
> <details>
>  <summary>Graph - Regional Trends</summary>
> <p align="center" width="100%">
> <img src="https://github.com/user-attachments/assets/89c80c23-7a87-419f-a72b-8f362e8d0d70" height="75%" width="75%">
> </p>
> </details>

- 

---

### By Country
> <details>
>  <summary>Graph - Top 10 Country Sales</summary>
> <p align="center" width="100%">
> <img src="https://github.com/user-attachments/assets/0296ee1a-ef5a-42f2-8d28-9990a6194c38" height="75%" width="75%">
> </p>
> </details>

- 

## Product Trends

## Loyalty Program

## Refund Rates

# Recommendations
