# covidcases-analysis-
Here is the text formatted in Markdown with headings:

# Introduction

This repository contains R code for the analysis of various statistical and data-related tasks. The tasks include simulations, probability estimations, and data visualization using ggplot2. The code is organized into sections, each addressing a specific task.

# Setup 

Before running the code, make sure you have the required R packages installed. You can install them using the following:

```R
install.packages(c("maps", "tidyverse", "rvest", "uniformly", "lubridate", "e1071", "maditr", "data.table", "caTools", "scales"))
```

# Simulations and Probability Estimations

The code in this section performs simulations and calculates probabilities.

## Task 1: Monty Hall Problem

Simulates the Monty Hall problem and estimates the probability of winning by switching doors.

## Task 2: Cycle Detection 

Performs simulations to detect cycles in a permutation and estimates the expected cycle length.

## Task 3: Card Game Probabilities

Estimates the probability of drawing specific hands in a card game.

# Data Analysis

The following sections analyze COVID-19 data and economic indicators.

## COVID-19 Data Analysis

Loads and preprocesses COVID-19 global data.

Visualizes cumulative COVID-19 cases for each country in the Eastern Mediterranean Region (EMRO).

Visualizes cumulative COVID-19 deaths for each country in EMRO.

## Economic Indicators Analysis

Reads and processes economic data, focusing on population and GDP.

Merges COVID-19 data with economic data. 

Visualizes log-scaled cumulative COVID-19 cases per million for selected countries.

Visualizes log-scaled cumulative COVID-19 deaths per million for selected countries.

Analyzes the relationship between cases per million and deaths per million.

Examines the distribution of fatality rates. 

Identifies outlier countries based on fatality rates.

Visualizes smoothed new daily cases for countries with high deaths (>200,000).

Visualizes new daily cases and deaths for WHO regions.

## GDP and Population Analysis

Analyzes the distribution of GDP per capita by WHO region.

Analyzes the distribution of the population above 65 years old by WHO region.

# Conclusion

This repository provides comprehensive R code for various statistical analyses, simulations, and data visualizations. Feel free to explore the code and adapt it to your specific needs. If you have any questions or need further clarification, please reach out.
