---
layout: page
title: Food Safety in Chicago
permalink: /projects/food-inspections/
---

# Food Safety in Chicago: Where Inspection Failures Happen and Why They Matter

**Authors:** Amritha Barani, Anurag Karthikeyan

[The Data](https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5){: .btn .btn--primary style="color: white;"}

[The Analysis Notebook](https://github.com/amritha-barani/amritha-barani.github.io/blob/main/final_project_food_inspections.ipynb){: .btn .btn--primary style="color: white;"}

## Main Visualization: Food Inspection Failure Rates by Facility Type
<iframe src="{{ '/inspection_failure_rates.html' | relative_url }}" width="100%" height="575" frameborder="0"></iframe>

## Contextual Visualization 1: Active Retail Food Establishments by Ward
<iframe src="{{ '/retail_food_establishments_by_ward (1).html' | relative_url }}" width="100%" height="525" frameborder="0"></iframe>

## Contextual Visualization 2: Open Grocery Stores by Zip Code
<iframe src="{{ '/grocery_store_status_by_zip (1).html' | relative_url }}" width="100%" height="525" frameborder="0"></iframe>

## Extra Credit Visualization: Overall Food Inspection Results

<iframe src="{{ '/inspection_results_breakdown.html' | relative_url }}" width="100%" height="500" frameborder="0"></iframe>

## Write Up
Food inspections help show whether institutions that serve/sell food are meeting public health standards. This dataset focuses on places in Chicago such as restaurants, grocery stores, daycares, schools, and more. Each row includes an inspection and has information about the facility type, inspection date, risk level, and result. For this project, we are focusing on failed inspections to understand which types of facilities have higher failure rates.

The main visualization, "Food Inspection Failure Rates by Facility Type", compares the inspection failure rate by the type of facilities. It is important to compare the rates because some facility types may have many more inspections than others. Using a percentage makes the comparison more fair because it shows the percentage of inspections that failed within each facility type. Additionally, there is a "year" dropdown included that allows the user to explore whether the failure rate patterns between facilities change over time. 

The contextual visualizations included allow us to understand more about Chicago's food environment/industry. The retail food facilities visualization (Contextual Visualization 1) reveals the ward where many active food businesses are located. This may help explain why there are more inspections in certain areas than others. A ward with more food facilities can have more inspections in the area because there are more places that need to be inspected. The grocery store visualization reveals where many open grocery stores are located by ZIP code. This gives further context on food access in Chicago. The main visualization illustrates why some types of facilities have higher failure rates in inspections, but it does not reveal the distribution of food options across the city. Having a visualization that shows how many grocery stores are located in each zip code will help individuals understand how food safety is connected to location and access. This gives readers more background when thinking about food safety, food businesses, and more. 

## Sources
City of Chicago. “Food Inspections.” Chicago Data Portal. https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5

City of Chicago. “Retail Food Establishments - Chicago.” Chicago Data Portal. https://data.cityofchicago.org/Community-Economic-Development/Retail-Food-Establishments-Chicago/efs4-hghf

City of Chicago. “Grocery Store Status Map.” Chicago Data Portal. https://data.cityofchicago.org/Health-Human-Services/Grocery-Store-Status-Map/rish-pa6g

Note: The main visualization, contextual visualizations, and extra credit visualization were created by the authors using Python, Pandas, and Altair. The code used to create these visualizations is available in the analysis notebook linked at the top of this page.
