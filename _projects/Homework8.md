---
name: Building Inventory Visualization
tools: [Python, HTML, Altair]
description: This is a project that includes visualizations made with the buildings inventory dataset. 
custom_js:
 - vega.min
 - vega-lite.min
 - vega-embed.min
 - just charts
---


# Building Inventory Dataset Visualization

### Plot 1: Visualization of square footage and total floors of a building 

<vegachart schema-url="{{ site.baseurl }}/assets/json/scatter1.json" style="width: 100%"></vegachart>

### Write-Up for Plot 1

This scatter plot visually illustrates the relationship between the floor area of a building and its corresponding square footage. Additionally, it provides insight into the construction years of these buildings, shedding light on whether older structures tend to exhibit more floors and square footage in comparison to newer ones. The choice of a scatter plot was deliberate, as it offers an effective means of identifying outliers and discerning patterns among these three key variables. The 'inferno' color scheme was selected for its consistency in color, making it easier to distinguish outliers due to its darker shades at the lower end of the spectrum.

### Plot 2: Interactive plot of Congresss members, Congress District and Rep Dist. 

<vegachart schema-url="{{ site.baseurl }}/assets/json/altair_mobility_local_dashboard.json" style="width: 100%"></vegachart>

### Write-Up for Plot 2

This interactive plot combines two distinct chart types to provide insightful information. The first chart takes the form of a rectangular grid, displaying Congress members alongside their corresponding Congressional Districts. The second chart adopts a bar chart format to effectively illustrate Representative Districts and their corresponding record counts. The chart's height is set at 200 to ensure full visibility of all Congress members' names.

The choice of a bar chart is deliberate, as it accurately reveals the Representative District with the highest count for each selection made in the first chart. The interactive nature of this chart enhances its appeal and clarity, particularly considering the substantial volume of data it conveys. In essence, it consolidates what would typically require multiple plots into a single, comprehensive visualization.

<div class='left'>
<a class="m-1 btn btn-outline-primary btn-2 " href="https://github.com/harishr03/harishr03.github.io/blob/main/assets/json/altair_mobility_local_dashboard.json">
The Data
</a>
</div>

<div class="right">
<a class="m-1 btn btn-outline-primary btn-2 " href="https://github.com/harishr03/harishr03.github.io/blob/main/python_notebooks/HW8.ipynb">
The Analysis
</a>
</div>