# COVID-19 Global Trend Analysis and Forecasting

## Project Overview

This project analyzes the global spread of COVID-19 using data collected from 187 countries between January 2020 and July 2020.

The project focuses on:

- Infection trend analysis
- Recovery rate analysis
- Death rate analysis
- Country-wise impact assessment
- WHO region-wise distribution
- Time-series forecasting using Facebook Prophet

Interactive visualizations were developed using Plotly, while Pandas was used for data preprocessing and aggregation.

---

## Objectives

- Analyze the progression of COVID-19 across the world.
- Study daily infection trends.
- Evaluate recovery and death rates over time.
- Identify the most affected countries and regions.
- Forecast future confirmed cases using Prophet.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Plotly
- Prophet
- Google Colab

---

## Dataset

Dataset: COVID-19 Clean Complete Dataset

Features:

- Date
- Country/Region
- Confirmed Cases
- Deaths
- Recovered Cases
- Active Cases
- WHO Region

Number of Records: 49,068

Countries Covered: 187

Time Period: 22 January 2020 – 27 July 2020

---

## Project Structure

```text
COVID19-Global-Trend-Forecasting
│
├── data
├── docs
├── images
├── notebooks
├── README.md
├── LICENSE
├── requirements.txt
└── .gitignore
```

---

## Key Analysis Performed

### Global Confirmed Cases Trend

Analyzed the cumulative growth of confirmed COVID-19 cases across the world.

### Daily New Cases

Calculated daily infection rates using first-order differencing.

### Recovery Rate Analysis

Recovery Rate = (Recovered / Confirmed) × 100

### Death Rate Analysis

Death Rate = (Deaths / Confirmed) × 100

### WHO Region Analysis

Studied the distribution of confirmed cases across WHO regions.

### Country-wise Analysis

Identified the top affected countries based on confirmed cases and deaths.

### Forecasting

Used Facebook Prophet to forecast future confirmed cases for the next seven days.

---

## Key Findings

- Global confirmed cases showed exponential growth during the study period.
- Daily infection rates increased significantly after March 2020.
- Recovery rate improved from below 10% to more than 57%.
- Death rate peaked around May 2020 and gradually declined.
- The Americas accounted for more than 50% of global confirmed cases.
- The United States, Brazil, and India were the most affected countries.
- Prophet forecasting predicted continued growth in confirmed cases during the following week.

---

## Results

The project successfully combined:

- Data Cleaning
- Exploratory Data Analysis
- Interactive Visualization
- Time Series Forecasting

to analyze the impact and future trajectory of the COVID-19 pandemic.

---

## Author

**Shruti Turare**

B.Tech Chemical Engineering  
Indian Institute of Technology Indore
