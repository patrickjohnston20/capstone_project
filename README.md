# Capstone Project: Factors Influencing College-Going Rates and Educational Attainment in Tennessee Counties

## Table of Contents

1. [Overview](#overview)
2. [Data Question](#data-question)
3. [Methodology](#methodology)
4. [Technologies](#technologies)
5. [Data Sources](#data-sources)
6. [Problems / Hurdles](#problems--hurdles)
7. [Conclusion](#conclusion)

## Overview

The focus of my capstone project is to investigate the key factors influencing college-going rates and educational attainment in different counties in Tennessee. Additionally, I aim to explore how these factors relate to undergraduate degree completion and financial aid accessibility. By analyzing various governmental datasets, my goal is to gain insights into the educational landscape in Tennessee and identify potential areas for improvement.

## Data Question

- What are the key factors influencing college-going rates and educational attainment in different Tennessee counties?
-   How do these factors relate to undergraduate degree completion?
-   How do these factors relate to financial aid accessibility?
-   *DISCLAIMER* - I had to pivot from incorporating more covid based analysis and localized metro data from Nashville Open Data site due to time constraints and lack of concrete data to further explore those metrics. These are both possibilites that I will explore in the future!

## Methodology

### Gathering the Data

[Census Data](https://www.tn.gov/education/districts/federal-programs-and-oversight/data/data-downloads.html)
Educational Attainment Demographics: [link](https://data.census.gov/table?q=educational+attainment&g=010XX00US_040XX00US47,47$0500000&tid=ACSDT1Y2018.B07009)
Ready Grad Metrics with County Profile Data through THEC(Tennessee Higher Education Commission): [link](https://www.tn.gov/thec/bureaus/ppr/county-profiles.html)


### Cleaning and Analyzing the Data

Utilizing Excel for primarily initial inspection and Python for the heavy lifting, I meticulously cleaned and organized the data by way of string manipulation, joining various tables for further inspection, formatting columns to all be uniform and much more. Government data sure is messy! 


### Visualizing the Data

Visualizations were crafted both in Python (using matplotlib and seaborn) and Tableau to present the data in a clear and engaging manner:
- Various heatmaps based on a county's certain metric, such as college going rate percentage, bachelor degree obtained percentage, and median income.
- Bar graphs to compare different counties and their values.
- Scatter plots to explore correlations between "Ready Grad" students and Financial Status labeled as either "economically Disadvantaged or Non-economically Disadvantaged"
- Interactive filters with Dashboards and Story in Tableau for further exploration and detail.

## Technologies Used

- **Python**: pandas, numpy, seaborn, matplotlib, primary way of cleaning all the data.
- **Excel**: some data cleaning and mostly initial visualizations
- **Tableau**: displaying key factors visually and creating interactive visualizations on highlighted factors

## Data Sources

- Educational Attainment Demographics: [link](https://data.census.gov/table?q=educational+attainment&g=010XX00US_040XX00US47,47$0500000&tid=ACSDT1Y2018.B07009)
- Ready Grad Metrics with County Profile Data through THEC(Tennessee Higher Education Commission): [link](https://www.tn.gov/thec/bureaus/ppr/county-profiles.html)

## Problems / Hurdles

### Normalizing Data

One of the main challenges that I faced was being hyper-vigilant regarding correct normalization of the data across different counties. With variations in population size and demographic composition, it was crucial to weight the data appropriately to ensure that each county was fairly represented in my analysis. This involved careful consideration of factors like population percentage and applying appropriate normalization metrics.

### Identifying Local Educational Attainment

Another significant hurdle was ensuring that the educational attainment information was specific to individuals born in each county. This required additional data filtering and transformation to isolate the relevant population, avoiding any distortions in the analysis that could arise from including individuals who moved into the county from other regions.

These challenges added complexity to the data preparation and analysis process but were essential to providing an accurate and meaningful insight into the education landscape in Tennessee. They required a combination of meticulous data handling and a deep understanding of the local context to make sure the numbers didn't seem uncharacteristic to locals like myself.

## Conclusion

The analysis provided key insights into education attainment in Tennessee:
- There seems to be a pattern of "TN Ready-Grad" Seniors and their metric "qualified" percentage based on financial disposition. Is this program actually working and helping or is it not?
- Income by county plays a role but is not the sole factor.
- Williamson County tends to be a massive outlier regarding most metrics. They have over 60% of adults aged 25-64 that have at least a Bachelor's. Next closest is Davidson with 38%. 
- Continued efforts are needed to ensure that every student has the opportunity to succeed in higher education regardless of circumstance. 

Thank you for taking the time to explore my capstone with me. Together, we can raise awareness and create change.

## Tableau Links
- Full Story: [link](https://public.tableau.com/views/PatrickFinalCapstoneStory/the_main_point?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
- TN Ready Grad Metrics only [link](https://public.tableau.com/views/ReadyGradTNMetrics-PatrickJohnston/ready_grad_tn_stats?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
