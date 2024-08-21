# Overview
Welcome to my analysis of the job market for Data Analysts in the United States. This project dives deep into top-paying and in-demand skills to find optimal job opportunities for data analysts.

The dats used in the project was sourced from Luke Barrouse's Python Course, which contained information about job titles, salaries, locations, and essential skills. Python was used for this project to explore the data and answer the following questions.

# The Questions
- What are the most demanded skills for the top 3 most popular data roles in the United States?
- How are in-demand skills trending for Data Analysts?
- How well do jobs and skills pay for Data Analysts?
- What are the most optimal skills for a data analyst to learn?


# Tools I Used
For my analysis of the Data Analyst job market, I harnessed the following tools:

- Python: Used for data cleaning, analysis, and visualization. More specifically, I used the Pandas library to analyze the data, the Matplotlib library to visualize the data, and the Seaborn library to create more advanced visualizations.
- Jupyter Notebooks: Used to run Python scripts and include notes within my analysis.
- Visual Studio Code: The environment I used to write and execute my code.

# The Analysis
## 1. What are the most demanded skills for the top 3 most popular data roles in the United States?

To find the most demanded skills for the top 3 most popular data roles, I filtered out the positions that were the most popular and got the top 5 skills for those top 3 roles. This highlights the most popular job titles and their top skills, showing which skills should have one's attention when looking at a certain role.

View my Jupyter Notebook with detailed steps here:
[2_Skill_Demand.ipynb](3_Project\2_Skill_Demand.ipynb)

### Results
![Visualization of top skills for in-demand data jobs](3_Project\skill_demand.png)

### Insights
- Python and SQL are all highly demanded across all 3 roles.
- Python seems to be more prominent in for Data Scientists(72%) and Data Engineers(65%).
- SQL is the most requested skill for Data Analysts and Data Engineers, with it being in over half of job postings for both roles. SQL is the second most requested skill for Data Scientists, but is still in over half of all job postings for that role.
- Data Engineers require more specialized technical skills (aws, azure, spark) whereas Data Analysts and Data Scientists are expected to be proficient in data management tools (excel, tableau).



## 2. How are in-demand skills trending for Data Analysts?

View my Jupyter Notebook with detailed steps here:
[3_Skills_Trend.ipynb](3_Project\3_Skills_Trend.ipynb)

### Results
![Visualization of demand of top skills for Data Analysts over time](3_Project\skills_trend.png)

### Insights
- Python, Tableau, and Power BI seem to be the most consistent throughout the year while SQL and Excel fluctuate and varying points.
- Python does appear to be increasing right at the end, so one could argue that it's demand could continue to grow after this point in time.
- While SQL and Excel flucuate alot, they are still the top 2 skills throughout the entire year.
- The demand for all of these skills seems somewhat stable.



## 3. How well do jobs and skills pay for Data Analysts?

View my Jupyter Notebook with detailed steps here:
[4_Salary_Analysis.ipynb](3_Project\4_Salary_Analysis.ipynb)

### Salary analysis for data roles

![Visualization of salary of top 6 data roles in the United States](3_Project\salary_analysis.png)

### Insights
- All senior roles pay higher than their respective junior roles.
- The Senior Data Analyst role pays lower than the Junior roles for Data Scientists and Data Engineers.
- The Data Scientist and Data Engineer roles show a lot more outliers than their respective Senior roles, suggesting that being very proficient in certain skills could lead to a higher salary compared to the more stable salaries of their Senior roles.



### Highest paid and most demanded skills for Data Analysts

![Visualization of highest paid and most demanded skills for Data Analysts in the United States](3_Project\highest_paid_vs_most_demanded.png)

### Insights
- Microsoft skills (Excel, PowerPoint, Word) seem to be the least paying skills while hard coding and visualization skills are paid higher.
- It's important to keep in mind that the skills that are the highest paid share no common skills with what is most in-demand. Meaning that the top paid skills aren't as needed.



## 4. What are the most optimal skills for a data analyst to learn?

View my Jupyter Notebook with detailed steps here:
[5_Optimal_Skills.ipynb](3_Project\5_Optimal_Skills.ipynb)

### Results

![Visualization of highest paid and most demanded skills for Data Analysts in the United States](3_Project\optimal_skills.png)

### Insights
- The closer a skill is to the top right corner, the more higher salary and prevalence that skills has.
- Cloud base skills consistently have high pay but are not very prevalent across job postings
- Analyst tools are both prevalent and have competitive salaries, showing that these skills are both valuable and needed. These skills also easily transfer between other common data tasks.