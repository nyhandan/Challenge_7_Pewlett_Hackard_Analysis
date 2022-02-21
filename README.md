# Challenge 7: Pewlett-Hackard Employee Database Analysis
Dan Nyhan 1st Attempt

## Purpose
The purpopse of this analysis is to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. We also wrote a report that helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.

In Devlierable 1, we have created a Retirement Titles table that holds all the titles of employees who were born between January 1, 1952 and December 31, 1955. Some employees may have multiple titles in the database—for example, due to promotions, so we created a table that contains the most recent title of each employee. We also created a table that has the number of retirement-age employees by most recent job title. Finally, because we want to include only current employees in our analysis, we excluded those employees who have already left the company.

In Deliverable 2, we referenced the ERD I created in the ETL module to create a mentorship-eligibility table that shows the number of employees eligible for the mentorship program.

## Results
   - The "retirment titles" file shows all the employees that are about to retire. There is a data point for each job title held by each employee.                         Preview:  
     ![Retirement_titles](https://github.com/nyhandan/Challenge_7_Pewlett_Hackard_Analysis/blob/main/Retirement_image.png)
  
   - The "unique titles" file shows all the employees that are about to retire, but it has a data point for each employee (it combines the job titles of each      employee). 
      Preview: 
     ![Unique_titles](https://github.com/nyhandan/Challenge_7_Pewlett_Hackard_Analysis/blob/main/Unique_image.png)
  
  - The "retiring titles" file counts the amount of employees retiring, categorized by job title. 
      Preview: 
     ![Retiring Titles](https://github.com/nyhandan/Challenge_7_Pewlett_Hackard_Analysis/blob/main/Retiring_titles.csv)
     
  - The "mentorship eligibility" file lists the employees who should start the mentorship program.
      Preview: 
     ![mentorship eligibility](https://github.com/nyhandan/Challenge_7_Pewlett_Hackard_Analysis/blob/main/Mentorship_image.png)
 
 ## Summary
  - As the "silver tsunami" takes effect, [90,398](https://github.com/nyhandan/Challenge_7_Pewlett_Hackard_Analysis/blob/main/Retiring_titles.csv) roles will need   to be filled

   - No, there is a huge shortage of eligible mentors. There are only 1549 people who are eligible (found using this code when opening up the csv file in Excel:  =COUNT(A2:A1550)).
