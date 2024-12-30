# Amazon Sales Data Analysis
## About
This project aims to explore the Amazon Sales data to understand top performing branches and products, sales trend of different products & customer behaviour. The aim is to study how sales strategies can be improved and optimized. The data set was provided by ineuron to complete the project and extract various information from it.
Here in this project, I developed a Power BI Dashboard to present insights into Amazon sales trends, highlighting region-specific and item-specific sales analyses across different years, quarters, months, and days. This comprehensive dashboard offers detailed insights into various sales trends.

## Purposes Of The Project
The major aim of thie project is to gain insight into the sales data of Amazon to understand the different factors that affect sales of the different branches.

## Problem Statement
Sales management has gained importance to meet increasing competition and the need for improved methods of distribution to reduce cost and to increase profits. Sales management today is the most important function in a commercial and business enterprise.
Do ETL : Extract-Transform-Load some Amazon dataset and find Sales-trend -> month wise , year wise , yearly month wise. 
Find key metrics and factors and show the meaningful relationships between attributes.

## Tools Used
`Power BI`,
`Microsoft Excel`,
`MySql`

## Analysis List
1. Sales Analysis
> This analysis aims to answer the question of the sales trends of product. The result of this can help use measure the effectiveness of each sales strategy the business applies and what modificatoins are needed to gain more sales.

2. Product Analysis
> Conduct analysis on the data to understand the different product lines, the products lines performing best and the product lines that need to be improved.

3. Customer Analysis
> This analysis aims to uncover the different customers segments, purchase trends and the profitability of each customer segment.

## Approach Used
1. Data Wrangling:
> This is the first step where inspection of data is done to make sure **NULL** values and missing values are detected and data replacement methods are used to replace, missing or **NULL** values.
> 1. Build a database
> 2. Create table and insert the data.
> 3. Select columns with null values in them. There are no null values in our database as in creating the tables, we set **NOT NULL** for each field, hence null values are filtered out.

2. Feature Engineering:
>This will help use generate some new columns from existing ones. Here I have created a calendar table & then generate some new columns from them.
>1. Add a new column named `year` that contains the extracted year on which the given transaction took place (2012, 2013, 2014, 2015). Help to determine which year has the most sales and profit.
>2. Add a new column named `month_name` that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar..). Help to determine which month of the year has the most sales and profit.
> 3. Add a new column named `day_name` that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help answer the question on which week of the day each branch is busiest.

3. Exploratory Data Analysis (EDA):
>Exploratory data analysis is done to answer the listed questions and aims of this project.

## Dashboard
* Watch the complete Dashboard video [Video Link](https://www.youtube.com/watch?v=AXy5okhiFeY&t=1s)
* Check out the dashboard [Dashboard](https://www.novypro.com/profile_about/sandeep-borase?Popup=memberProject&Data=1714909286862x790781689201478600
)

## Documentation
* [High Level Documnet](https://github.com/Sandeepborse77/Ineuron-Internship-Amazon-Sales-Project/blob/main/HLD%20Document.pdf)
* [Low Level Document](https://github.com/Sandeepborse77/Ineuron-Internship-Amazon-Sales-Project/blob/main/LLD%20Document.pdf)
* [Architecture](https://github.com/Sandeepborse77/Ineuron-Internship-Amazon-Sales-Project/blob/main/Architecture.pdf)
* [Wireframe](https://github.com/Sandeepborse77/Ineuron-Internship-Amazon-Sales-Project/blob/main/Wireframe.pdf)
* [Report](https://github.com/Sandeepborse77/Ineuron-Internship-Amazon-Sales-Project/blob/main/Detailed%20Project%20Report.pdf)




