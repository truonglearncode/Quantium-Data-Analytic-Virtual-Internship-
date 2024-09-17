# TASK 2: EXPERIMENTATION AND UPLIFT TESTING
## Table of Content
 - [Task Overview](#overview)
 - [Background Information](#background-info)
 - [Task Information](#task-info)
 - [My Result](#my-result)
 - [My Insight](#my-insight)
## Task Overview <a class = 'anchor' id = 'overview'></a>
**What I learn**
- Understand experimentation and uplift testing, comparing trial and control stores.
- Learn control store selection based on defined metrics.
- Gain experience in data visualization.
- Perform statistical analysis to assess sales differences and formulate recommendations.

**What I do**
- Define metrics to select control stores.
- Analyze trial stores against controls.
- Use Python for data analysis and visualization and summarise findings and provide recommendations.

## Background Information <a class = 'anchor' id = 'background-info'></a>
You are part of Quantium’s retail analytics team and have been approached by your client. The Category Manager for Chips, has asked us to test the impact of the new trial layouts with a data driven recommendation to whether or not the trial layout should be rolled out to all their stores. Examining the performance in trial vs control stores to provide a recommendation for each location based on our insight

**Some areas I will focus on**

`Select control stores` – explore the data and define metrics for your control store selection – think about what would make them a control store. Look at the drivers and make sure you visualise these in a graph to better determine if they are suited.

`Assessment of the trial` – this one should give you some interesting insights into each of the stores, check each trial store individually in comparison with the control store to get a clear view of its overall performance. We want to know if the trial stores were successful or not. 

`Collate findings` – summarise your findings for each store and provide an recommendation that outlining the impact on sales during the trial period.

## Task Information <a class = 'anchor' id = 'task-info'></a>

Evaluate the performance of a store trial which was performed in stores 77, 86 and 88.

This can be broken down by:

- total sales revenue
- total number of customers
- average number of transactions per customer

Create a measure to compare different control stores to each of the trial stores to do this write a function to reduce having to re-do the analysis for each trial store. Consider using Pearson correlations or a metric such as a magnitude distance e.g. 1- (Observed distance – minimum distance)/(Maximum distance – minimum distance) as a measure.

Once you have selected your control stores, compare each trial and control pair during the trial period. You want to test if total sales are significantly different in the trial period and if so, check if the driver of change is more purchasing customers or more purchases per customers etc.
