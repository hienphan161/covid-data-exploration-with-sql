# Exploring COVID-19 Data: An In-depth Analysis

# Introduction

In the face of the global COVID-19 pandemic, understanding the data behind the numbers is crucial. This project dives deep into COVID-19 datasets, leveraging data analysis and SQL querying to extract meaningful insights. We explore key metrics such as total cases, deaths, vaccinations, and their percentages, shedding light on the pandemic's impact worldwide.

## Project Highlights

1. **Connect to the Database:**
   - Utilize SQLite to connect to an SQLite database for efficient data manipulation.

2. **Load the Dataset:**
   - Import COVID-19 datasets from CSV files into the SQLite database for easy access.

3. **Data Exploration:**
   - Preprocess `COVID_DEATHS` and `COVID_VACCINATIONS` datasets, correcting data types and creating processed tables.

4. **Global COVID-19 Overview:**
   - Analyze global COVID-19 statistics, including total cases, deaths, vaccination efforts, and related percentages.
   - Visualize trends in new COVID-19 cases, deaths, and vaccinations worldwide over time.

5. **COVID-19 Impact Across Continents:**
   - Explore COVID-19 metrics for continents, examining infection rates, mortality, and vaccination progress.

6. **COVID-19 Impact Across Income Levels:**
   - Analyze COVID-19 impact and vaccination responses based on income levels, highlighting disparities.

7. **COVID-19 Impact Across Countries:**
   - Delve into COVID-19 metrics for individual countries, focusing on population, total cases, deaths, vaccinations, and trends.
   - Visualize regional patterns, vaccination progress, and challenges faced by countries.

8. **COVID-19 Trends in Vietnam:**
   - Focus specifically on Vietnam's COVID-19 situation, examining total cases, deaths, vaccinations, and trends over time.
   - Visualize the progression of the pandemic in Vietnam, highlighting key insights.

## Skills Utilized

- **Joins:** Connecting data from multiple sources for comprehensive analysis.

- **Common Table Expressions (CTE's):** Simplifying complex queries and calculations.

- **Temporary Tables:** Storing interim results for efficient data manipulation.

- **Window Functions:** Performing computations over specified subsets of data.

- **Aggregate Functions:** Summarizing data to reveal trends and patterns.

- **Creating Views:** Organizing data for future reference and visualization.

- **Converting Data Types:** Ensuring data compatibility and accuracy.


This project not only showcases SQL proficiency but also aims to uncover trends, disparities, and progress in the fight against COVID-19. Join us on this data-driven journey as we unravel the story behind the numbers.

# Overview of the dataset

In this project, we focus on analyzing specific aspects of the extensive [COVID-19 dataset](https://ourworldindata.org/covid-deaths). This dataset is diligently maintained by [Our World in Data](https://ourworldindata.org), with daily updates to ensure it reflects the latest information relevant to the COVID-19 pandemic. It encompasses a diverse range of crucial metrics sourced from reputable institutions, guaranteeing accuracy and reliability.

Our analysis hones in on the following key variables:

- **Confirmed Cases:** Total and new confirmed cases, smoothed averages, and cases per million people.
- **Confirmed Deaths:** Total and new deaths attributed to COVID-19, smoothed averages, and deaths per million people.
- **Vaccinations:** Total doses administered, people vaccinated, fully vaccinated, and booster doses.

The dataset we're using contains 390,786 rows spanning from January 1, 2020, to April 18, 2024. It is divided into two CSV files:

- **CovidDeaths.csv**: Contains the data on confirmed cases and deaths.
- **CovidVaccinations.csv**: Contains the data on vaccinations.

For further insights, you can explore the complete dataset [here](https://github.com/owid/covid-19-data/tree/master/public/data).
