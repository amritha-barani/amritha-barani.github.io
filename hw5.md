---
layout: page
title: Homework 5
permalink: /hw5/
---

# Illinois License Data Visualizations

[The Data](https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/licenses_fall2022.csv){: .btn .btn--primary}
[The Analysis](https://github.com/amritha-barani/amritha-barani.github.io/blob/main/hw5.ipynb){: .btn .btn--primary}

## Visualization 1

<iframe src="{{ '/visual1.html' | relative_url }}" width="600" height="350" frameborder="0"></iframe>

The first visualization shows the number of licenses for the most common License Type categories in the Illinois licensing dataset. I decided to use a bar chart because it is easy to compare the count of licenses across the different categories. The x-axis encodes License Type as a nominal variables and the y-axis encodes the number of records as a quantitative variable. Using different colors to encode this was also helpful because the bars are visually separated. Since License Type is a categorical variable, the default categorical color scheme was used instead of a gradient. A gradient was not needed because I only wanted the bars to have different colors, so the default color theme worked well. I also did not include a legend because the category names are already listen on the x-axis and I decided to include tooltips, so when a user hovers over a bar it will show the license type and the exact count. This makes the user be able to read the chart easier, instead of having to guess the count. When preparing the data, I removed rows with missing values and I also only used the top 15 most common license types to ensure that there was not too much information in the visualization. This helps the visualization to be easier to read and also makes the comparison clearer. 

## Visualization 2

<iframe src="{{ '/visual2.html' | relative_url }}" width="600" height="350" frameborder="0"></iframe>

This second visualization also shows counts of licenses by License Type, but it adds interactivity by letting the viewer filter the chart by License Status using a dropdown menu. I used a bar chart again because it makes category comparisons easy  to interpret. The x-axis encodes License Type as a nominal variables and the y-axis encodes the number of records as a quantitative variable. Color is again encoded to License Type so that the categories are visually distinct and consistent with the first plot. I used a c ategorical color scheme for this chart as well and did not include a legend because the x-axis already lists the cateogries. I decided to include tooltips, so when a user hovers over a bar it will show the license type, license status, and the exact count. I took the same steps as the first visualization to prepare the dataset. I dropped missing rows from both License Type and License Status. For interactivity, I used a dropdown menu for the License Status, which allows the user to choose one status at a time and see how the distribution of license types changes for that selection. I chose this because it makes the visualizaiton more clear, instead of showing every status at once. Having a dropdown makes the visualization look less complicated and allows the user to look at one subset of the data at a time, making comparisons easier. 