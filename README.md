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

As a data analyst,i will examine the data provided and use the appropriate visualization tools to represent my insights and make a presentation to the management team to show to the public and make vital decisions in the area they are lacking.

**Solution**

I analyse the available data from a performance analysis perspective and also from diversity perspective in all the regions. In here management and stakeholders could choose make insightful decisions by evaluating the following;

Total salary of all employees
Gender distribution in all departments and regions
Gender pay gap by departments and regions
Salary (Bonus inclusive) distribution by department
Salary category by gender and regions.
Salary distribution of employees grouped by a band of $10,000

![image](https://github.com/user-attachments/assets/c2ec8aaa-6316-44f1-b260-99d9e329f641)

![image](https://github.com/user-attachments/assets/d14a9459-62fe-41a0-b2fb-8b57a677db08)

![image](https://github.com/user-attachments/assets/87c77103-2a3d-4cbe-aeab-688e6d374437)

![image](https://github.com/user-attachments/assets/4d853085-8d3e-47e2-a6ce-6350f054a460)

“The aim of this project is provide recommendation by analysing the gender distribution worldwide and also answer key questions that focus on gender pay differences.”

In order to identify key areas that could affect the image of Palmoria, there is a need to leverage on business intelligence applications. For this i use microsoft power BI for my analysis and visualisation.

**DATA UNDERSTANDING**

Two dataset was provided for me, which was inform of csv(comma seperated values) while the other was in microsoft excel . The csv dataset is "emp_data” while the excel file and “Bonus Rules”.

The emp_data workbook consist of the names of the employees, gender, department, salary, location and the rating. The second workbook includes the department and their ratings(very poor, poor, average, good, very good).

An overview of the datasets are shown below;

![image](https://github.com/user-attachments/assets/4cb6f145-1f8c-4968-b929-92505d671513)

![image](https://github.com/user-attachments/assets/0b702727-748e-4e40-a2d3-c0b95cc3a78b)

![image](https://github.com/user-attachments/assets/4865ad8b-3c71-4ffe-a6a5-4575217c6fe4)

**Data Preparation in Power Query**

Power query is used to transform and clean data for analysis. Firstly, i explored the data composition so as to know if the data cleaning is needed. By doing this i leveraged on the data profiling distributor feature provided by BI. I checked for any structural and observation errors in each given column and how many unique values there where, I found no errors, I also ensured the data type was in the right format for each column as it is imperative to be able to analyze effectively and generate accurate result.

Since the “emp_data” is a csv file i had to do the following cleaning which was required before finally loading:

Use the first rows as headers
Replace the empty gender with Others as required by Palmoria.
filter out the null rows in the departmental column.
Filter out the empty rows in the salary column.

![image](https://github.com/user-attachments/assets/856a28ce-c6f4-4375-b7c3-9e0181ba369c)

![image](https://github.com/user-attachments/assets/81364a67-f239-4f89-80e9-a404688e23cb)

![image](https://github.com/user-attachments/assets/23849747-522f-4a27-ace6-d233cbcf46c7)



**DATA MODELLING**

The last step which i took before analyzing the data was to create a relationship between the tables i created in the previous step. This will allow me to drill and slice through the data for efffective and visualization analysis.

PowerBI is optimized to work with data models, data models are important as they help organize tables of data based on groupings or relationships to reduce redundancy and optimize efficiency.

In creating a relationship between the various tables which i already created I had make sure the tables which had primary keys where uniquely identifiable (Removing duplicates with the primary table). Rating and department were primary tables. Eitherway the DSF_emp_data table could be use to connect to both rating and department table or could be use single handedly when preparing analysis. I then close and apply all data preparation applied steps for analysis in the power BI desktop.

In creating the relationship, Firstly i deleted the relationship already created by power BI and I connected both tables using the model icon near the dashboard. I connected the primary keys to the tables were they share the same identifier.
The approach

I followed the CRISP-DM approach in modelling the solution for the challenge facing Palmoria.

![image](https://github.com/user-attachments/assets/108488cd-eec8-49f8-8308-aa78b4d59a4c)


To enable the management of Palmoria make quality decision as regards gender distribution, insights on ratings and gender pay gap, i summarised below important insights to take note which can cause data driven decisions in future.

The total employees in Palmoria group is 946(male 465, female 441 and unspecified 40), while the diversity ratio is 49% worldwide.
The total salary of employees worldwide is over 70 million while the average pay of each employee is over 73,000 thousand dollar.
The marketing, engineering and sales department appears to have a negative gender pay gap. Engineering department which has more male than female has the highest pay gap of over 7,505.16 dollar.
Over 654 employees earn below 90,000 dollar in all the regions, while a total number of 292 employees earns 90,000 and above.






