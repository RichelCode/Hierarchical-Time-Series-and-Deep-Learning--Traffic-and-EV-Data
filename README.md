# Hierarchical-Time-Series-and-Deep-Learning--Traffic-and-EV-Data

## **Project Overview**
This project focuses on analyzing and forecasting **traffic patterns in California’s District 3** using data from the **Caltrans Performance Measurement System (PeMS)**. The goal is to develop predictive models for traffic congestion trends, utilizing **hierarchical time series models and deep learning techniques**.

Additionally, the study will later incorporate **electric vehicle (EV) charging data** to assess its impact on traffic patterns, creating a holistic forecasting framework.

## **Dataset Information**
- **Source**: [PeMS District 3 Traffic Data](https://pems.dot.ca.gov/?dnode=Clearinghouse&type=station_hour&district_id=3&submit=Submit)
- **Data Type**: Hourly traffic measurements
- **Key Features**:
  - `Timestamp`: Time of data collection
  - `Station`: Unique traffic station identifier
  - `Route`: Road segment under study
  - `Direction of Travel`: North (N), South (S), East (E), West (W)
  - `Total Flow`: Total vehicle count per hour
  - `Avg Speed`: Average speed recorded per station
  - `% Observed`: Data reliability metric

## **Project Goals**
1. **Exploratory Data Analysis (EDA)**
   - Identify trends, seasonality, and anomalies in the traffic data.
   - Visualize hourly, daily, and weekly traffic patterns.

2. **Time Series Forecasting**
   - Implement **classical time series models** (ARIMA, SARIMA, Exponential Smoothing) to establish baseline forecasts.
   - Assess model performance and limitations.

3. **Hierarchical Time Series Modeling**
   - Develop **hierarchical time series models** to capture relationships at station, route, and district levels.
   - Compare aggregation/disaggregation strategies for forecasting.

4. **Deep Learning Integration**
   - Explore **LSTMs and Transformer-based models** for time series forecasting.
   - Compare deep learning approaches against traditional statistical models.

5. **Electric Vehicle (EV) Charging Data Integration**
   - Incorporate EV charging station data to assess its influence on traffic congestion.
   - Build an advanced forecasting model that integrates traffic and EV data.

## **Project Workflow**
1. **Data Collection & Preprocessing**
2. **Exploratory Data Analysis (EDA) & Visualization**
3. **Baseline Forecasting with Classical Time Series Models**
4. **Implementation of Hierarchical Time Series Models**
5. **Deep Learning Model Development**
6. **EV Charging Data Integration & Analysis**
7. **Final Model Evaluation & Results Interpretation**

## **Installation & Dependencies**
To run this project, install the following dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels tensorflow
```

## **Usage**
1. **Download the dataset from PeMS** and save it in the `data/` directory.
2. Run `data_preprocessing.ipynb` to clean and structure the dataset.
3. Execute `eda.ipynb` to explore traffic trends and visualize key patterns.
4. Implement forecasting models in `time_series_forecasting.ipynb`.
5. Develop deep learning models in `deep_learning_forecasting.ipynb`.
6. Integrate EV data and conduct a final analysis in `ev_analysis.ipynb`.

## **Expected Outcomes**
- **Accurate traffic forecasting models** for congestion prediction.
- **Insights into traffic patterns** at different levels (station, route, district).
- **Impact assessment of EV charging on traffic congestion**.
- **A robust forecasting framework** combining hierarchical and deep learning approaches.


