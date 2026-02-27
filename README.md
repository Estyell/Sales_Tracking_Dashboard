# Nairobi VII Sales Tracking dashboard
## Business Context
This project was designed for one branch of a major insurance and investment company in Kenya, that sells different insurance, savings, investment, and corporate business products.
The branch has significant amounts of data on its sales that has been underutilized, and leadership lacks insight into branch financial advisors' sales performance. This project thoroughly analyzes and synthesizes this data in order to uncover critical insights that will improve the branch’s sales revenue and effectively monitor financial advisor participation.

## Project Objective
The Nairobi VII branch manager would like to be able to monitor the sales of the different financial advisors within the branch and across the different lines of products. The aim is to easily identify any struggling financial advisor for better management.

## Business Problem
Sales data exists, but is not structured for proper performance monitoring.

## Stakeholders
Branch Manager </br>
Branch Unit managers

## Business Requirements
To increase the sales performance and increase value by X%. Having a better understanding of the participation of different financial advisors and increase financial advisor contribution to revenue to a constant Y%.

### Functional Requirements
The solution should track the general sales performance of the branch over time by unit branch, financial advisor, and product line.</br>
The solution should allow the user to apply preferred filters depending on which sales question they want to answer; by branch unit, by financial advisor, by product</br>
The solution should be able to show the financial advisor participation into the sales revenue i.e how many unique sales contributed to the sales revenue</br>
The solution should also allow the user to drill down on a specific financial advisor sales performance and participation over time</br>
The solution should identify underperforming Financial advisors, branch units, and product line.

### Non-Functional Requirements
The users will have access to the dashboard but not the dataset feeding the dashboards.</br>
There will be one data manager who updates the dataset with new sales records.</br>
The dataset is updated with new records every Friday of the week</br>
The dashboard visuals update automatically.


## Dataset Used
### Source
The data used was a mock sales dataset that was generated with parameters that matched the client’s sales scenario.

- <a href="https://github.com/Estyell/Sales_Tracking_Dashboard/blob/main/DemoDashboard_Data.xlsx">Dataset</a>

### Cleaning & Transformations
#### Key Assumptions
Each row represents one sales transaction

#### Process
•	Verify the dataset to ensure there is no missing data
•	Ensure the data is consistent and clean with respect to data types, data format, and data values used.

#### Data Structure
Dropdowns are introduced on Advisor_Name, Product_Name to ensure data integrity
A transaction ID column is introduced to ensure uniqueness in each sales record

### Tools Used
Google sheets and Looker studio


## KPI Questions
•	What is the performance of each financial advisor?</br>
•	What is the participation of each financial advisor?</br>
•	What is the performance of each branch unit?</br>
•	What is the participation of each branch unit?</br>
•	How are the different product lines distributed?</br>
•	How is the performance of the financial advisors over time?</br>

### KPIs
- Sales Revenue
- Sales growth with previous period - tracks sales performance
- Average sales amount - indicated sales value/ performance of branch
- Average sales count - indicates financial advisor participation
- Top sale - showcases top financial advisor and product
- Sales performance unitwise - which branch is carrying the branch?
- Sales performance productwise - what is the product distribution in relation to sales revenue


## Dashboard Created
-Dashoard Interaction	<a href="https://github.com/Estyell/Sales_Tracking_Dashboard/blob/main/Dashboard.png">View_Dashboard</a>


## Dashboard
<img width="652" height="539" alt="Dashboard" src="https://github.com/user-attachments/assets/2cd021fb-07cb-4ad7-82ac-9420c0d822ef" />
