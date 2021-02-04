# The Power of Plots

![](Images/Laboratory.jpg)

In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. This analysis will generate all of the tables and figures needed for the technical report of the study.

This Python script will analyze the records will generate all of the tables and figures needed by perfoming the following:

  - Check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID and use the cleaned data for the remaining steps
  - Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen
  - Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment regimen throughout the course of the study
  - Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style
  - Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.
  - Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
  - Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.


