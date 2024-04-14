# PIC-16B-HW1

# Global Temperature Analysis

This repository contains data and Python scripts for analyzing global temperature trends. The analysis covers average temperature data across various countries and compares changes over the decades, highlighting potential indicators of climate change.

## Project Overview

The project involves importing temperature data, combining multiple datasets, and creating insightful visualizations to understand the changes in global temperature patterns. The project is structured into several parts, each addressing a specific aspect of data manipulation and visualization.

### Part 1: Data Preparation

- Combine multiple DataFrame objects to a large dataframe using `pandas.concat`.

### Part 2: Dataframe Creation

- Create a new DataFrame that includes temperature data along with country names, latitude, longitude, and station names.

### Part 3: Query Function

- Develop a function `query_climate` to extract temperature readings for specific countries and dates.

### Part 4: Global Warming Visualization

- Create bar plots to compare average temperatures of decades 1901-1910 and 2011-2020.

### Part 5: Advanced Plots

- Generate complex and interactive data visualizations to further analyze the temperature data.

## Dependencies

The analysis is performed using Python, with several external libraries:

- `pandas` for data manipulation.
- `numpy` for numerical operations.
- `matplotlib` and `seaborn` for data visualization.

Ensure you have these libraries installed before running the scripts.

## Repository Structure

### Visualization Examples
The script will output graphs that showcase the data's insights. For example:

Average temperature comparison by country and month for decades 1901-1910 vs 2011-2020.
Scatter plot with regression for individual countries.
Annotated heatmap of temperature correlations.
