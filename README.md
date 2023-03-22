<h1>POWER-BI - HR Data Analytics</h1>


<h2>Description</h2>
The problem we will be working on is analysing company's HR data to provide HR team with custom analytics and readly usable reports for furhter analysis. We will be using dataset from a company calles "Atlas Labs .

Defining HR Analytics <br />
HR analytics (also known as people analytics) is the collection and application of talent data to improve critical talent and business outcomes. HR analytics leaders enable HR leaders to develop data-driven insights to inform talent decisions, improve workforce processes and promote positive employee experience.(Gartner)
<br />


<h2>Language / Technolgies Used</h2>

- <b>PowerBI Desktop</b> 
- <b>DAX Language</b>
- <b>Power Query</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)


<h2>Project Scope:</h2>
This project is primarily focusing on the steps of the report development process that include: <br/>
1.	Requirement gathering <br/>
2.	Connecting to data sources <br/>
3.	Transforming data according to business requirements <br/>
4.	Building data model <br/>
5.	Creating DAX measure that help in analyzing our data <br/>


<h2>Project Steps:</h2>
1.Data is loaded to PowerBI with one fact table and 4 other dimension tables 
 <br/>
 <br/>
<p align="center">
<img src="https://i.ibb.co/vmDW3ym/1.jpg" height="50%" width="20%" alt="Analysing Customer Churn"/>
<br />
<br />
<p align="left">
2.	To analyze data chronologically, a new calculated time dimension table is created using DAX code with “Calendar” function 
 <br/>
 <br/>
<p align="center">
<img src="https://i.ibb.co/jGFLCJV/2.jpg" height="80%" width="80%" alt="Analysing Customer Churn"/>
<br />
<br />
<p align="left">
3.	After we have managed to load the data sources from which the analysis will be carried over, the data model is established with tables relations according to the snowflake schema illustrated here   
 <br/>
 <br/>
<p align="center">
<img src="https://i.ibb.co/jfF3rxW/3.jpg" height="80%" width="80%" alt="Analysing Customer Churn"/>
<br />
<br />
<p align="left">
4.	Next, some exploratory analysis is done to check the number of employees (Active, In-active) to find out the company attrition rate    
<br/>
<br/>
<p align="center">
<img src="https://i.ibb.co/k6wYnJC/4.jpg" height="80%" width="80%" alt="Analysing Customer Churn"/>
<br />
<br />
 <p align="left">
5.	The following visuals are created to overview the company’s hiring trend with more emphasis on active employees regarding their departments and job roles  
<br/>
<br/>
<p align="center">
<img src="https://i.ibb.co/xSB0g9h/5.jpg" height="80%" width="80%" alt="Analysing Customer Churn"/>
<br />
<br />
 <p align="left">
6.	In the following steps, we will focus more on diversity and inclusion metrics <br/>
•	employee’s distribution according to their age category and gender <br/>
•	further employee information regarding marital status and ethnicity   
<br/>
<br/>
<p align="center">
<img src="https://i.ibb.co/h2KQpLV/6.jpg" height="80%" width="80%" alt="Analysing Customer Churn"/>
<br/>
It’s clearly notices that White ethnicity group average salary is far higher than other ethnicity groups 
<br />
<br />
 <p align="left">
7.	After examining employees’ diversity, now we will examine an individual employee’s yearly performance  <br/>
•	DAX measures were calculated to determine employees last performance rating date and the next performance rating due date 
<br/>
<br/>
<p align="center">
<img src="https://i.ibb.co/NTrj4LR/7.jpg" height="80%" width="80%" alt="Analysing Customer Churn"/>
<br />
<p align="left">
 •	Next, to complete our performance tracker dashboard, measures for satisfaction levels and rating progress over the years by individual employee 
<br/>
<br/>
<p align="center">
<img src="https://i.ibb.co/6FjXmGb/8.jpg" height="80%" width="80%" alt="Analysing Customer Churn"/>
<br/>
The example employee previewed in the dashboard show a clear decline in performance from year to year and that can be justified by the deterioration in his levels of satisfaction. In this case, it may be recommended to set a meeting with the employee and create improvement plan 
<br />
<br />
 <p align="left">
8.	The last key insight we are going to look for is to understand employee attrition 
<br/>
<br/>
<p align="center">
<img src="https://i.ibb.co/51PN6nj/9.jpg" height="80%" width="80%" alt="Analysing Customer Churn"/>
<br/>
From the charts we’ve just built, we can see some interesting insights on attrition that can help us prioritize which issues to resolve first. One thing is that frequent travelers have highest attrition rate despite making only 19% of total employees. Accordingly, a review for travel requirement policy and survey employees about feelings around travel frequency should be conducted
<br />
<br />
<p align="left">
9.	Finally, best practices are implemented to our visualizations to make it visually appealing to users who will engage with it on a regularly basis
<br/>
A.	An overview dashboard that summarize the dimensions by which in the analysis was made upon.
<br/>
<br/>
<p align="center">
<img src="https://i.ibb.co/VVxQ5Lm/10-A.jpg" height="80%" width="80%" alt="Analysing Customer Churn"/>
<br />
<br />
<p align="left">
B.	Demographics dashboard
<br/>
<br/>
<p align="center">
<img src="https://i.ibb.co/PZ2tKFL/10-B.jpg" height="80%" width="80%" alt="Analysing Customer Churn"/>
<br />
<br />
<p align="left">
C.	Performance Tracker
<br/>
<br/>
<p align="center">
<img src="https://i.ibb.co/fqdFhLW/10-C.jpg" height="80%" width="80%" alt="Analysing Customer Churn"/>
<br />
<br />
<p align="left">
D.	Attrition   
<br/>
<br/>
<p align="center">
<img src="https://i.ibb.co/M6c0Mgn/10-D.jpg" height="80%" width="80%" alt="Analysing Customer Churn"/>
<br/>
<br/>

 
 
 
 
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
