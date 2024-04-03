
# HR Data Analytics Power BI Report

## Project Description:
This Power BI report provides comprehensive analysis of the employees in a company. I made this dashboard trying to help the stakeholder to make the right decisions relating to the employees.

## How to Use:
- Download the report file (HR project.pbix).
- Open it using Power BI Desktop.
- Explore the visualizations and charts to analyze employees data.
- Interact with the charts to get the specific information you want.
- you can also download the raw data if you want to show the data before processing from the data files ( HR Analytics Data.csv & HR employee data.csv)

## Requirements:
- Power BI Desktop to open the report file (can be downloaded for free from the Power BI website).

## Steps i followed in this report :
- step 1 : I loaded the data into Power Query editor to transform the data to improve the quality of it.
These tranformations are the followings:

(1) splitting the columns by delimiter (Tap delimiter).

(2)Changing data types of some columns.

(3) Promoted headers ( use first row as header).

(4) Add som conditional columns that help me getting the insights. 

These Condiotional columns are >> 

_ "Reach retirement age" if the employee's age is greater than or equal 60 then "Yes" and else "No".

_"Distance between company and home" >> if the Distance from home greater than or equal 20 then "Far" else if this distance is greater than or equal " Close" else "Very close".

_"Experience" >>   if TotalWorkingYears is less than or equal 1 then "No expeience" else if the years is less than or equal 5 then "Mid experienced" else if  the years is less than or equal 20 then "Highly experienced" else " Top experienced".

_ "Retrenchment " >> if YearsAtCompany is greater than or equal 18 then "Yes" else "No"

_"Promotion" >> if YearsSinceLastPromotion is greater thanor equal 10 the " Need to promotion" else then " No Need to promotion"

_ "Experience_level" >> if JobLevel = 1 then "Junior" else if = 2 then "Senior" else if then = 3 then "Team leader" else if = 4 then "Project manager" else then " Manager"

_"Performance" >> PerformanceRating = 3 then "Median" else then "High"

_"Statisfaction(Job)" >> if JobSatisfaction is less than or equal 2 then "Low" else if = 3 then "Median" else then "High"

(5) Inserting Merged columns and these columns are : 

_"Level of job" which resulted from merging columns "JobLevel" with word "level" 

_"Num of Ex companies" which resulted from merging columns "NumCompaniesWorked" with word "companies"

- step 2 : apply these the transformations on the data and load the data 

- The dashboard 
I divided it into 6 pages and each page showing a specific information . I added a page navigator in all pages to move between the Pages easily " by Click on the page in the navigator with clicking ctrl".


_ page 1 " General" :
showing some general inforamtion lile the total num of employees , the num of males , num of females , num of employees which need to promotion or don't need,the num of employees who will be retrenched or will not be retrenched and the num of employees who work over time or not.
![Screenshot 2024-04-03 152722](https://github.com/Ahmedhosny18/HR-analytics-data/assets/165747704/5d557a99-73df-4912-b29a-b090f9894d1c)

_ page 2 "Details" : showing detailed informations about promoted and not promoted employees and the employees who will be retrencehed and who will not be retrencehd.
![Screenshot 2024-04-03 152752](https://github.com/Ahmedhosny18/HR-analytics-data/assets/165747704/22d641d9-6350-4424-8c42-2e3f99d0ff79)

_page 3 "Service benefits " : showing the employees who need to promotion but they will be retrencehed so they deserve the huge end of service bonus.
![Screenshot 2024-04-03 152815](https://github.com/Ahmedhosny18/HR-analytics-data/assets/165747704/a881c315-1582-4bac-bfad-e5427c934dd9)

_page 4 "Details in departements" : showing detailed informations about promoted and not promoted employees and the employees who will be retrencehed and who will not be retrencehd in each departement.
![Screenshot 2024-04-03 152834](https://github.com/Ahmedhosny18/HR-analytics-data/assets/165747704/755a155b-e6e4-428d-ad2d-063b2a67317e)

_page 5 "Salaries" : showing the top 10 employees with salaries in each department.
![Screenshot 2024-04-03 152900](https://github.com/Ahmedhosny18/HR-analytics-data/assets/165747704/81a9eeab-db5e-4648-a971-443590672207)

page 6 "Performance & Statisfaction" : showing the num of employees in each performance rating and in each job satisfaction rating. 
![Screenshot 2024-04-03 152918](https://github.com/Ahmedhosny18/HR-analytics-data/assets/165747704/3d87a6d1-6f30-4955-9952-dcc290438bda)







## Contribution:
We welcome contributions from other developers. You can open a pull request to submit improvements or fixes to the report.

## Contact:
If you have any questions or inquiries, please contact us via email at ahmed123hosny4@gmail.com.

