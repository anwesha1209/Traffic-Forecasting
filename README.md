# TRAFFIC FORECASTING

## Project Overview  
This project aims to forecast passenger traffic for JetRail, a high-speed rail system using jet propulsion technology. Investors from Unicorn Ventures are considering funding JetRail, provided it can achieve over 1 million monthly users within the next 18 months.  

## Objective  
The goal is to build a time series forecasting model to predict JetRail's daily traffic for the next 7 months, helping investors assess the feasibility of their investment.  

## Dataset  
Source: Historical JetRail traffic data  
Features:  
- Datetime: Timestamp of recorded traffic  
- Count: Number of passengers per recorded time interval  

## Methodology  
### 1. Data Preprocessing  
   - Convert timestamps to datetime format  
   - Handle missing values  
   - Resample data to daily granularity  

### 2. Exploratory Data Analysis (EDA)  
   - Visualize trends and seasonality  

### 3. Modeling with Facebook Prophet  
   - Train-test split (last 60 days as test set)  
   - Fit Prophet model with yearly seasonality  
   - Generate 7-month traffic forecast  

### 4. Evaluation  
   - Compare actual vs. predicted traffic  
   - Visualize forecast uncertainty bounds  

## Results  
- Forecasts JetRail's future traffic  
- Identifies trends and seasonal patterns  
- Provides insights for investment decision-making  

## Dependencies  
- Python 3.x  
- Pandas, NumPy, Matplotlib  
- Facebook Prophet  
