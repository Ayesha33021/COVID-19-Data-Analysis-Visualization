# COVID-19 Data Analysis & Visualization

## Overview

This project analyzes the global impact of the COVID-19 pandemic using Python for data analysis and Power BI for interactive dashboard creation. The analysis explores infection trends, mortality, population-level impact, and country-wise comparisons through exploratory data analysis, feature engineering, time-series analysis, and business intelligence visualizations.

The project demonstrates an end-to-end data analytics workflow, from data preprocessing to interactive dashboard development.

---

## Project Objectives

* Clean and preprocess real-world COVID-19 data.
* Perform exploratory data analysis (EDA).
* Analyze infection and mortality trends across countries.
* Engineer meaningful analytical features.
* Study relationships between demographic and economic indicators.
* Build interactive Power BI dashboards for data exploration.
* Present insights using professional visualizations.

---

## Dataset

**Source:** Our World in Data COVID-19 Dataset

### Features Used

* Continent
* Country
* Date
* Total Cases
* New Cases
* Total Deaths
* New Deaths
* Population
* GDP per Capita
* Life Expectancy

### Engineered Features

* Death Rate
* Infection Rate
* Case Growth

---

## Technologies Used

### Programming

* Python

### Python Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn

### Business Intelligence

* Power BI
* DAX

---

## Project Workflow

### 1. Data Collection

* Imported COVID-19 dataset.
* Selected relevant analytical features.

### 2. Data Cleaning

* Removed missing values.
* Converted date columns.
* Handled duplicate records.
* Corrected data types.

### 3. Feature Engineering

Created additional metrics including:

* Death Rate
* Infection Rate
* Case Growth

### 4. Exploratory Data Analysis

Performed analysis including:

* Global case trends
* Daily new cases
* Daily deaths
* Country comparisons
* Population impact
* Correlation analysis
* GDP vs COVID impact
* Life expectancy analysis

### 5. Time Series Analysis

* Daily trend visualization
* 7-day moving average
* Growth trend analysis

### 6. Dashboard Development

Built an interactive Power BI dashboard featuring:

* KPI Cards
* Global trend analysis
* Country-wise comparison
* Top affected countries
* Death rate analysis
* Interactive filters
* Scatter plot analysis
* Country statistics table

---

## Dashboard Features

### KPI Cards

* Total Cases
* Total Deaths
* New Cases
* New Deaths
* Countries
* Continents
* Average Death Rate
* Average Infection Rate

### Interactive Filters

* Date
* Continent
* Country

### Visualizations

* Global Daily Cases Trend
* Global Daily Deaths Trend
* Top 10 Countries by Total Cases
* Top 10 Countries by Death Rate
* GDP per Capita vs Life Expectancy Scatter Plot
* Country Statistics Table

---

## Key Insights

* Identified countries with the highest COVID-19 case counts.
* Compared mortality rates across countries.
* Examined infection rates relative to population.
* Explored relationships between GDP, life expectancy, and COVID-19 impact.
* Visualized global pandemic trends over time.

---

## Repository Structure

```
COVID-19-Data-Analysis/

│
├── data/
│   └── covid_cleaned.csv
│
├── notebooks/
│   └── COVID_Analysis.ipynb
│
├── powerbi/
│   └── COVID_Dashboard.pbix
│
├── images/
│   ├── dashboard.png
│   ├── dashboard_page1.png
│   └── dashboard_page2.png
│
├── README.md
│
└── requirements.txt
```

---

## Results

The project combines Python analytics with Power BI reporting to transform raw COVID-19 data into interactive dashboards and actionable insights. It demonstrates skills in data cleaning, feature engineering, exploratory data analysis, business intelligence, and dashboard design.

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Visualization
* Time Series Analysis
* Business Intelligence
* Dashboard Development
* Power BI
* DAX
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn




If you found this project useful, feel free to star the repository.
