**COVID-19 Data Analysis with Python & Pandas**

**Project Overview**
  This project performs an exploratory data analysis (EDA) on a global COVID-19 dataset. The goal is to extract meaningful insights regarding confirmed cases, deaths, and recoveries across different regions using the Pandas library. 
  This analysis covers data cleaning, filtering, and multi-variable sorting.

**Key Objectives**
The analysis seeks to answer the following technical and business questions:
    Regional Summaries: Calculate total Confirmed, Deaths, and Recovered cases per region.
    Data Integrity: Filter out low-impact records (regions with fewer than 10 confirmed cases).
    Extremity Analysis: Identify regions with the maximum confirmed cases and minimum death tolls.
    Geographical Deep-dive: Specific reporting for cases in India up to April 29, 2020.
    Statistical Sorting: Organizing data to identify trends in recovery and infection rates.

**Tech Stack**
Language: Python 3.x
Library: Pandas (Data Manipulation)
Environment: Jupyter Notebook 

**Analysis Roadmap**
The project is structured around solving these specific queries:
  Aggregation: Using .groupby() to consolidate regional data.
  Filtering: Removing noise from the dataset using boolean indexing.
  Global Leaders: Finding max/min values using .idxmax() and .sort_values().
  Time-Specific Queries: Isolating data for specific countries within defined timeframes.

