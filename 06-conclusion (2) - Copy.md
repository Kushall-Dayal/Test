﻿---
output:
  html_document: default
  pdf_document: default
---
# How to run a data viz project


## General Introduction

## Important Prerequisites of data visualization project

[@prerequisites_viz]

The below are the important prerequisites of a successful data visualization project.

+ ** As a data visual designer, understanding the goal of the project** is very important for a successful visualization project.Sometimes you may not be aware of the project goal, but you may know the reason why you are creating the visualization. This understanding will result in a good design.
+ ** Understanding the audience ** how they will process this visualization is another important prerequisite. Designing a visualization for scientists is entirely different from a visualization designed for law-makers or for general public. 
+ ** Understanding the data you are trying to visualize ** such as shape and dimension of the data, is data time-series, relationship in data between entities,categorical attribute exists is also an important prerequisite.


Defining the project:
[@prerequisites_vizhitachi]

+ ** Behind every project there is an organization need. The need could be simple or cumbersome, however you want to be able to have a measurable objective with the goal to deliver the right information. To do this you need to set requirements, design processes, schedule regular discussions with users and continue these meetings until the final project rollout. 
Sample questions that can help one understand the project better:
what is the organization need you are trying to address?
What are the main data sources you need to access?
Is there a measurable goal you want to achieve?


Data Visualization Selection:
[@prerequisites_vizhitachi]

+ ** Selecting the right visualization is key to your project. Most user want to see 'Key performance indicators' which are the main drivers for visualizations. The following are different kinds of visualizations that can be used to display KPIs:
Quantities: counts or measures. Example - Count of likes or comments
Trends and changes over time:  time series. Example - Change in sales quantity over time 
Relatives Share and proportions:  display relationship between the parts and the whole. Example - breakdown of a stock portfolio by asset.
Ranked list: although not a real data visualization, it could achieve the goal needed.
Geographical Location: Gives user spatial and physical relationships.


Choosing a tool to visualize:
[@prerequisites_tools]

The tool to be used for visualization.This depends on the person conducting the visualization, and the platform he wants to integrate his work into.It also depends on the ability of the user eg:-Tableau has a no code approach whereas D3.js ,Altair etc.These approaches are discussed in detail below: 

**No coding** :

On can start with MS Excel and probably use pivot tables feature, in excel you come up with decent charts.

If you already have some data and need a powerful tool to explore the data visually, Tableau is the tool. There is a free public version and a paid version , which students can get for free. One can publish the charts to web .To start Tableau Public website has a good number of examples to take inspiration from.

**Some coding:**

If somebody wants to venture in the coding world to build charts, R is a good start. It is easy to learn, free as it is opensource.One can us the ggplot library in R to come up with visual data exploration. You can publish these charts with the help Shiny package and add a bit of interaction as well.

  **More coding:**

This section is derived because of recent innovation in interactive visualization, especially on the web. One might ask where to start to come up with interactive visualizations as good as New York Times. The answer is D3.js, many of the data visualizations running in the browser today is D3.js, created by Mike Bostock. This does mean you&#39;ll need to learn some Javascript in general and then D3.js specifically. One area to call out as a particular strength of D3 is geospatial visualizations. D3 is great at creating maps of many flavors.

Finally, if you really want to learn a do-it-all programming language that just happens to be great at data visualization, go with Python. Python is a general purpose and powerful tool, and it&#39;s quite popular in the data science community. Finally, much like D3.js for Javascript or ggplot for R, there are many Python libraries dedicated to data visualization. Seaborn (which builds on an older popular library, matplotlib) and Bokeh are probably the best-in-class right now, but this is a quickly evolving and improving landscape. Both the [Seaborn](http://stanford.edu/~mwaskom/software/seaborn/examples/index.html) and [Bokeh](http://bokeh.pydata.org/en/latest/docs/gallery.html) websites include galleries showing off the kinds of visualizations you can create with those tools.




