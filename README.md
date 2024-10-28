# OneStop Electronics E-Commerce Analysis

## Company Background

![OneStopElectronics Logo](https://github.com/user-attachments/assets/f8007ef5-afd6-4cf1-8cf0-3dc63c9ae42a)

Founded in 2018, OneStop Electronics is a global e-commerce company specializing in popular electronics products. Initially focused on selling through its online platform, the company has rapidly grown, attracting customers worldwide. With a product portfolio that includes high-demand brands such as Apple, Samsung, and Lenovo, OneStop Electronics has become a go-to destination for electronics enthusiasts. The company leverages multiple marketing channels—email campaigns, search engine optimization (SEO), and affiliate partnerships—to reach its expanding customer base. As the business scales, OneStop Electronics continues to strive for excellence in delivering cutting-edge products and customer satisfaction.

# Find Out More!

<details>
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

- In 2020, the company experienced a significant spike in sales across all metrics. Sales revenue more than doubled to $10M, driven by a twofold increase in order volume (34K orders). The average order value also saw a 30% year-over-year (YoY) increase, reaching $300. March 2020 marked the highest month-over-month (MoM) growth in the company's history, with a 50% increase in sales. This surge can likely be attributed to the impact of COVID-19 and the resulting lockdowns

- However, since 2020, the company has struggled to sustain the high sales levels seen during the pandemic. As global activities returned to normal, OneStop Electronics experienced a decline in YoY growth, with sales revenue dropping by 10% in 2021 and a sharper decline of 46% in 2022. AOV and order count have also followed a similair trend

<p align="center" width="100%">
<img src="https://github.com/user-attachments/assets/8af24b46-5e93-4d26-87cb-f435ac9304ce"> 
</p>

The following analysis will provide key insights to help guide the company’s strategy moving forward, focusing on areas like geographical trends, product mix, and loyalty program performance. These insights will enable OneStop Electronics to take informed action and identify new opportunities for growth and efficiency as the company navigates post-pandemic challenges.

# Sales Trends

## Historical

<p align="center" width="100%">
<img src="https://github.com/user-attachments/assets/ef05defe-018d-46bf-8e2f-f60b3855d3c0">
</p>

### Sales Revenue
- From January 2019 to December 2020, OneStop Electronics saw steady growth in sales revenue, averaging a 7% monthly increase. The company reached a peak of $1.2M in December 2020, compared to a company-wide average monthly growth of just 1.4% from 2019-2022. On average, the company generated $585K in monthly revenue
- Following this peak, the company experienced two consecutive months of decline: -18% in January 2021 and -31% in February 2021. Since December 2020, sales have generally declined, with the largest drop occurring in October 2022 (-55%), where sales fell to $178K
- Despite the overall downward trend, there were moments of recovery. From June to September 2021, sales grew by 10% monthly on average, and a 36% spike occurred from November to December 2021

### AOV
- In contrast to sales revenue, AOV has remained relatively stable. From 2019 to 2022, the average monthly AOV was $253, with a modest average monthly growth rate of 0.3%
- AOV peaked at $322 per order in October 2020 but dropped to a low of $217 by October 2022. After this dip, AOV grew by 4% in November 2022 and 3% in December 2022

### Order Count
- Order count trends closely followed sales revenue. From 2019-2022, the average monthly growth rate for orders was 1.1%, with an average of 2K orders per month
- The company saw its highest order volume in December 2020, with 4K orders, and its lowest in October 2022, with 825 orders

## Seasonal

<p align="center" width="100%">
<img src="https://github.com/user-attachments/assets/2368b333-720c-44e5-961b-ea3f1fb1b32d" height="75%" width="75%">
</p>

- **Best Performing Months:** Jan, Sep, and Dec consistently generate the highest order counts and revenue, contributing 25% of total company sales in these three months alone
- **Worst Performing Months:** In contrast, sales and order counts tend to dip in Feb, June, and Oct, with Feb and Oct typically seeing a 25% decline from the previous month
- **Fall Season Trend:** The data show a seasonal increase in AOV during the fall, with averages of $263 in Aug, $268 in Sep, and $272 in Oct

# Geographical Trends

OneStop Electronics operates across four regions and 194 countries. A closer examination of geographical trends will provide valuable insights into the company’s performance across different markets, helping to identify both current challenges and potential opportunities for growth.

## Regional 

<p align="center" width="100%">
<img src="https://github.com/user-attachments/assets/f5c1dc17-879a-4b23-9a87-06725651a82c" height="75%" width="75%">
</p>

- Across all regions, OneStop Electronics averaged $7M in sales with 26K orders
- **Best Performing Region (Sales):** North America was the best-performing region, generating $14M in sales and accounting for more than 50% of total company sales.
- **Worst Performing Region (Sales):** In contrast, Latin America was the lowest-performing region, with just $1.6M in sales
- **Leading Region in AOV:** APAC leads in terms of the highest average order value (AOV), with an average AOV of $280. This is largely driven by Japan, which has an exceptionally high AOV of $393

## By Country

<p align="center" width="100%">
<img src="https://github.com/user-attachments/assets/d13b27cb-045c-4571-babd-22d0ecc477a3" height="75%" width="75%">
</p>

- **Top Performing Country:** The United States is the company's top-performing country, driving 47% of total sales, and is the primary contributor to North America's dominance in both sales revenue and order count
- **Top 10 Countries:** The top 10 countries by sales revenue account for approximately 80% of total sales. These countries, ranked by sales revenue, are: United States, United Kingdom, Canada, Japan, Germany, Australia, Brazil, France, Spain, and the Netherlands
- **AOV Performance:** Among these top 10 countries, Japan ($393) and the Netherlands ($289) have the highest AOV, while Spain has the lowest AOV at $223

# Product Trends

<p align="center" width="100%">
<img src="https://github.com/user-attachments/assets/3e52ce6f-9474-4fba-a3ca-e2c5b39e8d09" height="75%" width="75%">
</p>

### Best Performing Products

- The top three products by sales revenue: 27-inch 4K Gaming Monitor, Apple AirPods, and MacBook Air account for 85% of total sales, generating $9.8M, $7.7M, and $6.2M, respectively
- The products with the highest average order value (AOV) are the MacBook Air ($1,591), ThinkPad ($1,101), and Apple iPhone ($741)
- Apple AirPods lead in order volume with 48K orders, followed by the 27-inch 4K Gaming Monitor with 23K orders, and the Samsung Charging Cable Pack with 21K orders

### Worst Performing Products
- The worst performing products in terms of sales revenue and order counts are the Bose Soundsport and Apple Iphone, while Samsung products have the lowest AOV across the board
- Across all metrics, the Bose Soundsport underperformed, with just $3K in total sales and 27 orders. Its low AOV further reinforced its weak performance

### Notable Insights:
- Despite low sales and order counts, the Apple iPhone has the third-highest AOV, indicating untapped potential. By exploring ways to increase iPhone sales, the company could significantly boost overall revenue if the high AOV trend persists
- Macbook Air sales were the main driver of the company's revenue spike in 2020 growing a whopping 384% from 2019 to 2020 (more than double the growth of the next highest product in terms of YoY growth from 2019 to 2020)
   
# Loyalty Program

> ### Should the company keep the loyalty program?
<p align="center" width="100%">
<img src="https://github.com/user-attachments/assets/57d9faa4-8884-4bcc-b714-8c6da342662b" height="85%" width="85%">
</p>

The company introduced a loyalty program in 2019 to incentivize customers to make more frequent purchases. Five years later, they are evaluating whether to continue the program.

### Key Insights:
- Overall, non-loyalty members have outpaced loyalty members in total sales, generating $17M compared to $11M, with generally higher AOV (except in 2022)
- However, a trend reversal occurred after the first two years. Since then, loyalty members have surpassed non-loyalty members in both sales and order count
- Additionally, loyalty members' AOV has been steadily rising and, by 2022, exceeded the AOV of non-loyalty members

### Recommendation:
Although the data does not provide a decisive conclusion about the loyalty program's impact, the upward trend in loyalty members' performance, particularly in the last two years, suggests potential for future growth. Based on this, it is recommended to retain the loyalty program and closely monitor its performance over the next few years. The recent positive trends warrant further observation before making a long-term decision.

<!-- Commented out parts -->

# Refund Rates

**Overall Refund Rate:** The company-wide refund rate was 5%, with 5,377 refunds out of 108K orders, totaling $2.1M in refunded sales

## Across All Products

<p align="center" width="100%">
<img src="https://github.com/user-attachments/assets/97bf2075-c726-480a-8aa3-3c603e470fb8">
</p>

### Most Refunded Products:
- **Highest Refund Rates:** ThinkPad (11.7%), MacBook Air (11.4%), and Apple iPhone (7.6%) had the highest refund rates
- **Most Frequent Refunds:** Apple AirPods and the 27-inch 4K Gaming Monitor were refunded most often, with 2.6K and 1.4K refunds, respectively
- **Highest Total Refund Amounts:** The MacBook Air ($719K), 27-inch 4K Gaming Monitor ($607K), Apple AirPods ($421K), and ThinkPad ($376K) recorded the highest total refunded sales

### Least Refunded Products:
- **Lowest Refund Rates:** The Samsung Charging Cable Pack and Samsung Webcam had refund rates of 1.3% and 2.6%, respectively
- **Lowest Refund Counts:** The Apple iPhone had the lowest refund count, with only 22 refunds, followed by the Samsung Webcam with 186 refunds
- **Lowest Total Refund Amounts:** The Samsung Charging Cable Pack ($6K), Samsung Webcam ($9.3K), and Apple iPhone ($6K) had the lowest refunded sales amounts

**Note:** The Bose Soundsport was the only product never refunded

### Notable Insights: 
- Together, Apple Airpods (49%) and 27in 4K Gaming Monitor (27%) make up more than 75% of all refunds in terms of refund counts
- More than 75% of all refunds occurred before 2021 with 18% in 2019 and 58% in 2020
- 2022 had no refunds

## Spotlight: Apple Products 

<p align="center" width="100%">
<img src="https://github.com/user-attachments/assets/5045d1ff-ff27-4210-9c9b-ac8653c27fc3">

</p>

<p align="center" width="100%">
<img src="https://github.com/user-attachments/assets/4fc8c094-0f18-4e4e-83cf-6d0ed2542c06">
</p>

### Refund Metrics: 
- Apple products have an overall refund rate of 5.9%, totaling slightly over 3K refunds
- The MacBook Air has the highest refund rate among Apple products at 11.4%, while Apple AirPods were refunded most frequently, with 2.6K refunds, making up 85% of all Apple refunds

### Notable Insights:
- Apple products account for 58% of all refunds, totaling $841K—the highest refund amount of any brand
- Approximately 60% of Apple refunds occurred in 2020, with a notable decrease in 2021 and no refunds recorded in 2022

<!-- 
# Recommendations

# Appendix: Tables & Graphs
> <details>
>  <summary>Yearly Product Trends (Drivers of 2020 Spike)</summary>
> <p align="center" width="100%">
> <img src="https://github.com/user-attachments/assets/c2110688-a93c-4e26-ab6d-33fb03121521" height="85%" width="85%">

> </p>
> </details>

> <details>
>  <summary>Pivot Table - Yearly Product Refund Trends</summary>
> <p align="center" width="100%">
> <img src="https://github.com/user-attachments/assets/8b0f6ea0-107c-4e92-9ff4-b57a0ff07e6d" height="85%" width="85%">
> </p>
> </details>
-->
