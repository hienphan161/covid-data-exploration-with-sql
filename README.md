# Exploring COVID-19 Data: An In-depth Analysis

# Introduction

In this project, we delve into the extensive dataset of COVID-19, utilizing a range of SQL skills to extract meaningful insights. The dataset encompasses vital statistics on COVID-19 cases, deaths, population demographics, and vaccination progress across various locations and continents.

## Project Highlights

1. **Initial Data Exploration:**
- A look at the core dataset focusing on COVID-19 cases and population statistics.
- Understanding the progression of total cases, deaths, and infection rates.

2. **Country-specific Analysis:**
- Examining the likelihood of death if infected and the percentage of population infected.
- Identifying countries with the highest infection rates and death counts.

3. **Continental Breakdown:**
- Analyzing continents with the highest death counts per population.
- Understanding the global impact on different regions.

4. **Vaccination Progress:**
- Tracking the percentage of the population vaccinated.
- Utilizing various methods like CTEs and temporary tables for calculations.

5. **Data Storage and Future Use:**
- Creating a view for easy access to vaccination and demographic data.
- Setting the stage for insightful visualizations and further analysis.

## Skills Utilized

- **Joins:** Connecting data from multiple sources for comprehensive analysis.

- **Common Table Expressions (CTE's):** Simplifying complex queries and calculations.

- **Temporary Tables:** Storing interim results for efficient data manipulation.

- **Window Functions:** Performing computations over specified subsets of data.

- **Aggregate Functions:** Summarizing data to reveal trends and patterns.

- **Creating Views:** Organizing data for future reference and visualization.

- **Converting Data Types:** Ensuring data compatibility and accuracy.


This project not only showcases SQL proficiency but also aims to uncover trends, disparities, and progress in the fight against COVID-19. Join us on this data-driven journey as we unravel the story behind the numbers.

## Overview of the dataset

In this project, we focus on analyzing specific aspects of the extensive [COVID-19 dataset](https://ourworldindata.org/covid-deaths). This dataset is diligently maintained by [Our World in Data](https://ourworldindata.org), with daily updates to ensure it reflects the latest information relevant to the COVID-19 pandemic. It encompasses a diverse range of crucial metrics sourced from reputable institutions, guaranteeing accuracy and reliability.

Our analysis hones in on the following key variables:

- **Confirmed Cases:** Total and new confirmed cases, smoothed averages, and cases per million people.
- **Confirmed Deaths:** Total and new deaths attributed to COVID-19, smoothed averages, and deaths per million people.
- **Vaccinations:** Total doses administered, people vaccinated, fully vaccinated, and booster doses.

The dataset we're using contains 390,786 rows spanning from January 1, 2020, to April 18, 2024. It is divided into two CSV files:

- **CovidDeaths.csv**: Contains the data on confirmed cases and deaths.
- **CovidVaccinations.csv**: Contains the data on vaccinations.

For further insights, you can explore the complete dataset [here](https://github.com/owid/covid-19-data/tree/master/public/data).
