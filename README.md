# Analyst-Portfolio

# Table of Content
- [Executive Summary](#executive-summary)
- [Objective](#objective)
- [User Story](#user-story)
- [Tools](#tools)
- [Development](#development)
   - [Data Cleaning](#data-cleaning)
   - [Pivot Tables](#pivot-tables)
- [Visualization](#visualization)
   - [Results](#results)
- [Analysis](#analysis)
    - [Findings](#findings)
    - [Validation](#validation)
    - [Discovery](#discovery)
- [Recommendations](#recommendations)
    - [Potential ROI](#potential-roi)
    - [Potential Courses of Actions](#potential-courses-of-actions)
- [Conclusion](#conclusion)

# Executive Summary
This project aims to design and implement an Emergency Room (ER) Operations Dashboard for 2024 that will help the hospital administration team make data-driven decisions to improve patient flow, satisfaction, and overall operational efficiency of the hospital departments in the following year.

The Primary user is Dr. Collins (Hospital Administrator), who faces challenges such as uneven resource allocation, low patient satisfaction scores, and unpredictable wait times.

The dashboard will analyze key metrics including average patient wait times, patient satisfaction scores, admission rates, referral patterns, and demographic trends. By visualizing these insights in a clear, easy-to-use format within Excel, the Hospital Administrator will be able to:

  1. Identify bottlenecks and peak periods in the ER.
  2. Optimize staffing schedules and resource planning.
  3. Target improvements in specific departments or patient groups.
  4. Support compliance with quality standards and reporting requirements.

Ultimately, this project supports the hospital’s mission to deliver timely, high-quality, and equitable emergency care while providing leadership with actionable insights to drive continuous improvement.

# Objective
- What is the key pain point?

   Dr. Collins, who is the Hospital Administrator, wants to know which departments in 2024 are understaffed by looking at the wait time and patient experience in those departments to identify which departments need more staffing or better coordination.

## User Story
Dr. Collins is a Hospital Administrator with 15 years in healthcare operations and hospital management. He needs a dashboard to analyse Emergency Room (ER) data in the hospital.
This dashboard should allow me to identify key operational patterns such as average patient wait times, department referral volumes, and satisfaction scores, broken down by demographics like age, gender, and race.

With this information, I can make more informed decisions about resource allocation, staffing schedules, and care process improvements - ultimately reducing wait times, improving patient satisfaction, and ensuring equitable healthcare delivery across all patient groups.

## Tools
| Tools | Purpose |
| --- | --- |
| Excel | Explore, Clean, Analyze & Visualize the data |
| Github | Hosting the project documentation |

# Development
## Data Cleaning
In the initial data preparation phase, I performed the following tasks:
1. Data loading and inspection
2. Removing unnecessary columns by filtering for only the columns I needed
3. Extract month, day of the week, and time from the datetime column to improve analysis

## Pivot Tables
### KPIs 
- Total number of patients in 2024
- Average patient score
- Average patient wait time
- Number of admitted or unadmitted patients

### Analytical Questions
1. What is the average patient wait time across different departments?
2. Do wait times or satisfaction scores vary by age?
3. Are wait times significantly higher during specific Months or hours?

# Analysis
## Findings
1. What is the average patient wait time across different departments?
| Departments | Avg Patient Wait time |
| --- | --- |
| Cardiology | 33.2 |
| Gastroenterology | 34.9 |
| General Practice | 34.3 |
| Neurology | 36.3 |
| None | 35.3 |
| Orthopedics | 36.5 |
| Physiotheraphy | 36.0 |
| Renal | 30.5 |

2. Do wait times or satisfaction scores vary by age?
| Age | Avg Satisfaction Scores |
| --- | --- |
| 1-10 | 5.0 |
| 11-20 | 5.1 |
| 21-30 | 4.7 |
| 31-40 | 5.2 |
| 41-50 | 5.0 |
| 51-60 | 5.2 |
| 61-70 | 4.3 |
| 71-80 | 4.1 |

2. Are wait times significantly higher during specific Months or hours?
