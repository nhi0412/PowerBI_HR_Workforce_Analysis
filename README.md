# PowerBI_HR_Workforce_Analysis

## 1. Introduction and Motivation

Employee retention and engagement are critical factors for organizational success. High turnover rates and low satisfaction can negatively impact productivity and profitability. The HR Workforce Dashboard project aims to analyze workforce metrics to gain insights into employee performance, satisfaction, and turnover.

The dataset comprises five key tables:

- **Employee:** Contains demographic information and employment details.
- **Marital Status:** Provides marital status data for each employee.
- **Performance:** Includes performance level.
- **Position:** Details job roles department ID.
- **Department:** Involves the department to which the employee belongs.

These tables are interconnected to provide a holistic view of the workforce, enabling data-driven decision-making for HR management.

## 2. Project Objectives

- Analyze key HR metrics, including total employee, salary expenses, tenure, turnover rates, absence rates, and satisfaction scores.
- Identify trends and patterns in employee engagement and reasons for termination.
- Provide data-driven recommendations to improve employee retention and satisfaction.

## 3. Design Thinking Method

The project followed the design thinking methodology, focusing on delivering a valuable and insightful report for HR managers and executives. The approach included:

### Step 1: Empathize

- **Target Audience:** This report is designed for HR managers and executives who need to make informed decisions about workforce management and improve organizational performance.
- **Purpose of Report:** To provide a clear and comprehensive overview of workforce metrics, identify potential issues such as high turnover rates, and support strategic planning for employee retention and satisfaction.
- **Logic and Data Type:** The dashboard integrates quantitative data from five key tables, offering both numerical insights (e.g., turnover rates, satisfaction scores) and categorical analysis (e.g., department, position, marital status).
- **Data Cleaning:** Before analysis, ensure that the data is accurate and consistent by addressing any missing values, correcting inconsistencies, and removing duplicates. This step guarantees that the insights provided are based on reliable, high-quality data, enabling better decision-making.

### Step 2: Define

- Modeling tables and establishing key objectives, such as identifying high-risk turnover departments, analyzing satisfaction scores, and evaluating performance metrics.
- Specify the need to visualize data from five interconnected tables: Employee, Marital Status, Performance, Position, and Department.

### Step 3: Ideate

- List down the key metrics: turnover rate, satisfaction score, engagement score, tenure, salary expenses, and recruitment sources.
- Split the dashboard layout into distinct sections: KPIs, recruitment sources, termination reasons, workforce metrics, and demographic analysis.
- Choosing Charts:
    - Bar Charts: Used to compare the termination reasons.
    - Pie Chart: Selected to visualize gender distribution.
    - Cards: Highlighted essential metrics like total employees, turnover rate, and engagement scores.
    - Funnel chart: To display different recruitment sources.
- Color Scheme:
    - The dashboard uses a professional blue and white color palette, promoting readability and focus on data insights.
    - Consistent color coding for performance and risk indicators helps to quickly identify areas needing attention.

### Step 4: Prototype

- Create the dashboard with dynamic filters for real-time analysis.
- Implement the designed layout and selected visualization methods.

### Step 5: Review

- Review each part of the report

## 4. Visualization

### Executive summary

<img width="980" alt="Image" src="https://github.com/user-attachments/assets/73480886-797d-4d6a-8e16-a4a6813d2be5" />

The dashboard presents a comprehensive overview of workforce metrics:

- **Top Section:** Displays high-level KPIs such as total employees (311), total salary expenses ($21M), turnover rate (33.44%), average tenure (12.31 years), absence rate (0.23%), satisfaction score (3.89), engagement score (4.11), and average age (46.1).
- **Charts:**
    - **Top Recruitment Sources:** Indeed, LinkedIn, and Google Search are the leading sources of new hires.
    - **Termination Reasons:** The main reasons for employee departures include 'Another Position,' 'Unhappy,' and 'More Money.'
    - **Age Distribution:** The 35-44 age group dominates, while the 25-34 group is the smallest.
    - **Gender Distribution:** A slight female majority, with 56.59% female and 43.41% male.
    - **Turnover Rate by Department:** Production has the highest turnover (39.71%), with Admin Offices and Software Engineering at similar levels (30%).
