
***HR Analytics Dashboard – Power BI Project***

Project Overview

This HR Analytics dashboard provides a comprehensive view of workforce data to help HR teams make informed, data-driven decisions. It covers key metrics such as employee demographics, performance indicators department-level insights and attrition trends.

Objective
To analyze employee data and uncover trends in attrition, performance, and demographics, enabling HR and leadership to improve employee retention, engagement, and workforce planning.

Dataset Structure

HR_Data_Analysis
COLUMN	DESCRIPTION
Employee ID-	Unique identifier assigned to each employee
StartDate-	Date the employee started at the company
Title-	Job title or designation of the employee
BusinessUnit-	Division or strategic unit of the organization
EmployeeStatus-	Current employment status
EmployeeType-	Type of employment
PayZone-	Geographical or pay bracket classification for payroll
EmployeeClassificationType-	Full Time, Temporary or Part Time
DepartmentType-	Specific department category
Division-	Organizational division employee belongs to
DOB-	Date of birth of the employee
State-	State location of the employee
GenderCode-	Gender of the employee
RaceDesc-	Race or ethnicity description
MaritalDesc-	Marital status of the employee
Performance Score-	Performance evaluation score
Current Employee Rating-	Most recent employee performance rating
Survey Date	-Date when engagement or feedback survey was taken
Engagement Score-	Employee engagement level based on surveys
Satisfaction Score-	Overall job satisfaction score
Work-Life Balance- Score	Work-life balance feedback score
Training Date-	Date the training program was attended
Training Program Name-	Name of the training attended
Training Type-	Category/type of the training program
Training Outcome-	Result or outcome of training
Training Duration(Days)-	Length of training program in days
Training Cost-	Cost associated with the training program
Age-	Employee's age



### 🔹 1. Overview Dashboard
- **Workforce Gender Distribution** – Donut chart of Male vs Female.
- **Yearly Hiring Trend** – Line chart of new joiners.
- **Top KPIs** – Total employees, Active employees, Termination Ratw, Average Rating.

### 🔹 2. Demographics

**Age Group Distribution** –Stacked Column chart.
**Race wise employee Split** – Donut chart.
**Employee distribution by State** – Map chart (State-wise).

### 🔹 3. Performance Analysis
- **Performance Rating Distribution** – Donut chart.
- **Employee Performance analysis by Department ** – Stacked bar.
- **Engagement & Satisfaction Scores** – Donut charts.
- **Top 10 Rated Performers** – Table visual.

### 🔹 4. Departmental Insights
- **Training Success v/s Failure for each Dept.** – Donut chart.
- **Training Success Rate** – KPI cards.
- **Workforce Composition by Department & Gender** – clustered column visuals.

### 🔹 5. Termination Analysis
- **Average Age at Termination** – KPI Card.
- **% Female and % male Terminated** – KPI Card.

- **Top 3 Depts. by Terminations** – Table.
- **Termination Split by Training outcome ** –Column chart.
- **Termination over time** – Line Chart.
- **Termination by Employee Type** – Pie Chart.

## 🧮 DAX Measures Used
Some key calculated measures used:
- `Total Employees`
- `Active Employees`
- `Total Terminated Employees`
- `Termination Rate = Terminated Employees / Total Employees`
- `Training Success Rate = COUNT(Completed + Passed Training) / Department Headcount`
- `Average Rating = AVERAGE(Employee Rating)`
- `% Female Terminated = COUNT(Female & Terminated) / Total Terminated`
- `% Male Terminated = COUNT(Male & Terminated) / Total Terminated`

**Thank You!**

Thank you for taking the time to explore this HR Analytics Dashboard project.  
I hope this dashboard demonstrates how data-driven insights can empower HR decision-making.
