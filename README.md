# COVID-19 Global Trend Analysis and Forecasting

A comprehensive data analytics and time-series forecasting project that analyzes the global spread of COVID-19 across 187 countries using Pandas, Plotly, and Facebook Prophet.

---

## Project Highlights

- Analyzed **49,068 COVID-19 records** spanning **187 countries**
- Performed exploratory data analysis (EDA) on infection, recovery, and mortality trends
- Visualized global and regional pandemic patterns using Plotly
- Identified the most affected countries and WHO regions
- Built a Facebook Prophet forecasting model for future case prediction
- Forecasted global COVID-19 confirmed cases one week into the future

---

## Technologies Used

- Python
- Pandas
- NumPy
- Plotly
- Facebook Prophet
- Google Colab
- GitHub

---

## Dataset Information

| Attribute | Details |
|------------|------------|
| Dataset | COVID-19 Clean Complete Dataset |
| Records | 49,068 |
| Countries Covered | 187 |
| Time Period | 22 January 2020 – 27 July 2020 |
| Features | Date, Country/Region, Confirmed, Deaths, Recovered, Active, WHO Region |

---

## Project Objectives

- Analyze the progression of COVID-19 across the world
- Study daily infection trends
- Evaluate recovery and death rates over time
- Identify the most affected countries and regions
- Forecast future confirmed cases using time-series modeling

---

## Key Findings

- Global confirmed cases exhibited exponential growth during the study period.
- Daily infection rates increased significantly after March 2020.
- Recovery rates improved steadily, reaching over 57% by July 2020.
- Death rates peaked around May 2020 and gradually declined.
- The Americas accounted for more than 50% of global confirmed cases.
- The United States, Brazil, and India were identified as the most affected countries.
- Prophet forecasting predicted continued growth in confirmed cases during the following week.

---

## Featured Visualizations

### Global Confirmed Cases Trend

![Confirmed Cases](images/confirmed_case_trend.png)

### WHO Region Analysis

![WHO Region Analysis](images/who_region_analysis.png)

### Global COVID-19 Distribution

![World Map](images/world_map.png)

### Prophet Forecast

![Prophet Forecast](images/prophet_forecast.png)

---

## Analysis Performed

### Exploratory Data Analysis (EDA)

- Global confirmed cases trend
- Daily new cases analysis
- Recovery rate analysis
- Death rate analysis
- Recovery rate vs death rate comparison

### Country-wise Analysis

- Top 10 countries by confirmed cases
- Top 10 countries by deaths

### Regional Analysis

- WHO region-wise distribution of cases

### Geographic Analysis

- Global COVID-19 choropleth map

### Forecasting

- Time-series forecasting using Facebook Prophet
- Seven-day future prediction of confirmed cases

---

## Project Workflow

1. Data Collection and Loading
2. Data Cleaning and Preprocessing
3. Feature Engineering
4. Exploratory Data Analysis
5. Country-wise and Regional Analysis
6. Visualization using Plotly
7. Forecasting using Facebook Prophet
8. Interpretation of Results

---

## Repository Structure

```text
COVID19-Global-Trend-Forecasting
│
├── data
│   └── covid_19_clean_complete.csv
│
├── docs
│   └── COVID-19_Project_Report.pdf
│
├── images
│   ├── confirmed_case_trend.png
│   ├── daily_new_cases.png
│   ├── death_rate.png
│   ├── recovery_rate.png
│   ├── recovery_vs_death_rate.png
│   ├── top_10_countries_by_confirmed_cases.png
│   ├── top_10_countries_by_death_cases.png
│   ├── who_region_analysis.png
│   ├── world_map.png
│   └── prophet_forecast.png
│
├── notebooks
│   └── COVID19.ipynb
│
├── requirements.txt
├── LICENSE
├── README.md
└── .gitignore
```

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/shrutea5112124/COVID19-Global-trend-forecasting.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open:

```text
notebooks/COVID19.ipynb
```

in Jupyter Notebook or Google Colab and execute all cells sequentially.

---

## Future Scope

- Forecast deaths and recoveries separately
- Compare country-specific infection trajectories
- Develop an interactive Streamlit dashboard
- Evaluate forecasting performance using MAE and RMSE
- Incorporate additional epidemiological indicators

---

## Author

**Shruti Turare**

B.Tech, Chemical Engineering  
Indian Institute of Technology Indore
