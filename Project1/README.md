# Project 1: Job Market Analysis (Salary and Skills)

## About This Project

In this project I analyzed data-related job postings in Excel to answer two questions: what these roles pay, and which skills employers ask for most.

I loaded the data with Power Query into two related tables (`data_jobs_all` and `data_jobs_skills`), built them into an Excel Data Model, and wrote my own DAX measures: Median Salary (overall, US, and non-US), Job Count, Skill Count, Skills Per Job, and Skill Likelihood. I then used pivot tables, slicers, and charts to explore the results.

## What I Built

| Sheet | Question I wanted to answer | What I made |
|---|---|---|
| `Salary_Vs_Skills` | Do more skills get you better pay? | A scatter chart of median salary against skills requested per posting, one point per job title |
| `Salary_Analysis` | How does pay compare between the US and other countries? | A pivot table of median salary (US, non-US, overall) by job title, with a country slicer |
| `Skill_Job_Analysis` | What are the top skills for a role? | A bar chart of the 10 most likely skills for the selected job title, with job title and country slicers |
| `Skill_Salary_Analysis` | What do the top skills pay? | A combo chart of median salary and skill likelihood for the top 10 skills, with a job title slicer |

One result from the workbook: for Data Engineer postings, the most likely skills are SQL (49%), Python (46%), AWS (30%), Spark (22%), and Azure (22%).

## Tools and Skills Used

- Power Query for loading data
- Excel Data Model with two related tables
- DAX measures (`CALCULATE`, `DIVIDE`, `MEDIAN`, `DISTINCTCOUNT`)
- Pivot tables, slicers, scatter, bar, and combo charts

**File:** `Project1 - analysis.xlsx`
