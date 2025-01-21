# DATA PROFESSIONALS’ SALARY DISTRIBUTION AND GROWTH TREND ANALYSIS (2020-2023)
## Project Objective
This project provides a comprehensive analysis of salary distribution and growth trends among data
professionals, including Data Analysts, Data Architects, Data Engineers, Data Scientists, and
Machine Learning Specialists, over a four-year period (2020_2023). The dataset, containing 11
columns and 3,755 rows, includes variables such as work year, job title, salary, company size
(small, medium, large), employment type (full-time, part-time, contract, freelance), experience
level (senior, expert, entry, experienced) e.t.c
## The analysis addressed key questions, such as:
● Salary statistics (average, minimum, and maximum) of data professionals.

● Trends in salary over the years among data professionals.

● Distribution of salaries across experience levels of data professionals.

● The impact of company size and employment type on salary distribution of data
professionals.

● Top-paying countries for data professionals.

● Data professionals with the highest growth trends over the years.

## Methodology
To ensure accurate and actionable insights, the dataset was cleaned, transformed, and analyzed
using a combination of tools.
## Tools used for analysis
The tools used for this analysis are Microsoft Excel, Microsoft PowerBI and SQL Server
## Data Cleaning and Transformation
**Excel**: Missing values were identified and handled appropriately. Duplicates
were removed, and data types were standardised.

**Power BI**: The dataset was loaded for transformation, including renaming
columns and replacing of values to standardise the data set
## Data Analysis
**SQL Server**: Structured Query Language (SQL) was used to perform in-depth analysis,
answering each of the key questions with queries designed to explore
relationships, compute aggregates, and identify trends.
## Visualization
**Power BI**: Charts and dashboards were created to visually represent insights,
such as salary trends over time, distributions, and comparisons across categories
like job titles, experience levels, and company sizes.
## Maintaining Data Integrity
Throughout the transformation process, the paramount goal was to uphold data integrity,
preserving the reliability and trustworthiness of the dataset
## Data Source
https://docs.google.com/spreadsheets/d/12JEfttQhnGC4gclIpfxAESPQQVu54kN3VCq_p0qyKpw/edit?usp=sharing

