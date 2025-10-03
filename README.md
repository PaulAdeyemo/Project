# London Bike Rides Analysis

Executive Summary

I carried out this project to explore bike-sharing usage in London and uncover patterns that could help operators and city planners make smarter decisions. Using Kaggle API (for data access), Python (for wrangling and analysis), and Tableau (for visualization), I discovered how weather, time of day, and seasonality influence ride demand. The project not only sharpened my skills in data acquisition, EDA, visualization, and storytelling, but also gave me experience in framing raw data into real-world business insights.

2. Business Problem

- Urban transport services like bike-sharing face constant challenges:

- How do we predict demand to ensure bikes are available when and where people need them?

- How do we reduce costs from station imbalances (empty/full stations)?

- How can insights guide policy and infrastructure investment?

- For this analysis, I treated myself as the data analyst in a bike-sharing company. My role was to answer these questions and provide  insights that decision-makers could act on.

3. Methodology

 Here’s how I approached the project step by step:

1. Data Acquisition

- Used the Kaggle API to download the London Bike Sharing Dataset.

-  Stored the raw dataset in .zip format, then extracted and loaded it into Python.

2.  Data Preparation

-  Consolidated multiple files into a single dataset (london_merged.csv).

-  Cleaned missing values, standardized datetime formats, and merged weather-related attributes.

3.  Exploratory Data Analysis (EDA)

- Examined daily, monthly, and yearly ride patterns.

- Applied moving averages to smooth seasonal fluctuations.

- Explored correlations between ridership, temperature, and weather conditions.

4. Visualization

- Built heatmaps in Tableau to show hourly demand across weekdays and weekends.

- Created a moving average dashboard in Tableau to highlight long-term demand trends.

5. Interpretation

- Framed findings in business language: when demand is highest, which external factors matter most, and how operators can respond.

4. Skills / Tools I Applied

- Kaggle API for dataset acquisition and integration into my workflow

- Python (pandas, numpy, matplotlib, seaborn) for cleaning, analysis, and visualization

- Tableau for dashboards, heatmaps, and time-series visualization

- Excel for quick data inspection and validation

- Statistical techniques: moving averages, correlation analysis, seasonal trend evaluation

- Business framing: translating technical results into insights for strategy and operations

5. Results & Business Requirements
Key Findings

🚴 Seasonality: Summer months showed the highest ridership, while winter dropped sharply.

⏰ Peak Demand: Strong spikes during morning (7–9 AM) and evening (5–7 PM) commute hours.

🌦️ Weather Impact: Clear correlation between warmer temperatures and higher ride counts.

📍 Station Utilization: Heatmaps revealed high-demand areas versus underutilized ones, highlighting rebalancing needs.

Business Requirements Addressed

- Demand Forecasting → Moving averages used to project future ridership.

- Station Optimization → Heatmaps identified stations needing redistribution strategies.

- Operational Efficiency → Insights guided resource allocation and staffing.

- Stakeholder Communication → Tableau dashboards provided interactive summaries for non-technical audiences.

6. Next Steps

If I were to extend this project, I’d focus on:

- Predictive Modeling: Build machine learning models (e.g., ARIMA, Prophet, Random Forest) to forecast ridership using weather and seasonal data.

- External Data Integration: Incorporate holidays, city events, and traffic data to refine predictions.

- Real-Time Analytics: Automate data pipeline from Kaggle (or live APIs) into dashboards.

Optimization Models: Recommend efficient bike redistribution and maintenance schedules.

Customer Segmentation: Analyze rider groups to design tailored incentives or pricing.
