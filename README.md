
**Heart Failure Patient Analysis Dashboard**

## Overview
This Power BI dashboard provides an analytical view of heart failure patient data, aiming to uncover trends and patterns in demographics, medical conditions, and survival outcomes. 
The dataset used originates from clinical heart failure records and has been cleaned and enriched to allow for meaningful visualization.

## Data Source
- **Dataset:** Heart Failure Clinical Records (cleaned & transformed version of `heart_failure_clinical_records_dataset.csv`)
- **Number of Records:** 299
- **Number of Fields:** Includes demographics, lab results, health conditions, and survival status.

## Key Metrics
1. **Average Age of People Affected** – Displays the mean age of patients who died due to heart failure.
2. **Survival Status** – Percentage of patients who survived vs. died.
3. **Most Affected Gender** – Count of male and female deaths.
4. **Possible Causes of Death** – Breakdown of major risk factors (Anaemia, Diabetes, High Blood Pressure, Smoking, Unknown).
5. **Deaths by Age Group** – Distribution of deaths across different age ranges.
6. **Ejection Fraction by Survival Status** – Heart pumping efficiency comparison between survivors and non-survivors.

## Dashboard Components
### Filters (Slicers)
- **Diabetes** (Yes/No)
- **Sex** (Male/Female)
- **Age Group** (All or specific range)
- **Smoking** (Yes/No)

### Visualizations
1. **Card Visual** – Average age of people affected.
2. **Donut Chart** – Survival status percentage.
3. **Bar Chart** – Death events by sex.
4. **Bar Chart** – Count of survival status by possible causes.
5. **Horizontal Bar Chart** – Death events by age group.
6. **Line Chart** – Sum of ejection fraction by survival status.
7. **Pie Chart** – Possible causes for death.

## Insights
- Males have a higher number of deaths compared to females.
- The highest death rate is among patients aged **60–69**.
- Common risk factors include **High Blood Pressure** and **Smoking**.
- Patients with lower **ejection fraction** have significantly higher death rates.
- Survival rate is approximately **68%** in the dataset.

## Usage
1. Open the Power BI file containing this dashboard.
2. Use the slicers (Diabetes, Sex, Age Group, Smoking) to filter and explore the dataset.
3. Hover over charts to see detailed values and percentages.
4. Combine filters to drill into specific demographics or medical conditions.


