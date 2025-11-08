# Analysis-of-Taxi-Travel-Patterns-Chicago-

Data analysis project for Zuber, a new ride-sharing company launching in Chicago. The goal is to find patterns in taxi ride data, understand passenger preferences, and assess the impact of external factors (such as weather) on ride frequency.

## 🎯 Business Objectives
Analyze competition in the Chicago taxi market

Identify patterns in passenger preferences

Assess the impact of weather on trip frequency

Determine the most popular neighborhoods for trip completion

Test hypotheses about factors affecting trip duration
## Generated Datasets
project_sql_result_01.csv
Trips by company (Nov. 15-16, 2017)
project_sql_result_04.csv
Average trips per neighborhood (Nov. 2017)
project_sql_result_07.csv
Loop → O'Hare Airport trips
🔬 Methodology
### Step 1: Web Scraping
- Extraction of Chicago weather data (November 2017)
- Source: Website specializing in meteorological data
- Techniques: Beautiful Soup, requests

### Step 2: SQL Analysis
- Complex queries with multiple JOINs
- Aggregations by company, neighborhood, and time period
- Filtering data by specific dates and conditions

### Step 3: Exploratory Analysis (Python)
- Importing and cleaning CSV datasets
- Validating data types
- Identifying the top 10 neighborhoods by trip completion
- Visualizations: bar charts, distributions

### Step 4: Hypothesis Testing
Hypothesis to be tested:
> “The average travel time from the Loop to O'Hare International Airport changes on rainy Saturdays.”

Null hypothesis (H₀): There is no significant difference in duration.
Alternative hypothesis (H₁): There is a significant difference.
Statistical method: Student's t-test.
Significance level: α = 0.05.