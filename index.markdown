---
layout: home
title: HW 5
---
Plot 1: Number of License Types

In this dataset, I am visualizing the number of License Types there is. License Type is a important column in this dataset and I wanted to visualize it some how. The encoding types of I used was catergorical and quantative. For x, in this dataset Lincese Type is categorical and I used the column name + the encoding variable N. For y, I I used count() to find the number of each License Type which is quantative(Q). Using color was not necessary for this visualization. I filtered the dataset to 5000 rows by using the head() function just to get the top 5000 because the dataset was too big for Jupyter Notebook to load.  

<iframe src="python_notebooks/plot1.json" width="600" height="400"></iframe>
[The Data](https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/licenses_fall2022.csv)
[The Analysis](https://github.com/jaidaduson/jaidaduson.github.io/blob/main/HW5.ipynb)

Plot2: License Type vs License Status
This plot is visualizing a heatmap that shows the relationship between License Type and License Status. The encoding choices I made was using categorical for both x and y variables. License Type is on the x-axis and License Status is on th y-axis. I used the encoding type color to count the number of each License Type per License Status. With blue being the top number of records and light green being the lowest number of records. I also filtered out the dataset to the first 5000 rows using the .head() function because the dataset was large. This plot is interactive, I used .tooltip to show case the hover over part. When you hover over a color it shows you License Type, License Status and Counts of Records. This interactive visualization helps users see the difference between the amount of License Status per License Types there is. 

<iframe src="python_notebooks/plot2.json" width="600" height="400"></iframe>

