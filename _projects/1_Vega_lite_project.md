---
layout: default
title: HW6 Visualizations
---

# Homework 6 - Interactive Visualizations with Altair

## Visualization 1: Count of Licenses by License Type

<p>This bar chart visualizes the count of licenses grouped by license type. The chart helps identify which license types are most common by providing a clear, visual comparison of counts across different categories.</p>

### Design Choices
<p>The x-axis represents the license type, sorted in descending order of the count, while the y-axis displays the total count of licenses for each type. A distinct color encoding is applied for each license type, helping differentiate the categories visually and highlighting their relative magnitudes.</p>

### Data Transformations
<p>Data transformations included counting the number of licenses for each license type to generate a summarized view. Additionally, the x-axis was sorted by count to emphasize the highest and lowest categories.</p>

### Overlap with Homework #5
<p>In Homework #5, a different dataset was used with no emphasis on sorting or color encoding. This visualization introduces sorting based on counts and applies color encoding to enhance clarity and comparison.</p>

<iframe src="/python_notebooks/chart1.html" width="900" height="600"></iframe>



---

## Visualization 2: Interactive Filtered Count of Licenses by Status

<p>This line chart shows the filtered count of licenses by status (e.g., ACTIVE, EXPIRED, NOT RENEWED) over time. The interactive component allows for enhanced exploration of license trends and status changes.</p>

### Design Choices
<p>The x-axis represents time, shown as a Year-Month format, while the y-axis indicates the count of licenses. Different colors represent license statuses, making it easier to distinguish trends. Tooltips provide additional information, such as status and count, when hovering over points on the line.</p>

### Interactivity
<p>Interactivity is added via point markers on the line chart and tooltips. This allows users to explore data details dynamically by hovering, which improves the understanding of trends for specific statuses over time.</p>

### Data Transformations
<p>The data was filtered to include specific statuses (e.g., ACTIVE, EXPIRED, NOT RENEWED) to focus on meaningful trends. Date fields were transformed into Year-Month values for better temporal analysis.</p>

### Overlap with Homework #5
<p>Unlike Homework #5, this visualization incorporates interactivity and a focus on a subset of data categories. These enhancements allow for a deeper exploration of license status trends over time.</p>
<iframe src="/python_notebooks/filtered_chart.html" width="1000" height="480"></iframe>


---

<p>
  <a href="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/licenses_fall2022.csv" target="_blank" style="padding: 10px 20px; background-color: #007bff; color: white; text-decoration: none; border-radius: 5px; margin-right: 10px; display: inline-block;">The Data</a>  
  <a href="https://github.com/Saloniibonde/Saloniibonde.github.io/blob/main/python_notebooks/test_generate_plots.ipynb" target="_blank" style="padding: 10px 20px; background-color: #007bff; color: white; text-decoration: none; border-radius: 5px; display: inline-block;">The Analysis</a>  
</p>

