# Data-Professional-Global-Salary-Insights-Power-BI-Dashboard
This project analyzes a global survey of over 600 data professionals to uncover trends in compensation, job satisfaction, and the technical landscape of the industry. 

Project Overview
​This project analyzes a global survey of over 600 data professionals to uncover trends in compensation, job satisfaction, and the technical landscape of the industry. I transformed raw, multi-response survey data into a clean, interactive dashboard that answers critical questions about the "state of data" across different countries and roles.

​Data Transformation (The Power Query Stage)
​Survey data is notoriously difficult to process. I utilized Power Query to perform heavy-duty ETL (Extract, Transform, Load) tasks:

​String Manipulation & Cleaning: Extracted numeric salary values from text-based ranges (e.g., "$100k-$120k") to create a continuous variable for average salary calculations.

​Handling Multi-Select Responses: Managed complex "Check all that apply" columns for programming languages and data tools to ensure they could be aggregated correctly.

​Data Profiling: Used Column Quality and Value Distribution tools to ensure the integrity of the data professional profiles before modeling.
​
Dashboard Insights & Visualizations
​The final report focuses on four primary pillars of the data profession:

​Compensation Analytics: A gauge visual tracking the Average Salary ($54k) against global benchmarks, segmented by job title and country.

​The Technical Stack: A treemap visualization identifying Python as the dominant programming language, followed by R and SQL, providing insight into the most valuable skills in the current market.

​Job Satisfaction Metrics: Analyzed the correlation between "Work-Life Balance" and "Salary Satisfaction" to provide a holistic view of professional well-being beyond just income.

​Demographic Distribution: A map visual showing the geographic spread of respondents, with significant concentrations in the US, India, and the UK.
​
Technical Skills Demonstrated
​Advanced Power Query: Splitting by delimiter, unpivoting columns, and conditional formatting to normalize survey responses.

​DAX Calculations: Created measures for Average Salary, Respondent Count, and Satisfaction Scores.

​UX/UI Design: Developed a cohesive visual theme with custom icons, layout containers, and interactive slicers for a seamless user experience.

Key Findings: 

​Market Dominance of Python: Out of 630 respondents, Python remains the primary programming language for data professionals, followed significantly by SQL and R, indicating that Python proficiency is the most critical skill for entry into the field.

​Global Salary Benchmark: The average global salary for a Data Professional in this dataset is $54,000. However, geographic heatmaps show a high concentration of premium salaries ($100k+) located in the United States, while the largest volume of respondents resides in India and the UK.

​Work-Life Balance vs. Pay: There is a strong correlation between job title and work-life balance satisfaction. While Data Scientists report higher average salaries, Data Analysts show a higher "Satisfaction with Work-Life Balance" score on a scale of 1-10.

​Entry Barriers: The data suggests that approximately 40% of respondents transitioned into data roles from non-technical backgrounds, highlighting the importance of specialized certifications and portfolio projects.
