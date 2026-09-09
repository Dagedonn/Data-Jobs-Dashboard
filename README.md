# 📊 Data Jobs Dashboard

An interactive Power BI dashboard exploring the global job market for **Data Analyst**, **Data Engineer**, and **Data Scientist** roles — job volume, salary trends, and geographic distribution.

[data job dashboard](screenshot.png)
<!-- Add a screenshot or GIF of the dashboard here. Export a page as an image in Power BI (File > Export > Image), save it as screenshot.png in this repo, and update the path above. -->

## Overview

This project analyzes real-world job posting data to answer three core questions:
- **How many** data-related jobs are posted, and what do they pay?
- **What are the top roles** in demand within the data field?
- **Where** in the world are these jobs concentrated?

## Data Source

The dashboard is built on the **[Data Analyst Job Postings dataset](https://www.kaggle.com/datasets/lukebarousse/data-analyst-job-postings-google-search)** created by Luke Barousse, which aggregates data job listings (title, salary, location, and more) scraped from Google job search results.

| Field | Description |
|---|---|
| `job_title_short` | Standardized job title (e.g., Data Analyst, Data Engineer, Data Scientist) |
| `salary_year_avg` | Average annual salary |
| `salary_hour_avg` | Average hourly salary |
| `job_country` | Country where the job was posted |

## Dashboard Features

**KPI Cards**
- **340K** job postings
- **$116K** average yearly salary
- **$47.73** average hourly salary

**Top Data Jobs (Bar Chart)**
- Compares posting volume across Data Analyst, Data Engineer, and Data Scientist roles

**Where Are Data Jobs? (Map)**
- Visualizes job posting concentration by country

**Filtering**
- The page is pre-filtered to the three core roles (Data Analyst, Data Engineer, Data Scientist) to keep the focus on data-specific careers

## Key Insights

- **Data Engineer** has the highest posting volume of the three roles, followed closely by **Data Analyst**, with **Data Scientist** slightly behind — all three sit in the same general range (roughly 100K+ postings each)
- Job postings are heavily concentrated in **North America** and **Europe**, with smaller but notable clusters across Africa, Asia, and South America
- Across all three roles combined, the average yearly salary is **$116K**, with an average hourly rate of **$47.73** for hourly-paid positions

## Tools & Techniques

- **Power BI Desktop** — data modeling, DAX measures, report design
- **Power Query** — data cleaning and transformation
- **DAX** — aggregate measures (Sum, Average, Count) for KPI cards
- Data visualization: clustered bar chart, filled map, card visuals

## How to Explore

1. Download `Data_job_dashboard.pbix` from this repository
2. Open it in [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads) (free)
3. Interact with the visuals — click a bar or map point to cross-filter the rest of the page

## Skills Demonstrated

- Data modeling and cleaning in Power Query
- DAX measure creation
- Dashboard/report design (layout, KPI cards, filtering)
- Turning raw job-market data into a clear, explorable story

---


