# Jupyter-Visualization
A series of projects conveying the different types of visualizations on Jupyter with Notebook Widgets

Introduction
---

I'm back on the Python life, and I'll be developing new projects and projects innovated from tutorials on Jupyter! In particular, I will be practicing Juptyer's interactive widgets, which allows me to visualize data and graphs. Additionally, I will be attaching my codes as Jupyter notebooks and visualizations in the readme.

Project 1 - The Magic of Maps:
---

This project demonstrates Geospatial analytics. Geospatial analytics allows us to use geographic coordinates to indentify a specific address or a general area of the map. The image is then produced from satellite photography. For this process to occur, first install ipyleaflet from terminal (or an equivalent to terminal depending on your computer) and then apply ipyleaflet to obtain your satellite photo. The coordinates that I implemented in this map is Hell's kitchen, NYC. 

Installation: 
-----
Using conda: 
```
$ conda install -c conda-forge ipyleaflet
```
Visualization:
-----
<img width="783" alt="coordinate results" src="https://user-images.githubusercontent.com/27433542/50857780-9e951480-135c-11e9-88ef-c25738ef5881.png">

I later add the option to create circular and rectangular shapes on the map to pinpoint specific locations. The shapes represent the distance from my college to my favorite ramen place (which you all should go).

<img width="612" alt="screen shot 2019-01-09 at 5 30 55 pm" src="https://user-images.githubusercontent.com/27433542/50932823-bf309d80-1434-11e9-8625-bf0fef702e35.png">

Project 2 - Some Epic Scatter Plots:
-----

I then use bqplot, which is a 2-D interactive data visualization library. This allows me to create different types of plots and graphs in two dimensions. My first scatterplot is innovated from the example in Jupyter notebook where I assign a set size of plots and create a graph consisting of random values. My second scatterplot is uniquely developed, displaying a plot of a household's income based on the district that they reside in. 

Installation:
-----
Using conda:
```
$ conda install -c conda-forge bqplot
```
Next, bqplot is enabled with Jupyter lab:
```
$  jupyter labextension install bqplot
```

Visualizations:
-----
Epic Scatter Plot featuring vibrant colors:

<img width="549" alt="screen shot 2019-01-08 at 4 02 54 pm" src="https://user-images.githubusercontent.com/27433542/50858709-33007680-135f-11e9-9fbf-ad3a60153e38.png">

Annual Household Income by District:

<img width="579" alt="screen shot 2019-01-08 at 4 03 20 pm" src="https://user-images.githubusercontent.com/27433542/50858658-00ef1480-135f-11e9-8719-97499aea1678.png">
