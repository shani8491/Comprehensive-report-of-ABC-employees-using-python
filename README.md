# ABC Company Employee Analysis
This project analyzes a dataset of employees from ABC Company, focusing on team distributions, positions, salary expenditures, and age groups. Key tasks include identifying the predominant age group, determining salary trends, and examining correlations between age and salary. Visualizations are used to present findings.

**Table of Contents**
  1. Project Overview
  2. Preprocessing Steps
  3. Analysis Tasks
  4. Graphical Representations
  5. Insights Gained
  6. Technologies Used
      
**Project Overview**
This project aims to provide a comprehensive analysis of employee data from ABC Company, including team structures, roles, salary distributions, and demographics. The dataset contains 458 rows and 9 columns, and the goal is to provide insights into employee distribution, salary expenditure, and more. Visualizations and summaries are created to present the findings effectively.

**Preprocessing Steps**
Handling Missing Data: The dataset was examined for any missing values or inconsistencies, especially in columns like "Height" and "Salary". Missing values in the "Height" column were replaced with random values between 150 and 180 for consistency.
Data Transformation: Data was categorized into relevant groups, such as "Age Group", to facilitate further analysis. The "Age Group" column was created by binning the "Age" column into predefined ranges.
Consistency Checks: Ensured that salary data was consistent and free from any errors (e.g., outliers or negative values).

**Analysis Tasks**
1. Team Distribution:
Identified the distribution of employees across different teams.
Calculated the percentage split of employees in each team relative to the total number of employees.
2. Segregation by Position:
Grouped employees based on their positions within the company (e.g., Manager, Analyst, Developer).
Provided a breakdown of employee counts per position.
3. Predominant Age Group:
Analyzed the age distribution of employees and identified the predominant age group within the company.
4. Salary Expenditure Analysis:
Calculated the total salary expenditure per team and position.
Identified the team and position with the highest salary expenditure.
5. Correlation Between Age and Salary:
Investigated the correlation between employee age and salary.
Created visualizations to represent this relationship and assess the strength of the correlation.

**Graphical Representations**
For each of the analysis tasks, the following types of visualizations were created:
a) Bar Charts: Used for team distribution and position segregation to clearly show the count and percentage of employees in each category.
b) Pie Charts: Represented the age group distribution and salary expenditure distribution visually.
c) Stacked Bar Charts: Used to show salary expenditures across different teams and positions.
d) Heat map: Used to visually represent the correlation between age and salary.
Each chart was designed to make the insights more accessible and easy to interpret.

**INSIGHTS GAINED FROM THE ANALYSIS**
1. Employee Distribution Across Teams:
•	Insight: Certain teams have a significantly higher proportion of employees. For example, New Orleans Pelicans might constitute 4.148472% of the members, indicating a possible dependency or focus on that team’s operations.
2. Segregation by Position:
•	Insight: Positions such as "PF" or "SG" are predominant, making up the majority of roles, whereas niche positions like "SF" or "C" might be less common.
•	Pattern: A hierarchical structure may be evident, with a smaller proportion of C roles and a larger base of SF positions.
3. Predominant Age Group:
•	Insight: Employees are concentrated in the 26–30 age group, indicating a young workforce, possibly focused on innovation and energy.
•	Pattern: Age groups like 45+ may be underrepresented, suggesting the company might not have many senior professionals or could face challenges in retaining older employees.
4. Team and Position with the Highest Salary Expenditure:
•	Insight: The Los Angeles Lakers and SF Positions might have the highest salary expenditure, reflecting the company’s focus on revenue-driving roles.
•	Trend: Teams or positions critical to strategic goals are compensated more, indicating clear prioritization of resources.
5. Correlation Between Age and Salary:
•	Insight: A weak positive correlation between age and salary suggests that while older employees tend to earn more, the increase isn't significant. This could point to salary structures based on roles rather than tenure.
•	Pattern: The salary for specific positions may plateau after a certain age, reflecting limited growth opportunities within roles.

**Technologies Used**
Python: Used for data preprocessing, analysis, and visualization.
Pandas: For data manipulation and analysis.
Matplotlib & Seaborn: For creating visualizations.
Jupyter Notebook: For an interactive analysis environment.
