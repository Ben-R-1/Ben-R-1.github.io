---
title: Battery Plotting
permalink: /battery-plotting/
layout: single
---

This page will touch upon the basics of using Python and R as powerful tools to convert, process and plot battery cycling data. 
I picked up these skills during my PhD and want to show others how investing a small amount of time into learning to code can save a lot of time in the future, particularly those long monotnous origin or excel plotting sessions that more senior academics will insist on!

# 1. Getting the Battery Data
Firstly you're going to want to work with some nice reliable cell cycling data, [heres] a raw file you can work with. 

# 2. Converting the data into a readable format
Every battery cycler software that I'm aware of will produce data files in a format tailored to that software, this format allows you to easily play around with the data in the software provided and also keeps the data in a relatively compressed format. 
Unless you want to go through the excruciating pain of copying the data directly from the cycler software, it is best to read the files into a data frame format with Python. The [galvani](https://pypi.org/project/galvani/) package is best for this from my experience. This will read the raw battery cycling file into a dataframe via the [pandas](https://pandas.pydata.org/) package. If you want to then process the data in R or some other data processing software like MATLAB, then you can convert the dataframe into a csv file quite easily. 
(sidenote: I am aware there is a way to convert most raw battery data files into csv files via MATLAB and Origin but I want to use softwares that are completely free to everyone!

# 3. Having an initial look at the data 
Section to be added and updated.
