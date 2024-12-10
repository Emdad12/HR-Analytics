# HR-Analytics
### Project Overview
In this project, I conducted a comprehensive analysis of employee performance and satisfaction using Power BI. The goal was to uncover insights into performance trends, satisfaction levels, and the influence of education and rating levels on employee outcomes. Using six interconnected tables, I built a robust data model to deliver actionable insights for human resource management.
### Objectives
- Understand trends in employee performance ratings and satisfaction levels.
- Analyze how education level impacts performance and satisfaction.
- Explore patterns based on rating levels to identify high-performing groups.
- Provide an interactive dashboard for decision-makers to monitor HR metrics.
### Dataset Details
The analysis utilized the following six tables:

- DimRatingLevel: Employee performance rating categories.
- DimSatisfiedLevel: Satisfaction level ratings for employees.
- DimEducationLevel: Education qualifications of employees.
- FactPerformanceRating: Core fact table containing performance metrics and satisfaction ratings.
- DimEmployee: Employee demographic details such as age, gender, and department.
- DimDate: Time dimension for temporal analysis of performance trends.
### Tools and Technologies
- Power BI: For data cleaning, modeling, and dashboard creation.
- Excel: Initial exploration and preparation of the dataset.
### Process and Approach
1. Data Preparation and Cleaning

- Cleaned the dataset using Power Query in Power BI.
- Handled missing data in key fields, such as education levels and performance ratings.
- Standardized categorical data (e.g., rating levels, satisfaction levels) for consistency.
3. Data Modeling
  
- Designed a star schema with FactPerformanceRating as the central fact table.
- Linked the fact table to dimension tables (e.g., DimRatingLevel, DimSatisfiedLevel) using primary and foreign keys.
- Created calculated columns and measures, including average performance rating, satisfaction scores, and rating distribution.
4. Analysis and Visualization
  
- Developed an interactive dashboard to visualize key HR metrics:
- Performance Analysis: Trends in performance ratings over time, categorized by department and education level.
- Satisfaction Analysis: Satisfaction levels by demographic groups and performance tiers.
- Education Insights: Correlation between education level and performance.
- Rating Breakdown: Distribution of ratings across departments and time periods.
5. Metrics and KPIs
  
- Average Performance Rating per Department
- Satisfaction Levels by Education Group
- Rating Distribution (%) by Demographics
- Year-over-Year Performance Improvement (%)
### Key Insights
- Employees with higher education levels showed a consistent trend of higher performance ratings.
- Satisfaction levels were notably lower among employees in specific departments, indicating areas for improvement.
- Performance ratings peaked during certain months, suggesting seasonal influences on productivity.
### Deliverables
- Power BI Dashboard : An interactive visualization of HR metrics.
- Sample Dataset: A processed version of the dataset for demonstration purposes.
- Documentation: Detailed explanation of the data model and analysis process.
### Next Steps
- Incorporate advanced statistical analysis using R or Python for predictive modeling.
- Automate the data refresh process in Power BI for real-time updates.
- Expand the analysis to include employee retention and attrition patterns.
### Acknowledgments
Special thanks to the HR department for providing the dataset and supporting this analysis.

