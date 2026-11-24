# Indian-startup-funding-analysis
# Indian Startup Funding Analysis (2018–2021)

## Project Overview
An exploratory data analysis project investigating startup funding patterns across industries, locations, years, startups, investors and funding types using Python.

## Objectives
- Identify industries receiving the highest funding.
- Compare funding activity across locations.
- Examine yearly funding trends.
- Identify startups and investors associated with major funding transactions.
- Analyse funding patterns across different funding stages.

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Dataset
The project uses an Indian startup funding dataset containing information about startup names, industries, locations, investors, funding types, dates and funding amounts.

Final dataset after cleaning: **331 records and 8 columns**.

## Data Cleaning
- Removed duplicate records.
- Standardised text fields by removing unnecessary whitespace.
- Converted date values into datetime format.
- Created a Year column for time-based analysis.
- Identified one missing date and retained the record for analyses that did not require dates.
- Investigated funding amount outliers and retained them as potentially genuine transactions.

## Key Findings
- **Industry:** Logistics recorded the highest total funding.
- **Location:** Bangalore led in total funding and number of funding records.
- **Year:** 2019 recorded the highest total funding.
- **Startup:** Rapido Bike Taxi had the highest recorded funding.
- **Investor:** Westbridge Capital was associated with the highest funding record.
- **Funding Type:** Series B recorded the highest total funding among identified funding types.

## Visualisations
See the `charts/` folder for the project visualisations.

## Business Recommendations
- Investigate industries attracting substantial funding while checking whether totals are dominated by individual large transactions.
- Examine Bangalore's funding activity and the large transactions influencing smaller locations' averages.
- Investigate the factors behind the 2019 funding peak.
- Compare startup funding totals with the number of funding rounds.
- Standardise investor information to improve investor-level analysis.
- Improve funding-stage classification to reduce unknown values.

## Limitations
- One record has a missing date.
- Some funding types are classified as Unknown.
- Multiple investors may be listed together in a single field.
- Currency information requires verification.
- The dataset may not represent the complete Indian startup ecosystem.

## Conclusion
This project demonstrates how exploratory data analysis can reveal patterns in startup funding and generate insights that support business and investment decisions.

---

**Project completed using Python and Google Colab.**
