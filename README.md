# Customer Segmentation and Sales Analysis

## Business Requirement

1. Identify top customers by segment and state to optimize marketing strategies, and determine top services by month to boost sales.
2. Analyze top services based on sales revenue and profit to guide business decisions.

## Tools and Functionalities Used 

MS Excel (Pivot Tables, Conditional Formatting, Data Validation, Data Analysis Toolpak), Power Query, DAX measures, and Data Visualization tools.

## Approach

### Data Cleaning and Loading

I used Power Query in MS Excel to rename columns, remove null/ duplicate values, add new columns like month, concatenate address columns to separate it from street number and loaded the dataset back to the excel sheet.

<img width="1224" height="347" alt="image" src="https://github.com/user-attachments/assets/0fda262b-69af-4bab-9ff7-57c123ab7c85" />

### Transformation

After loading I grouped the coustomers based on the services they used and extracted month column from date using IF ELSE and TEXT formulas and sorted them by month order.

<img width="648" height="277" alt="image" src="https://github.com/user-attachments/assets/9af7d87e-3efe-4ddf-b5db-706dd76b1606" />

### Analysis

I made two different sheets. One for Cusomter Analysis and other for Sales Analysis. 

I used Data Analysis Toolpack for Exploratory Data Analysis.

<img width="437" height="302" alt="image" src="https://github.com/user-attachments/assets/949e4457-5f04-475a-9180-4c1cd41d2308" />

<img width="399" height="295" alt="image" src="https://github.com/user-attachments/assets/30f1d369-a1e7-4b53-b7c1-72c9957a9313" />

### Pivot Tables

The main feature for this Analysis was Pivot Tables.

## Customer Analysis

Used Pivot table for analysis.

1) Customers by State

<img width="582" height="336" alt="image" src="https://github.com/user-attachments/assets/2c92b596-733d-489b-8c1f-b62b13d2796b" />

2) Customers by Segment

<img width="646" height="393" alt="image" src="https://github.com/user-attachments/assets/92466279-37e1-4148-8846-2a470d6c2c3b" />

3) Quantity ordered by month and service

<img width="1126" height="312" alt="image" src="https://github.com/user-attachments/assets/78604077-2f40-4aab-aa4c-92cd50e8df3c" />

## Sales Analysis

1) Sales by Service

I used DAX to calulate profit percentage.

<img width="535" height="299" alt="image" src="https://github.com/user-attachments/assets/e8e12557-8c71-4569-a2e6-7d30fc971f16" />

2) Sales by Agent

<img width="1006" height="342" alt="image" src="https://github.com/user-attachments/assets/7d149302-5b78-4696-b0ae-83b6974c2c61" />

3) Sales by Month

<img width="828" height="301" alt="image" src="https://github.com/user-attachments/assets/2bf11d3f-b972-45a0-b391-305fe5c05a63" />


## Insights

### Customer Insights

1. NSW is our Strongest Revenue Driver
NSW leads both in customer count (136) and total sales ($171,650), making it the most valuable market.
Our business growth is heavily supported by NSW. Any small improvement here will create a big impact on total revenue.

2. Opportunity in NT
NT has higher sales ($187,050) despite fewer customers (133) compared to NSW and VIC.
This means NT customers spend more per person.

3. Gold customers are the core revenue group
Gold customers form 354 out of 1000 customers, meaning over 35% of our customer base.

4. Bronze segment is a growth opportunity - Bronze customers make up 291 customers – a large entry-level segment.

5. Mentoring program is our top service
Mentoring program has the highest total orders (543) across the year.

6. Seasonal demand spikes March, June, August, November, and December show higher total orders (200+ in some months).

Increase staff availability and service capacity during these months.
Offer packages or promotions during slow months (April, May).

7. Interview Prep + LinkedIn Profile have growth potential

These services show moderate volume but consistent monthly demand.
Bundle them with high-performing services like Mentoring programs to increase cross-selling and average order value.

### Sales Insights

1.  Profitability & Cost Efficiency

The business generated $890,427 in total sales and $683,960 in total profit, achieving a strong overall profit margin of 76.78%.However, Service Provider Expenses totalled $206,466, accounting for 23.2% of total sales.

A 5% reduction in service provider costs could generate an additional $10,323 in profit without increasing sales volume.
This can be achieved through vendor negotiations, bulk service agreements, or optimizing provider allocation.

2. Top Performing Services
Mentoring Program , Interview Preparation and Networking Service contribute nearly 60 % of total profit. 
Increasing sales of the Mentoring Program by just 10% could result in approximately $16,800 additional profit.
Strategic focus can be placed on these top services through marketing promotions, bundling, and premium service packaging.

3. Monthly Profit Trend & Seasonality
Difference between higest profit month (March)  and lowest profit month ( April) is $22,922.65.
Even a 10% increase in April sales could generate an additional  $4,500 monthly profit.
We may introduce targeted promotions or service bundles during low-performing months (April–May).
















