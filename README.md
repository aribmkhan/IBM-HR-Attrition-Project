# IBM HR Attrition Project
## Project Background
IMB, founded in 1911, is known for its work in computer hardware, software, and IT services.

Due to its standing as the largest industrial research organization in the world with over 282,200 employees (as of December 2023), attrition is an ever-present problem that, if left unmanaged, has serious consequences pertaining to workplace and employee health, company finances, and company work-efficieny.

This project analyzes IBM employee data and uncovers critial insights that will result in decreased attrition in the future.

Insights and recommentdations are provided in the following key areas:
1. **Job Satisfaction:** Satisfaction levels pertaining to the individual's job and the work environment.
2. **Stock Options:** The number of stock options available to full-time employees.
3. **Distance from Workplace:** How the distance between the workplace and home impacts attrition.
4. **Job History:** Considering the likelihood of attrition considering the number of jobs held prior to beginning work at IBM.

## Executive Summary
### Key Findings
Ex-employees...
1. Reported lower job satisfaction than current employees.
2. Reported lower environemntal satisfaction than current employees.
4. Lived further from the workplace.
5. Had fewer stock options.
6. Worked a greater number of jobs prior to their position within IBM.
Below is the Attrition Dashboard created for HR management.

The entire dashboard can be downloaded <a href="https://github.com/aribmkhan/IBM-HR-Attrition-Project/blob/main/Employee%20Attrition%20Dashboard.pbix" target="_blank">here</a>.

<img width="1400" alt="Attrition Dashboard" src="https://github.com/user-attachments/assets/dca338f2-f553-4d5a-9baa-c15a58a42571">

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
## Data Exploration
### KPI Calculations
_Calculated using the count of current employees and ex-employees._

**Total Employees** = 1233

**Total Attrition** = 237

**Attrition Rate** = 16.12%

**Retention Rate** = 81.97%
### Satisfaction Scores
The first attributes to visualize were "Job Satisfaction" and "Environmental Satisfaction, segmented by the "Attrition" Dimension. This would allow us to see if there was a difference in satisfaction scores between current and ex-employees.

#### Average Job Satisfaction per Role

On average, the job satisfaction scores were lower for the employees that ended up leaving the company.

<img width="1400" alt="Average Job Satisfaction per Role" src="https://github.com/user-attachments/assets/b92a27b6-b7e9-46e0-8c77-4d72ec4a899f">

#### Average Environmental Satisfaction per Role

On average, the environmental satisfaction scores were lower for individuals that ended up leaving the company, with the exception of the Research Director role.

<img width="1400" alt="Average Environmental Satisfaction per Job Role" src="https://github.com/user-attachments/assets/1a85a7ac-278b-4e05-b7a9-99fec2267cc4">

### Further Disparities Between Current and Ex-Employees
The rest of the visualizations were conducted by keeping Rob Role as the independent variable and implementing different dependent variables. Each visualization was segmented via the Attrition dimension so we could see where the disparities lie between current and ex-employees.

#### Average Distance from Home per Job Role

On average, employees that quit lived farther from home than those that did not.

<img width="1400" alt="Average Distance from Home per Job Role" src="https://github.com/user-attachments/assets/b241e642-753a-4d71-b0c3-0da887616bf5">

#### Jobs Held History

Employees that committed attrition also held more jobs on average prior to their career at IBM.

<img width="1400" alt="Jobs Held History" src="https://github.com/user-attachments/assets/7f513973-8179-4946-a112-9734c7cb29ea">

#### Average Stock Options per Job Role

On average, employees that quit had fewer stock options than the employees that did not.

<img width="1400" alt="Average Stock Options per Job Role" src="https://github.com/user-attachments/assets/5cfb0c32-595d-4e4b-b5a2-b57de395861a">

### Answer -- What are the warning signs that attrition will occur?
1. Reported job satisfaction and work environment satisfaction scores are low.
2. Employee lives far from place of work.
3. Employee held a high number of jobs prior to their current job at IBM.
4. Lack of stock options.

### Answer -- What can be done to lower the chance of attrition?
1. Survey employees to discover what it would take to increase their job satisfaction.
2. Survey employees to determine what changes can be made to the work environemnt in order to increase their environmental satisfaction.
3. Communicate with upper-manageemnt in order to formulate a travel plan that reduces the commute costs, or allow for remote work.
4. Provide stock options to more employees.
### Recommendations
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
