# Analyst-Portfolio

# Table of Content
- [Objective](#objective)
- [Executive Summary](#executive-summary)

- [Data Source](#data-source)
- [Stages](#stages)
- [Design](#design)
  - [Mockup](#mockup)
  - [Tools](#tools)
- [Development](#development)
   - [Pseudocode](#pseudocode)
   - [Data Exploration](#data-exploration)
   - [Data Cleaning](#data-cleaning)
   - [Transform the Data](#transform-the-data)
   - [Create the SQL View](#create-the-sql-view)
- [Testing](#testing)
   - [Data Quality Tests](#data-quality-tests)
- [Visualization](#visualization)
   - [Results](#results)
   - [DAX Measures](#dax-measures)
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

The Primary user is Dr. Collins (Hospital Administrator) who faces challenges such as uneven resource allocation, low patient satisfaction scores, and unpredictable wait time.

The dashboard will analyze key metrics including average patient wait times, patient satisfaction scores, admission rates, referral patterns, and demographic trends. By visualizing these insights in a clear, easy-to-use format within Excel, the Hospital Administrator will be able to:

    1. Identify bottlenecks and peak periods in the ER.
    2. Optimize staffing schedules and resource planning.
    3. Target improvements in specific departments or patient groups.
    4. Support compliance with quality standards and reporting requirements.

Ultimately, this project supports the hospital’s mission to deliver timely, high-quality, and equitable emergency care — while providing leadership with actionable insights to drive continuous improvement.

# Objective
- What is the key pain point?
  Dr Collins who is the Hospital Administrator wants to know which departments in 2024 are understaffed by looking at the watitime and       patient experience in those departments to identify which departments need more staffing or better coordination.

## User Story
Dr. Collins is an Hospital Administrator with 15 years in healthcare operations and hospital management. He needs a dashboard to analyse Emergency Rooms (ER) data in the hospital.
This dashboard should allow me to identify key operational patterns such as average patient wait times, department referral volumes, and satisfaction scores, broken down by demographics like age, gender and race.

With this information, I can make more informed decisions about resource allocation, staffing schedules, and care process improvements - ultimately reducing wait times, improving patient satisfaction, and ensuring equitable healthcare delivery across all patient groups.