- **Interactive Metric Overview:**
    - Users can explore workforce metrics by various dimensions such as department, position, gender, citizenship, age, marital status, and ethnicity.

![Screenshot 2025-03-09 at 10.44.19 pm.png](attachment:b39375d2-b479-4c0a-b1f3-789707c45ee0:Screenshot_2025-03-09_at_10.44.19_pm.png)

The Filter Panel on the left side enables filtering by employee name, performance score, and manager name, offering enhanced interactivity and personalized insights.

### Workforce Database

![Screenshot 2025-03-09 at 10.47.39 pm.png](attachment:dcaf4626-c5b4-4feb-98ad-83147566aa8b:Screenshot_2025-03-09_at_10.47.39_pm.png)

This Workforce Database Dashboard is designed to provide clients with a comprehensive view of employee data, allowing them to easily filter, analyze, and compare key performance metrics.

1. Salary Comparison (Bar Chart)
    
    The salary information of employees is displayed in a bar chart, making it simple to compare salaries across departments or specific individuals. The bar chart allows users to quickly identify salary distributions and trends, enabling comparisons of employee compensation in an easily digestible format.
    
2. Absence Rate (Gradient Background)
    
    The absence rate is represented using a gradient color background. The color intensity increases as the absence rate rises, with darker shades indicating higher rates of absence. This visual representation ensures that users can instantly recognize employees with high absence rates, allowing for efficient monitoring and management of attendance.
    
3. Performance Rating (Categorized by Color)
    
    Performance metrics for each employee are categorized by color, enabling users to quickly identify employees who fall within different performance tiers. The color-coded performance categories offer a quick glance at an employee's overall effectiveness, whether they are excelling, meeting expectations, or requiring additional support.
    
4. Retention Risk (Icon Representation)
    
    To visually highlight the retention risk of each employee, an icon system is employed. Icons provide immediate insight into the likelihood of an employee leaving the organization, helping management to take proactive steps in addressing potential turnover. This feature uses intuitive symbols to indicate low, moderate, or high retention risk, offering actionable insights at a glance.
    

![Screenshot 2025-03-09 at 10.57.02 pm.png](attachment:41b5777d-4518-4862-93a2-29d3421687c6:Screenshot_2025-03-09_at_10.57.02_pm.png)

The dashboard includes a powerful filter panel that enables clients to refine the data based on several key parameters: Employee Name, Department, Performance, Manager Name

## 5. Insights

- High turnover rate (33.44%) with the Production department showing the highest turnover at 39.71%.
- Low satisfaction scores correlate with higher turnover rates, highlighting the need for employee engagement initiatives.
- The majority of terminations are due to career change and better opportunities, indicating a need for competitive benefits and growth opportunities.
- Low representation of the 25-34 age group (only 5 out of 311 total employees)
- The recruitment sources mainly came from job channels

## 6. Recommendations

- **Address High Turnover in the Production Department**:
    - Conduct surveys or focus groups to identify pain points in the production department.
    - Review management styles, job expectations, and work conditions to implement targeted improvements.
    - Enhance retention by improving work schedules, job roles, and fostering a supportive culture.
- **Implement Employee Engagement Initiatives**:
    - Introduce regular feedback mechanisms (e.g., surveys, one-on-ones) to address employee concerns.
    - Develop recognition programs to boost morale and celebrate achievements.
    - Offer team-building activities, wellness programs, and clear communication to enhance engagement.
- **Enhance Benefits and Career Growth**:
    - Ensure compensation packages are competitive and review benefits.
    - Create a structured career development program with mentorship and growth opportunities.
    - Highlight learning and advancement opportunities in recruitment to attract talent seeking career progression.
- **Target Recruitment for the 25-34 Age Group**:
    - Showcase career growth and skill development opportunities in job listings and interviews.
    - Promote work-life balance with flexible arrangements and wellness initiatives.
    - Highlight an innovative, inclusive company culture that resonates with younger employees.
- **Optimize Job Listings and Strengthen Employer Branding**:
    - Tailor job descriptions to emphasize career growth, flexibility, and work-life balance.
    - Use compelling employer branding on LinkedIn, Indeed, and other platforms to showcase company culture and employee well-being.
    - Share employee testimonials, behind-the-scenes content, and success stories to attract candidates.
