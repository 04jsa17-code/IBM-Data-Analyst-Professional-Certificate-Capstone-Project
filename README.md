# IBM Data Analyst Professional Certificate – Capstone Project

**Project Title:** Technology Trends Analysis – Stack Overflow Developer Survey

This is the capstone project for the **IBM Data Analyst Professional Certificate** on Coursera, synthesizing skills from all 11 courses in the program.

## Overview

- Collected job posting data via API calls and scraped programming language salary data using BeautifulSoup
- Performed comprehensive data wrangling on the Stack Overflow Developer Survey dataset (65,000+ respondents, 114 columns)
- Conducted exploratory data analysis (EDA) to identify trends in programming languages, compensation, job satisfaction, and remote work
- Built interactive data visualizations using Matplotlib, Seaborn, and Plotly
- Developed an interactive dashboard using IBM Cognos Analytics
- Presented findings in a final data-driven presentation

## Technologies Used

- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly / Plotly Express
- Dash
- BeautifulSoup
- SQLite / SQL
- IBM Cognos Analytics
- openpyxl

## Project Modules

### Module 1 — Data Collection
- Collected job posting counts for 7 US cities and 12 programming technologies using a REST API
- Scraped programming language salary data from a live webpage using BeautifulSoup
- Saved results to `job-postings.xlsx` and `popular-languages.csv`

### Module 2 — Data Wrangling
- Loaded and explored the Stack Overflow Developer Survey dataset (65,000+ rows)
- Identified and removed duplicate rows
- Handled missing values using forward-fill, mode imputation, and median imputation
- Applied Min-Max scaling and Z-score normalization to compensation data
- Performed one-hot encoding on categorical variables
- Created new feature columns including `ExperienceLevel` and `Employment_Imputed`

### Module 3 — Exploratory Data Analysis
- Analyzed relationships between years of experience and job satisfaction
- Investigated remote work trends by country and employment type
- Identified top programming languages by region
- Calculated Pearson correlation between compensation, work experience, and satisfaction
- Detected and removed outliers using the IQR method

### Module 4 — Data Visualization
- Created histograms, box plots, scatter plots, bubble plots, pie charts, and stacked bar charts
- Visualized compensation distributions by country using box plots
- Built correlation heatmaps for key numerical variables
- Analyzed programming language trends using grouped bar charts

### Module 5 — Dashboard
- Built an interactive dashboard using IBM Cognos Analytics
- Visualized current technology usage and future technology trends
- Analyzed demographic data of survey respondents

## Key Insights

- Python, JavaScript, and SQL dominate both current usage and desired future learning
- Full-time employed developers make up the vast majority of respondents across all countries
- Compensation varies significantly by country with the US leading globally
- Job satisfaction shows weak correlation with years of experience
- Remote work preferences differ significantly by region and employment type

## Files

- `DataCollectionAPI.ipynb` — API data collection notebook
- `WebScraping.ipynb` — Web scraping notebook
- `DataWrangling.ipynb` — Data wrangling notebook
- `EDA.ipynb` — Exploratory data analysis notebook
- `Visualization.ipynb` — Data visualization notebook
- `job-postings.xlsx` — Job postings data by city and technology
- `popular-languages.csv` — Programming language salary data
- `survey_cleaned.csv` — Cleaned Stack Overflow survey dataset

## About

End-to-end data analysis capstone using Stack Overflow survey data — data collection, wrangling, EDA, visualization, and interactive dashboards — Final project for the IBM Data Analyst Professional Certificate

---

**Part of the IBM Data Analyst Professional Certificate** (11-course program)
