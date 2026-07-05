# HR-Capstone-Assignment.
Given by IOTBTECH.

Data Cleaning 
- Highlighted all and clicked remove duplicates
- Changed the format of each cells accordingly eg, for Salary Cell, it was formatted to Currency.
- Some Cells had missing values, where it was text, I put unknown and where it was a numerical missing data, I found the mean and placed it there. Find and Replace was useful for this
- Using the PROPER formula, the Employment Status was corrected to the proper format.
- Using VLOOKUP, I was able to trace the department code to the department.
- Using nested IF function,I was able to get the performance band.
- After getting the Performance Band, I used VLOOKUP to get the bonus percentage which enabled me to be able to calculate the Eligible Bonus Amount by multiplication with the Salary.
-The Full Name was calculated with   the ampersand method. =B2&" "&C2.
-To get the year of service, I had to use Today() to get the date of today after which I used =INT(YearFrac to calculate it. 

Analysis 

With the aid   of PivotTable, I was able to;
Analyse the total number of employees in each department and the average salary collected.
Analyse the percentage of Active Employees, Employees who left and Employees who resigned.
Analyse the Total Eligible Bonus Amouunt based on Performance Band.

Dashboard

<img width="1831" height="586" alt="image" src="https://github.com/user-attachments/assets/116ad076-b199-4506-af87-c54cda12f0ca" />
