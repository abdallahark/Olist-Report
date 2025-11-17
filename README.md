# Project Overview 
This project is a business intelligence solution built for Olist dataset (available on Kaggle).
I performed an end-to-end analysis simulating a real-world engagement to provide actionable insights for sales, operations, and marketing leadership.
The final deliverable is a dynamic, multi-page power BI dashboard designed to empower data-driven decision-making.
The Business Problem
Lack of key performance indicators, the real-time revenue tracking for the Sales Head, the diagnosis of the delivery delays and the logistics operations for the operation leads, the unclear profile of customer base for the CMO.
These problems needed a centralized, reliable “single source to truth” to move from reactive problem-solving to proactive strategy.
## The Objective & Role
1.	My objective was to design and build an end-to-end BI solution from scratch.
My role was that of a solo Data Analyst, responsible for the entire project lifecycle.
The key goals were:
 To answer critical business questions related to sales trends, operational efficiency, and customer behavior 
2.	To create a robust and scalable data model capable of handling complex queries 
3.	To develop a suite of KPIs and insightful metrics using DAX
4.	To deliver a clean, intuitive, and interactive power BI report for non-technical stakeholders.




# The Action (process & Technical Skills):
To achieve this, I followed a structured, four-phase analytical process:
1. Data preparation & ETL (Power Query)
    * Connected to 9 separate CSV files using the Power Query Folder connector for scalability.
    * Performed extensive data cleaning: corrected data types, handled nulls strategically, and renamed columns for clarity.
	* Created custom columns to enrich measures for deeper business insights
	* Executed a Merge operation to translate product categories from Portuguese to English, enriching the dataset for an international audience.
    * Documented all transformations with renamed steps in power Query for maintainability.


2. Data Modeling (Star Schema Design):
    * Architected a robust Star Schema to optimize Performance and ensure analytical integrity 
    * Established relationships between fact tables and dimension tables 
    * Created a custom DAX Date table to enable powerful time-intelligence functions.
    * Implemented inactive relationships between the date table and multiple date fields (Order Date, Ship Date, Delivery Date) to enable complex comparative analysis on a single time axis.


3.	DAX Calculations & Analysis 
    * Created over 15 explicit DAX measures in a dedicated Measures table.
    * Foundational Measures: Total Revenue, Total Orders, Average Order Value (AOV)
    * Advanced Time-Intelligence: YOY Revenue Growth using SAMEPERIODLASTYEAR. 
    * Operational KPIs :  On-Time Delivery and  Avg Delivery Delta(Days), which required careful FIlTER context to exclude non-delivered orders.
    * Sophisticated Analytics: Used USERELATIONSHIP create Orders shipped and Orders Delivered measures for operation funnel analysis. Created a complex New vs. Returning Customer Revenue measure to provide deep marketing insights.

4.	Visualization & Report Design (Power BI)
    * Designed a clean, multi-page report with custom theme and intuitive button navigation.
    * Built an Executive summary page with high-level KPIs AND trends for quick business assessment.
    * Created deep-dive pages for Sales and Operations, utilizing visuals like the Matrix with conditional formatting for detailed analysis and a Filled Map with divergent colors to identify geographic bottlenecks
    * Enhanced user experience with advanced features like custom tooltip that reveals trends on hover. 

# Report screenshots
    ![Executive Performence](/images/ExecutivePerformance.png)
 
