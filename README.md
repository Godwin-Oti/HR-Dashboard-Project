# Advanced-HR-Dashboard
## Project Overview
This project involves the creation of a realistic Human Resources (HR) dataset and an interactive HR dashboard for a German workforce. The dataset, generated with Faker, a Python library, includes diverse employee profiles with attributes like hire dates, job titles, salaries, and more. The dashboard, built using Tableau, provides insightful visualizations and analysis of HR data to enhance business intelligence and decision-making.

## Project Features
## Data Generation
- Employee Profiles: Generated 8,950 unique records with realistic details.
- Custom Probabilities: Applied tailored probabilities for attributes such as gender, hire date, job title, and termination date.
- Salary Adjustments: Computed salaries considering factors like gender, education level, and age.
- Data Consistency: Ensured logical relationships between data points (e.g., hire date and birthdate).
## Dashboard
- Interactive Visualizations: Developed an HR dashboard using Tableau to visualize employee data and trends.
- Data Insights: Enhanced BI skills by creating interactive charts, filters, and reports for effective data analysis.
- Decision-Making: Provided actionable insights to improve HR processes and strategic decisions.
- [Explore the Dashboard](https://public.tableau.com/app/profile/godwin.oti5506/viz/HRDashboard_17234775444960/HRSummaryDashboard)
## Technologies Used
- Python: For data generation and manipulation using libraries like Pandas, NumPy, and Faker.
- Tableau: For creating interactive dashboards and visualizations.
- Libraries: Faker for generating realistic data, pandas for data manipulation, numpy for numerical operations.
## Getting Started
### Prerequisites
- Python 3.x
- Pandas
- NumPy
- Faker
- Tableau (for dashboard visualization)
### Installation
1. Clone the Repository:
 ```bash
git clone https://github.com/Godwin-Oti/HR-Dashboard-Project
cd hr-dashboard-project
```
3. Install Python Libraries:
```bash
pip install pandas numpy faker
```
5. Run the Data Generation Script:
```bash
python generate_hr_data.py
```
This script generates the HR dataset and saves it as HumanResources_Germany.csv.

4. Import CSV into Tableau:
- Open Tableau.
- Connect to the HumanResources_Germaany.csv file.
- Use Tableau’s features to build and customize the HR dashboard.
## Data Description
- employee_id: Unique identifier for each employee.
- first_name: Employee's first name.
- last_name: Employee's last name.
- gender: Gender of the employee (e.g., Male, Female).
- state: US state where the employee is located.
- city: City within the state where the employee is located.
- hiredate: Date when the employee was hired.
- department: Department where the employee works.
- job_title: Title of the employee's job.
- education_level: Highest education level achieved by the employee.
- salary: Employee's salary.
- performance_rating: Performance rating of the employee.
- overtime: Whether the employee works overtime.
- birthdate: Employee's date of birth.
- termdate: Date when the employee was terminated (if applicable).

## Acknowledgements
Special thanks to Baraa Khatib Salkini for invaluable guidance and mentorship throughout this project.