The dataset used for this analysis was sourced from Kaggle.com, a platform offering a wide range of
publicly available datasets. Kaggle’s datasets provide a rich and reliable foundation for data
analysis and insights. This particular dataset was pre-processed to ensure quality and
consistency before analysis.
## Questions to be answered
1. What is the total number of Data Professionals
2. What is the distribution of job titles in the dataset?
3. Salary statistics (average, minimum, and maximum) by job title over the years
4. What is the distribution of salaries across experience levels and job titles.
5. The impact of company size and employment type on salary.
6. What are the top 5 paying countries for data professionals?
7. Which Job title has the highest growth trends over the years.
## Dashboard
![Data PROFESSIONAL DASHBOARD dasborad](https://github.com/user-attachments/assets/d35e112c-a96b-4db1-a966-19f1bff00a98) 
## Insight Generated
**What is the total number of Data Professionals**
 ![Data Professionals Salary Distribution ANALYSIS-2](https://github.com/user-attachments/assets/8eb764fc-92d4-4f18-a0ec-e13270a98d5a)
SQL code (https://github.com/Yesumsughter/SQL-Excel-and-Power-BI-Data-Analysis-Project/blob/main/Count%20of%20data%20professionals%20by%20title.sql)

The dataset used for this analysis consisted of 3,755 entries, representing data professionals
across various roles, including Data Engineers, Data Scientists, Data Analysts, Machine
Learning Specialists, and Data Architects.

**What is the distribution of job titles in the dataset?**
![Data Professionals Salary Distribution ANALYSIS-3](https://github.com/user-attachments/assets/3e520209-0e7a-4adb-a0a5-6658ef46d2e4)
SQL CODE https://github.com/Yesumsughter/SQL-Excel-and-Power-BI-Data-Analysis-Project/blob/main/Count%20of%20data%20professionals%20by%20title.sql

The distribution of data professionals in the dataset indicated that Data Engineers were the most
represented group, accounting for the largest proportion (1,143 professionals), followed closely
by Data Scientists (1,139 professionals). Data Analysts (852 professionals) were the third most
common, while Machine Learning Specialists (513 professionals) and Data Architects (108
professionals) had smaller representations.
The distribution of data professionals highlights a strong demand for Data Engineers, reflecting
their critical role in building and maintaining data infrastructure to support analytics, machine
learning, and decision-making. Data Scientists are nearly as prevalent, reflecting their
importance in deriving actionable insights and solving complex problems. Data Analysts
followed after showing their role in Identifying trends, patterns, generating insights for decision
making and correlations in the data. In contrast, Machine Learning Specialists and Data
Architects are more specialized roles, likely concentrated in tech-focused sectors or requiring
niche expertise. This suggests that Data Engineers, Data Scientists and slightly Data Analysts
offer the most widespread career opportunities, while Machine Learning Specialists and Data
Architects may provide targeted but lucrative paths for skilled professionals. Overall, the
prevalence of these roles reflects organizational priorities in creating robust data pipelines and
leveraging insights, with selective investment in advanced AI and system architecture.

**● Salary statistics (average, minimum, and maximum) by job title over the years**
![Data sal-2](https://github.com/user-attachments/assets/65524368-f805-4990-92ca-d87d6930e1dc)

SQL CODE https://github.com/Yesumsughter/SQL-Excel-and-Power-BI-Data-Analysis-Project/blob/main/Average%2C%20min%2C%20and%20max%20salary%20by%20Job%20title.sql
**Average Salary**: Data Architects lead with an average salary of $160K, while Data Scientists
and Machine Learning Specialists follow closely with $147K each. Data Engineers average
$141K, and Data Analysts earn $112K on average.
**Maximum Salary**: Data Scientists earn the highest maximum salary ($450K), followed by
Data Analysts ($431K), Machine Learning Specialists ($424K), Data Architects ($376K), and
Data Engineers ($324K).
**Minimum Salary**: Data Architects have the highest minimum salary ($38K), while Data
Scientists, Data Analysts, Machine Learning Specialists, and Data Engineers each have a
minimum of $5K.
Data Architects earn the highest average salary, reflecting the specialized skills required for
their role, while Data Scientists have the highest maximum salary ($450K), highlighting their
value in advanced analytics. The $5K minimum salary for most roles likely represents global
disparities or entry-level positions in lower-paying regions. Although Data Engineers are in
high demand, their comparatively lower salaries suggest their work is more operational than
specialized. For professionals seeking higher pay, roles in Data Science, Architecture, or
Machine Learning may be more lucrative, but Data Engineering offers consistent opportunities
due to its steady demand.


**● What is the distribution of salaries across experience levels and job titles.**
![Data Professionals Salary Distribution ANALYSIS-5](https://github.com/user-attachments/assets/7feffd06-d325-431f-8b8b-649b3dae0aa4)

The analysis of salary distribution across experience levels and job titles shows clear trends in
how experience impacts earning potential:
**● Entry Level**:
Data Engineers and Machine Learning Specialists earn the highest at $88K, followed by
Data Scientists at $82K, Data Analysts at $59K, and Data Architects with no reported
salary, possibly due to the limited presence of entry-level roles in architecture.
**● Mid-Level**:
Data Architects lead with $150K, reflecting their high specialization, while Data
Engineers earn $104K, Data Scientists $100K, and both Data Analysts and Machine
Learning Specialists earn $99K.
**● Senior Level:**
Machine Learning Specialists earn the highest at $171K, followed by Data Scientists
($164K), Data Architects ($160K), Data Engineers ($152K), and Data Analysts
($126K).
**● Expert Level:**
Data Engineers top the scale with $207K, followed closely by Data Scientists at $200K,
Machine Learning Specialists at $164K, Data Architects at $168K, and Data Analysts at
$150K.
Machine Learning Specialists and Data Scientists command the highest salaries at senior and
expert levels, driven by the demand for advanced analytics and AI expertise. Data Architects,
with no entry-level roles, require significant experience but offer the highest mid-level salaries
due to their specialized skills. Salaries generally increase with experience, with Data Engineers
and Data Scientists experiencing the largest jumps, highlighting their long-term earning
potential. In contrast, Data Analysts show relatively lower salaries across all levels, reflecting
limited growth opportunities tied to their broader skill set. For career growth, professionals may
prioritize Machine Learning or Data Science, while those seeking high mid-level pay might
consider Data Architecture
## Conclusion
The analysis of salary trends and job distributions among data professionals reveals key
insights into the evolving landscape of the data industry. The demand for specialized roles like
Machine Learning Specialists and Data Scientists is evident, with these positions experiencing
the highest growth in both salary and market demand, reflecting the increasing reliance on AI,
machine learning, and advanced analytics across industries. Data Engineers also saw significant
salary growth, underscoring the critical role of building and maintaining data infrastructure in
today’s data-driven world.
On the other hand, roles such as Data Architects, while high-paying, showed signs of
stabilization after an initial surge, indicating a more niche demand. Data Analysts, though
integral to many organizations, experienced slower but steady growth, highlighting their more
generalist skill set compared to other specialized roles.
The impact of company size on salary distribution further emphasizes that larger companies
tend to offer more competitive compensation, particularly for specialized roles. Geographically,
the USA remains the dominant market for data professionals, offering significantly higher
salaries compared to other regions, though countries like the UK and Canada also provide
attractive opportunities.
In conclusion, professionals looking to advance in the data field should focus on acquiring
specialized skills in areas like machine learning and data science, while also considering factors
such as company size and location to maximize career growth and salary potential.
Understanding these trends will help both data professionals and organizations make informed
decisions to navigate the rapidly evolving data landscape
