---
title: Battery Plotting
permalink: /battery-plotting/
layout: single
---

Battery cyclers often save results in formats designed for their own software. Turning those files into tidy data makes it easier to check experiments, compare cells and create repeatable plots.

This guide is a work in progress. It focuses on free tools I used during my PhD and is intended for researchers who want a practical alternative to copying results by hand into spreadsheets or plotting software.

## 1. Read the raw data

For BioLogic .mpt files, the [Galvani Python package](https://github.com/echemdata/galvani) can read the measurement data into a [pandas](https://pandas.pydata.org/) DataFrame. Check the file format and instrument export options first, since different cyclers store data differently.

## 2. Prepare a portable table

Once the data is in a DataFrame, Python can be used to select columns, clean labels and save a CSV file. CSV is convenient when you want to continue analysis in R, MATLAB or another tool.

## 3. Explore and plot

Start by checking the data structure, units and cycle numbering. Then plot a small number of useful views, such as voltage against capacity or capacity against cycle number. Repeatable scripts make it easier to apply the same steps across multiple cells.

More examples and a sample dataset will be added in a future update.
