# Excel Sales Data Project

## 1. Introduction

Hi! My name is Max. This project involves a comprehensive analysis of a company's sales data. Using Excel, I performed data cleaning, conditional formatting, created a dashboard with pivot tables, and generated key business insights

## 2. Project Goals

With this project I want to generate key insights that can assist decision making and visualize useful data, the project adresses the following questions.

* What is the overall average deal size and total number of orders (KPI)?  
* How have total sales trended over time? 
* Who are the top 5 customers?   
* What are the top performing product lines?  
* How does sales performance vary across different territories?  

## 3. Data Cleaning and Preparation

When working with datasets the data can be very messy. Before visualizing the data, the data has to be cleaned and prepared to prevent errors in the later steps of the project. 

### Initial Obervation and Cleaning Methods

The first step when cleaning data should be to check for any duplicate values to ensure data integrity, but none were found. To ensure that the data validity we have to check for outliers and missspellings which can be done by activating and checking through filters. For most columns there were no significant errors detected.

### Data Type Formatting 

When opening the CSV file of the original data, Excel did not assign the correct data type for the columns that involve currency such as **PriceEach**,**Sales** and **MSRP**. I chose the Accounting format for better alignment and readability, as well as to prevent future calculation errors.

### Handling Categorical Data

An important step during the data cleaning process is to check for errors in categorical columns such as **Country**, **ProductLine** or **Territory** that are prone to missspellings which would affect our dashboard and pivot tables. In the **Territory** column, I found that "Japan" was incorrectly listed as its own territory and also included Singapore. I corrected these entries by reassigning them to the "APAC" territory for better clarity and consistency in the analysis. 

## 4. Analysis and Visualization

### Conditional Formatting

Conditional Formatting is a great tool to get a quick glimpse of and a feeling for the data. For the **Sales** and **DealSize** column I added a color gradient to visualize the revenue size. This allows users to quickly identify high-value transactions and larger deals at a glance. For the **Status** column I assigned colors according to its positivity making them easier to spot which is useful to detect and assess orders that were cancelled or disputed.

### Pivot Tables

To transform the raw data into business insights and to create our dashboard, we have to create pivot tables first for every chart that we want to visualize. I created 5 in total: Sales per Product Line, Sales per Territory, Quarterly Sales, Top 5 Customers and a Dashboard Summary that entails the Total Sales, Average Deal Size and Total Orders. All of these tables provide us with valuable information that decision makers can act on.

* **Sales per Product Line:** Classic Cars is the product line that sells the most by far while the Train product line sells the least. When decision makers see this they can decide in what product line to invest or to eliminate.
* **Sales per Territory:** In this pivot table we can see that the EMEA and NA markets are the leaders while the APAC region falls behind. With this information decision makers can decide on how to improve sales in the APAC territory and increase their market share.
* **Quarterly Sales:** The quarterly sales table tells us that most of our sales are made in the fourth quarter. Decision makers can utilize this insight to develop marketing strategies that boost sales during the first three quarters or focus on Q4 even more through advertising and marketing campaigns that capitalize on this trend and maximize sales during the holiday season.
* **Top 5 Customers:** By detecting the top 5 customers we can identify high-value and probable long-term customers that the company can put their focus on for strenghtening business relations and customized advertisement.
* **Dashboard Summary:** This gives us quick and valuable information about Key Performance Indicators (KPIs) to see wheter or not the company performs according to expectations. 

## 5. Final Dashboard

The final dashboard gathers all the pivot tables and transforms them into concise charts that provide all of the necessary information. The dashboard includes a summary of key performance indicators at the top, followed by the charts created from the remaining pivot tables. That way decision makers can comprehend the data quickly, monitor business health and develop business strategies.

![Dashboard Image](images/Dashboard%20Image.png)

## 6. Tools Used

Microsoft Excel for Data Cleaning, Analysis and Visualization