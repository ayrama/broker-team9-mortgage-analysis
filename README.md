# Broker T's Mortgage Analysis (Team 9)

## Repository Overview
This repository contains the analysis project conducted by Team 9 (Broker T's) to explore the relationship between income, county, and mortgage rates in New York from 2018 to 2023. The study investigates how these factors influenced mortgage trends during the pre-pandemic, pandemic, and post-pandemic periods.

## Overarching Question
How does the county you live in and the income you make affect mortgage rates, particularly throughout the three stages of the COVID-19 pandemic (2018-2023)?

## Specific Questions
1. Is there a county with more of a specific loan type than others? What could explain this?
2. What loan types were most popular pre, during, and post-pandemic?
3. Based on race and sex, who took out the most and least loans? Were specific loans dominant?
4. Is there a skew in the total number of loans given out depending on the county or geographic area?
5. Do interest rates vary significantly by county, and how are they influenced by sex or race?

## Data Sources
1. **NYC Annualized Sales (2003-2023)**  
   Source: [NYC Department of Finance](https://www.nyc.gov/site/finance/property/property-annualized-sales-update.page#)  
   Description: Provides property sales data for NYC.

2. **Record Mortgages Originated NY (2016-2021)**  
   Source: [NY State Department of Financial Services](https://www.dfs.ny.gov/apps_and_licensing/mortgage_companies/rrpm_originated_nys)  
   Description: Contains records of mortgages originated in New York State.

3. **HMDA US Mortgage Data (5 Years)**  
   Source: [Consumer Financial Protection Bureau](https://www.consumerfinance.gov/data-research/hmda/)  
   Description: Loan-level mortgage data, including interest rates, loan terms, and loan types.

4. **S1901: Income in the Past 12 Months**  
   Source: [US Census Bureau](https://data.census.gov/profile/New_York?g=040XX00US36)  
   Description: Annual income data by household type and income brackets.

5. **S2401: Occupation by Sex for the Civilian Employed Population 16 Years and Over**  
   Source: [US Census Bureau](https://data.census.gov/profile/New_York?g=040XX00US36)  
   Description: Employment statistics by occupation and demographics.

## Project Goals
- Examine the relationship between income, geographic location, and mortgage trends.
- Analyze demographic factors (race, sex) influencing mortgage patterns.
- Study the impact of the COVID-19 pandemic on mortgage rates and types.

## Team Members
- **Maria Jerez**
- **Lauren Cardieri**
- **Ayrat Aymetov**

## Folder Structure
- `/data`: Contains raw and cleaned datasets.
- `/scripts`: Includes code for data analysis and visualization.
- `/docs`: Documentation related to the project.
- `/results`: Final outputs, including figures, tables, and conclusions.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/ayrama/broker-team9-mortgage-analysis.git
