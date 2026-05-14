---
layout: page
title: Food Safety in Chicago
permalink: /projects/food-inspections/
---

# Food Safety in Chicago: Where Inspection Failures Happen and Why They Matter

**Authors:** Amritha Barani, Anurag Karthikeyan

[The Data](https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5){: .btn .btn--primary}
[The Analysis Notebook](put something){: .btn .btn--primary}

## Main Visualization: Food Inspection Failure Rates by Facility Type
<iframe src="{{ '/inspection_failure_rates.html' | relative_url }}" width="100%" height="575" frameborder="0"></iframe>

## Contextual Visualization 1: Active Retail Food Establishments by Ward
<iframe src="{{ '/retail_food_establishments_by_ward.html' | relative_url }}" width="100%" height="525" frameborder="0"></iframe>

## Contextual Visualization 2: 

## Write Up
  Food inspections help show whether institutions that serve/sell food are meeting public health standards. This dataset focuses on places in Chicago such as restaurants, grocery stores, daycares, schools, and more. Each row includes an inspection and has information about the facility type, inspection date, risk level, and result. For this project, we are focusing on failed inspections to understand which types of facilities have higher failure rates.

  The main visualization, "Food Inspection Failure Rates by Facility Type", compares the inspection failure rate by the type of facilities. It is important to compare the rates because some facility types may have many more inspections than others. Using a percentage makes the comparison more fair because it shows the percentage of inspections that failed within each facility type. Additionally, there is a "year" dropdown included that allows the user to explore whether the failure rate patterns between facilities change over time. 

  The contextual visualizations included allow us to understand more about Chicago's food environment/industry. 

## Sources
City of Chicago. “Food Inspections.” Chicago Data Portal. https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5

City of Chicago. “Retail Food Establishments - Chicago.” Chicago Data Portal. https://data.cityofchicago.org/Community-Economic-Development/Retail-Food-Establishments-Chicago/efs4-hghf
