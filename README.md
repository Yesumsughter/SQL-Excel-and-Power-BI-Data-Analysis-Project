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

SQL CODE https://github.com/Yesumsughter/SQL-Excel-and-Power-BI-Data-Analysis-Project/blob/main/Distribution%20of%20salaries%20across%20different%20experience%20levels%20by%20job%20titles.sql

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
consider Data Architecture.

**● The impact of company size and employment type on salary.**
![Data Professionals Salary Distribution ANALYSIS-9](https://github.com/user-attachments/assets/4a7793fc-5af5-4c45-b21a-0cd0365b5fbd)

**Large Companies:**
Salaries are highest for Data Architects ($156K), followed by Machine Learning Specialists
($132K), Data Scientists ($128K), Data Engineers ($115K), and Data Analysts ($83K).
**Medium Companies:**
Data Architects lead again with $160K, followed by Machine Learning Specialists ($159K),
Data Scientists ($155K), Data Engineers ($144K), and Data Analysts ($118K).
**Small Companies:**
Salaries drop significantly, with Machine Learning Specialists earning the highest at $87K,
followed by Data Engineers ($81K), Data Scientists ($76K), Data Analysts ($62K), and no
reported salary for Data Architects.
Company size significantly influences salary levels, with medium companies offering the
highest pay across most roles, likely due to their need to attract specialized talent. Data
Architects earn the highest salaries in both large and medium companies, highlighting the value
of their specialized skills. While medium companies lead in salaries, large companies still offer
competitive pay, especially for Machine Learning Specialists and Data Scientists, due to their
resources. Small companies offer lower salaries, possibly due to budget constraints or a focus
on less specialized tasks, and the absence of Data Architect roles suggests limited opportunities
for such specialization. Professionals aiming for higher salaries should consider medium or
large companies, particularly in specialized roles.

**● What are the top 5 paying countries for data professionals?**
![Data Professionals Salary Distribution ANALYSIS-8](https://github.com/user-attachments/assets/3848d075-6d35-4780-afc9-34f1fee9378c)

The analysis of salary data across different countries reveals the following top-paying nations
for data professionals:
● USA: $461,539K
● United Kingdom: $14,945K
● Canada: $11,477K
● Germany: $4,944K
● Spain: $4,441
The USA leads as the top-paying market for data professionals, with a significantly higher
salary figure of $461.5 million, reflecting strong demand for data skills, particularly in tech
industries and advanced sectors like AI. The salary gap between the USA and other countries
highlights higher pay in the USA. This could be due to factors such as a larger tech market,
higher cost of living, and greater demand. While the UK, Canada, Germany, and Spain offer
competitive salaries, the UK and Canada stand out in Europe and North America. Despite the
pay disparity, these countries still offer lucrative opportunities, with the salary differences
reflecting global disparities influenced by market maturity and economic factors.

**● Which Job title has the highest growth trends over the years.**

Growth trends of Data Professionals over the years (2020-2023)
**2020:**
In 2020, Machine Learning Specialists had the highest salary at $113K, followed closely by
Data Scientists at $112K. Data Engineers earned $80K, and Data Analysts had the lowest salary
at $56K. Data Architects had no data available, indicating limited representation or new
emergence in the market.
**2021:**
In 2021, Data Architects saw a significant jump to $170K, indicating a high demand for
specialized roles in data architecture. Meanwhile, salaries for Machine Learning Specialists and
Data Scientists increased slightly to $83K and $100K, respectively. Data Engineers earned
$97K, and Data Analysts had a notable increase to $82K, showing overall salary growth across
all roles.
**2022:**
In 2022, Machine Learning Specialists and Data Scientists saw substantial increases, reaching
$141K each, reflecting the growing demand for AI and advanced data analytics skills. Data
Engineers also experienced growth to $137K, while Data Analysts reached $110K. Data
Architects saw a slight dip to $163K, suggesting some market stabilization after their initial
surge.
**2023:**
By 2023, Machine Learning Specialists had the highest salary increase, reaching $164K, while
Data Scientists saw a comparable rise to $163K. Data Engineers earned $150K, continuing their
steady growth. Data Architects' salaries slightly decreased to $156K, while Data Analysts
continued their gradual rise to $119K, maintaining a consistent but slower growth trend.
Over the four years, Machine Learning Specialists and Data Scientists exhibited the highest
salary growth, driven by increasing demand for AI and advanced analytics. Data Engineers also
saw significant growth, emphasizing the importance of data infrastructure. Data Architects
experienced initial strong growth but stabilized in recent years. Data Analysts had steady,
slower salary increases, reflecting sustained demand but less specialization. These trends
highlight the evolving market demands, with a focus on advanced technologies and specialized
roles like Machine Learning and Data Science.

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
