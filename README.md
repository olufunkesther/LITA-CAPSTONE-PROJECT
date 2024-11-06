# LITA DATA ANALYSIS PROJECT

## Project 1: SALES PERFORMANCE ANALYSIS FOR SWIFT STORE

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Key Metrics](#key-metrics)

[Tools Used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Data Analysis](#data-analysis)

[Inference](#inference)

[Data Visualization](#data-visualization)

### Project Overview
---
This project aims to uncover key insights such as top-selling products, regional performance, and monthly sales trends of Swift store. The goal is to provide insights into revenue, units sold and products across regions. By analyzing these parameters in the data received, the focus is based on understanding revenue trends and sales performance across regions and in different products.

### Data Sources
---
The primary source of Data used here is the Sales Data provided by the sales department of Swift Store. The Data given is a table array of columns which include Product, Order ID, Customer ID, Region, Order Date, Quantity Sold and Unit Price.

### Project Objectives
---
This project was designed to address the following analysis goal of Swift Store:
- Revenue by Products and by Months: Determine the total and average revenue generated to give a sales overview.
- Region by Units sold: Analyzes the number of units sold per regions to identify the highest-selling locations.
- Region by Products and by Revenue: Analyses the products across the regions and give a regional breakdown.

### Key Metrics
---
- Revenue: sum of revenue column, grouped by regions and products.
- Unit sold: sum of quantity, grouped by region and months.
- Average Sales: analysed as total revenue/total unit sold for each region.

### Tools Used
---
- Microsoft Excel [Download Here](https://www.microsoftexcel.com)
 1. for Data Cleaning
 2. for Analysis
 3. for Data Visualization

- Structured Query Language Query for Querying of Data
  
- PowerBi for Data Visualization
  
- Github for Portfolio Building
 
 ### Data Cleaning and Preparation
  ---
  In the intial phase of the Data cleaning and preparations, we perform the following action;
  1. Removal of Duplicates: duplicates were identified and removed within the dataset.
  2. Handling missing variables: some variables like revenue were calculated.
  3. Data Formatting: the data was standardized in the right format.

### Exploratory Data Analysis
  ---
  EDA involved the exploring of the Data to answer some questions about the Data such as;
  - what is the total sales by products?
  - what are the top performing products?
  - what is the total revenue by products?
 
### Data Analysis
  ---
  Some formulars used during this analysis includes;

  ```
  Total Revenue = Total Sales * Unit price
  Average Revenue = Total Revenue/Unit sold
  ```

### Inference
---

#### Sales Trend
The Line chart visualization shows the monthly trend of revenue. The monthly trend shows that February had the highest revenue of **564,300** and September had the lowest revenue of **34,720**. The Line chart also shows the way rise and fall in revenue in different months and the seasons it depicts.
There was a rise in revenue in **December, January, February** (which depicts the **Harmattan season**) and another rise in revenue in **June, July and August** (which depicts the **summer season**) and a fall in revenue in **March, April and May** (which depicts the **dry season**) and another fall in revenue in **September, October and November** (which depicts the **rainy season**).

The Pivot table below is the analysis of this trend.

![image](https://github.com/user-attachments/assets/05b990cc-bd72-4384-9f9a-aa5ecdcc563c)


##### RECOMMENDATION
The store should carry out enticing marketing campaigns, promotions to targeted audience in seasons with high revenue and make provisons for unceratinties in seasons with low revenues. This wil help them note products that do well in these season as well as customers preference across these seasons.

#### Regional Breakdown
From the analysis of the data, below is the breakdown of Revenue and Sales by Region of Swift Store
1. South Region had the highest Revenue of **927,820** with a percentage of **44.16%** and highest Sales of **24,298** with a percentage of **35.49%**
2. East Region had a Revenue of **485925** with a percentage of **23.13%** and a sales **20,361** of with a percentage of **29.74%**
3. North Region had a Revenue of **378,000** with a percentage of **18.42%** and a sales of **12,402** with a percentage of **18.12%**
4. West Region had the lowest Revenue of **300,345** with a percentage of **14.29%** and lowest sales of **11,400** with a percentage of **16.65%**

The Pivot table below shows the analysis of this breakdown.
![image](https://github.com/user-attachments/assets/1ebc9c0c-a8e2-4fcd-8dfe-1159aa8fe1f5)

##### RECOMMENDATION

#### Top Performing Products
From the analysis done, below is the breakdown of Top performing products by Quantity sold and Revenue Generated by Sift Store.
1. Hat had the highest Sales of **15,929** and highest Revenue of **613,380**
2. Shoe had a Sales of **14,402** and Revenue of **485,600**
3. Shirt had a Sales **12,388** of and Revenue of **316,915**
4. Gloves had a Sales of **12,369** and Revenue of **296,900**
5. Socks had a Sales of **7,921** and Revenue of **208,230**
6. Jacket had the lowest Sales of **5,452** and lowest Revenue of **180,785**

The Pivot table below shows the analysis of this performance

![image](https://github.com/user-attachments/assets/ba253d64-e561-468a-bc81-41b2a91f7cf8)

##### RECOMMENDATION


### Data Visualization
---
![image](https://github.com/user-attachments/assets/c3ca2faa-4e06-4ad6-9a3b-d61a9dc01ce9)


|Heading 1|Heading 2|
|---------|---------|
|Table 1|Table 2|

