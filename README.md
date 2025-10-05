# Data-Analyst-Jobs-Analysis
Data Analyst Jobs Analysis Description 
---
Data Analyst Jobs Market Analysis
This project provides an in-depth Data Analyst Jobs Market Analysis based on over 2,200 job listings. The goal was to uncover critical trends in salary, location, job title, and industry to provide data-driven insights for both job seekers and companies to optimize their strategies.

Dataset Overview and Preparation
The analysis utilizes a dataset containing over 2,000 job listings for data analyst positions.

Key Dataset Features
The dataset includes information on:

Job Title

Salary Estimate

Location

Company Rating

Industry and Sector

Company Size, Headquarters, and Type of Ownership.

Data Cleaning and Transformation
The following key steps were executed to prepare the data for analysis:

Column Management: Irrelevant columns ('Unnamed: 0', 'Founded', 'Competitors') were dropped.

Standardization: Column names were converted to a consistent snake_case format, and job titles (e.g., 'Sr. Data Analyst') were standardized to 'Senior Data Analyst' to avoid duplicates.

Salary Metric Creation: The MinSalary and MaxSalary were extracted from the 'Salary Estimate' text column, and the average_salary was calculated. This new average_salary (in thousands of dollars, or $K) became the primary metric for all salary-based analyses.

Data Integrity: Rows with missing or improperly formatted salary data were removed.

Key Analytical Findings and Visualizations
The analysis focused on three main areas: salary trends by title, job demand by sector, and salary by sector.

1. Salary and Job Title Trends
Most Common Titles (by Count): Data Analyst is the most common job title (405 listings), followed by Senior Data Analyst (131) and Junior Data Analyst (58).

Highest Paying Title: The Lead Data Analyst position commands the highest average salary, exceeding $80,000 annually, confirming that increased responsibility correlates with higher pay, though job availability is low.

General Salary Distribution: Average data analyst salaries are predominantly distributed between $60,000 and $80,000 per year.

2. Geographic and Company Insights
Top Work Locations (by Count): New York, NY, and Chicago, IL, have the highest number of job openings.

Top Locations by Salary: The highest-paying jobs are concentrated in California, with cities like Newark, CA, Daly City, CA, and Marin City, CA topping the list for average salary.

Company Attributes: There is no significant correlation between company size, or company ratings (most fall between 3.0 and 4.0), and the average salary. The majority of postings are from Company - Private ownership.

3. Sector and Salary Correlation
Highest Demand Sectors: Information Technology and Business Services have the highest number of job listings and are confirmed as the primary employers for data analysts.

Highest Paying Sector: The Biotech & Pharmaceuticals sector is the highest-paying, offering an average salary of over $80,000 annually, followed by Real Estate and Arts, Entertainment & Recreation. Information Technology is ranked 5th, with an average salary between $70,000 and $75,000.

Strategic Recommendations
For Data Analyst Job Seekers
Prioritize Pay vs. Volume: Job seekers prioritizing maximum income should target the Biotech & Pharmaceuticals and Real Estate sectors, despite the lower volume of job postings compared to IT.

Geographic Flexibility: Candidates who are geographically flexible should focus their search on high-paying Californian cities.

Career Progression: While Lead Data Analyst roles pay the most, the Senior Data Analyst role offers the most balanced approach for career progression due to its higher demand than Lead positions.

For Companies
Address the Seniority Gap: The high volume of 'Data Analyst' postings versus 'Senior Data Analyst' suggests a potential need for clearer internal career paths and targeted mid-level hiring to groom future leaders.

Benchmark Salaries: Companies in high-demand sectors (IT, Business Services) should benchmark their salaries against higher-paying adjacent sectors like Biotech & Pharmaceuticals to remain competitive in talent acquisition.

Repository Structure and Next Steps
original_data_analyst_jobs.csv: The raw dataset used for the analysis.

cleaned_data_analyst_jobs.csv: The cleaned and transformed dataset, including the calculated average_salary column.

Data_Analyst_Jobs_Analysis.ipynb: The Jupyter Notebook containing all data cleaning, transformation, analysis, and visualization code.

Executive_Report.pdf: The final executive summary report.

The three key dashboard visualizations (Top 10 Average Salary by Sector, Top 10 Job Postings Distribution by Sector, and Average Salary by Top 10 Job Titles) are included for quick reference.
