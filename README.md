# IBM HR Attrition Project
<img width="876" alt="Employee Attrition Dashboard" src="https://github.com/user-attachments/assets/6afb48ea-418f-459e-b0d0-38597175f13d">

## Executive Summary
### Project Goal
The goal of this analysis was to provide the HR department with recommendations on how to decrease employee attrition.
### Key Findings
Ex-employees...
1. Reported lower job satisfaction than current employees.
2. Reported lower environemntal satisfaction than current employees.
4. Lived further from the workplace.
5. Had fewer stock options.
6. Worked a greater number of jobs prior to their position within IBM.
### Reccomendations
1. Survey employees to discover what it would take to increase their job satisfaction.
2. Survey employees to determine what changes can be made to the work environemnt in order to increase their environmental satisfaction.
3. Communicate with upper-manageemnt in order to formulate a travel plan that reduces the commute costs, or allow for remote work.
4. Provide stock options to more employees.
### Conclusion
Employee attrition can be decreased by bettering job and environemtnal satisfaction scores. Employees should also be provided with the means to easily commute to the workplace, or be allowed to work remotely from home. Finally, stock options should be offered to more employees to incentivize company loyalty.
### Call to Action
1. Create surveys to assess what would make employees more satisfied with their jobs and the workplace environment.
2. Create a plan with upper management to lessen costs of commuting, or allow for remote work.
3. Formulate a plan with finance department management pertaining to employee stock options.
## Analysis
### Requirements Gathering
* Stakeholders - HR Division, HR Management
* Need 1 - Determine why attrition occurs
* Need 2 - Determine how attrition can be decreased moving forwards
* Deliverables - Analytical Report (this document), Attrition Dashboard
### Project Overview
This project utilizes employee attrition data, satisfaction scores, and other relevant data in order to determine the reasons why attrition within the IBM workplace occurs. This information is then used to provide recommendations on where stakeholders (HR) should focus in order to decrease the likelihood of attrition in the future.
### North Star KPIs -- HR Division, HR Management
1. Total Employees
2. Total Attrition
3. Attrition Rate
4. Retention Rate
### Key Questions
_1. What are the warning signs that attrition will occur?_

_2. What can be done to lower the chance of attrition?_
### Data Exploration
### KPI Calculations
_Calculated using the count of current employees and ex-employees._
**Total Employees** = 1233
**Total Attrition** = 237
**Attrition Rate** = 16.12%
**Retention Rate** = 81.97%
#### Satisfaction Scores
The first thing to look at were the "Job Satisfaction" and "Environmental Satisfaction" attributes. These columns contained scores given by employees within a questionare to determine their satisfaction pertaining to their jobs and the work environment. The visualizations for these scores were segmented via the "Job Role" and "Attrition" dimensions.

<img width="876" alt="Average Job Satisfaction per Role" src="https://github.com/user-attachments/assets/ad394aab-9be1-4777-824b-a04bd3200e08">

We see that, on average, the job satisfaction scores were lower for the employees that ended up leaving the company.

<img width="876" alt="Average Environmental Satisfaction per Job Role" src="https://github.com/user-attachments/assets/d0b1f501-fdf2-4d76-a7f3-4a797970453f">

We also see that, on average, the environmental satisfaction scores were lower for individuals that ended up leaving the company, with the exception of the Research Director role.
#### Further Disparities Between Current and Ex-Employees
The rest of the visualizations were conducted by keeping Rob Role as the independent variable and implementing different dependent variables. Each visualization was segmented via the Attrition dimension so we could see where the disparities lie between current and ex-employees.

<img width="876" alt="Average Distance from Home per Job Role" src="https://github.com/user-attachments/assets/8e5815c7-ee75-4543-b799-2f9a307e1ab6">

On average, employees that quit lived farther from home than those that did not.

<img width="1465" alt="Jobs Held History" src="https://github.com/user-attachments/assets/7f513973-8179-4946-a112-9734c7cb29ea">

Employees that committed attrition also held more jobs on average prior to their career at IBM.

<img width="1466" alt="Average Stock Options per Job Role" src="https://github.com/user-attachments/assets/5cfb0c32-595d-4e4b-b5a2-b57de395861a">

Finally, we see that, on average, employees that quit had fewer stock options than the employees that did not.

### Answer -- What are the warning signs that attrition will occur?
