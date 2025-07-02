# DSA-DATA ANALYTICS PROJECT
Capstone Project — Employee Analysis for Palmoria Group.
Target Audience: Management- Stakeholders, Employees & Public.

Tools used: Microsoft Power BI.

**Introduction**

Over the years manufacturing industry in Nigeria have enjoyed efficient rich workforce that are diverse in various factors that could affect their ESG(environmental, social and governance)rating.
Furthermore, this industry is one which is very competitive in every aspect as the management of each company must make decisions that will encourage opportunities within. Hence it is important that each business decision taken must be as a results of insights generated from data analytics.

The last two years has been plagued with pandemic, so it is important for businesses to make data driven decisions. Insights from extensive data analytics can help improve payroll management, support diversity and inclusion objectives, understand key drivers that help increase engagement, examine benefit of cost effectiveness. In summary we can say data analytics act as a catalyst in every area of human capital management as it helps provide seemless operational process, efficient compensation and benefit, performance management and engagement.

In this case study, we are saddled with the responsibility of analysing Palmoria employees data from a various perspective that can affect the image of the company.The ambition to scale the business to other regions and overseas rest on our findings.

**The challenge**

Employee Distribution and Performance Measurement

The Palmoria group is facing issues bordering on gender inequality in its 3 regions. To make matter worse, the media has recently published in the news with the headline “Palmoria, the Manufacturing Patriarchy”. This doesn’t look good for the stakeholders as they look to move the business to other regions in the future.

As a hr data analyst,i will examine the data provided and use the appropriate visualization tools to represent my insights and make a presentation to the management team to show to the public and make vital decisions in the area they are lacking.

Solution

I analyse the available data from a performance analysis perspective and also from diversity perspective in all the regions. In here management and stakeholders could choose make insightful decisions by evaluating the following;

Total salary of all employees
Gender distribution in all departments and regions
Gender pay gap by departments and regions
Salary (Bonus inclusive) distribution by department
Salary category by gender and regions.
Salary distribution of employees grouped by a band of $10,000

![image](https://github.com/user-attachments/assets/c2ec8aaa-6316-44f1-b260-99d9e329f641)

![image](https://github.com/user-attachments/assets/87c77103-2a3d-4cbe-aeab-688e6d374437)

![image](https://github.com/user-attachments/assets/4d853085-8d3e-47e2-a6ce-6350f054a460)

“The aim of this project is provide recommendation by analysing the gender distribution worldwide and also answer key questions that focus on gender pay differences.”

In order to identify key areas that could affect the image of Palmoria, there is a need to leverage on business intelligence applications. For this i use microsoft power BI for my analysis and visualisation.

DATA UNDERSTANDING

Two dataset was provided for me, which was inform of csv(comma seperated values) while the other was in microsoft excel . The csv dataset is "emp_data” while the excel file and “Bonus Rules”.

The emp_data workbook consist of the names of the employees, gender, department, salary, location and the rating. The second workbook includes the department and their ratings(very poor, poor, average, good, very good).

An overview of the datasets are shown below;

![image](https://github.com/user-attachments/assets/4cb6f145-1f8c-4968-b929-92505d671513)

![image](https://github.com/user-attachments/assets/0b702727-748e-4e40-a2d3-c0b95cc3a78b)

![image](https://github.com/user-attachments/assets/4865ad8b-3c71-4ffe-a6a5-4575217c6fe4)

Data Preparation in data Query

Power query is used to transform and clean data for analysis. Firstly, i explored the data composition so as to know if the data cleaning is needed. By doing this i leveraged on the data profiling distributor feature provided by BI. I checked for any structural and observation errors in each given column and how many unique values there where, I found no errors, I also ensured the data type was in the right format for each column as it is imperative to be able to analyze effectively and generate accurate result.

Since the “emp_data” is a csv file i had to do the following cleaning which was required before finally loading:

Use the first rows as headers
Replace the empty gender with Others as required by Palmoria.
filter out the null rows in the departmental column.
Filter out the empty rows in the salary column.

The approach

I followed the CRISP-DM approach in modelling the solution for the challenge facing Palmoria.

![image](https://github.com/user-attachments/assets/108488cd-eec8-49f8-8308-aa78b4d59a4c)








