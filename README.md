
# Analysis of Particulate Matter (PM 10 & 2.5) Levels in Delhi

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![Library](https://img.shields.io/badge/Library-Pandas%20%7C%20Seaborn%20%7C%20Plotly-orange) ![Status](https://img.shields.io/badge/Status-Completed-green) ![License](https://img.shields.io/badge/License-MIT-blue)

## 📄 Project Overview
This project provides a data-driven analysis of air pollution trends in Delhi, specifically focusing on Particulate Matter (PM 10 and PM 2.5). The analysis spans historical data from **January 2017 to November 2022**, exploring seasonal variations, meteorological correlations, and comparative trends against other major Indian cities.

**[📄 View the Full Analysis PDF Here](https://github.com/sameerhussai230/Analysis-of-PM-10-and-2.5-Levels_in_Delhi/blob/main/Analysis%20of%20PM%20Levels%20in%20Delhi.pdf)**

---

## 🎥 Visual Demo: Multi-City Pollution Trends
Below is a **Bar Chart Race** visualizing the fluctuating levels of PM 10 across 5 major Indian cities (Delhi, Ahmedabad, Hyderabad, Kolkata, Mumbai) from June 2019 to November 2022.

![Analysis of Particulate Matter GIF](https://github.com/sameerhussai230/Analysis-of-PM-10-and-2.5-Levels_in_Delhi/blob/main/Analysis_of_Particulate_Matter.gif?raw=true)

---

## 📊 Key Features & Analysis

The analysis is performed using a Jupyter Notebook and exported as a comprehensive report. Key components include:

### 1. Data Cleaning & Preparation
- Handling missing values and nulls from CPCB datasets.
- Resampling hourly data into Daily and Monthly averages.
- Type conversion for meteorological parameters (RH, WS, WD, Temp).

### 2. Multi-City Comparison
- **Visualization:** Animated Bar Chart Race (seen above).
- **Scope:** Comparison of PM levels across 5 major cities to understand regional pollution disparities.

### 3. Trend Analysis & Seasonality
- **Year-wise Box Plots:** Illustrates the variation and median levels of PM 2.5 over the years.
    - *Insight:* Box plots reveal outliers and the range of pollution concentration (typically 90-110 median).
- **Seasonal Point Plots:**
    - *Insight:* Clear cluster of low pollution points during **Monsoon months (June-August)** due to rain dispersion.
    - *Insight:* High pollution clusters in **Winter (Dec-Jan)** due to atmospheric inversion.

### 4. Correlation Study (Heatmap)
- **Visualization:** Correlation Matrix Heatmap.
- **Parameters:** PM10, PM2.5, Relative Humidity (RH), Wind Speed (WS), Temperature.
- **Key Findings:**
    - Strong **negative correlation** (-0.34) between Temperature and PM levels.
    - **Negative correlation** between Wind Speed and PM levels (High wind speed helps disperse pollutants).

### 5. Wind Speed vs. Particulate Matter
- **Visualization:** Dual-axis chart (Bar + Line graph).
- **Observation:** In months like April/May, despite high temperatures, PM levels can rise if wind speed is low. Conversely, higher wind speeds in July-September correlate with the lowest PM levels.

### 6. Extreme Events
- **Analysis:** Identification of the **"Top 10 Polluted Days of 2022"**.
- **Result:** The most polluted days consistently fall in **November and January**, attributed to the "Winter Inversion" phenomenon where cold air traps pollutants near the surface.

## 🛠️ Technologies Used
- **Python** (Core Language)
- **Pandas & NumPy** (Data Manipulation)
- **Matplotlib & Seaborn** (Static Visualizations, Heatmaps, PairPlots)
- **Plotly & Cufflinks** (Interactive Visualizations)
- **Bar_Chart_Race** (Animated comparisons)

## 📂 Dataset
The data was collected from the **Central Pollution Control Board (CPCB)** website containing air quality data for:
1.  **5 Regions:** June 2019 to Nov 2022.
2.  **Delhi Deep Dive:** Jan 2017 to Nov 2022.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/sameerhussai230/Analysis-of-PM-10-and-2.5-Levels_in_Delhi.git
   ```
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly bar_chart_race
   ```
3. Open the notebook in Jupyter/Colab to view the interactive graphs.

## 📉 Biological & Meteorological Insights
Based on the data analysis, the following conclusions were drawn:
*   **Atmospheric Inversion:** Higher concentrations of PM 10/2.5 are observed in winter because the temperature difference between the ground and the air above is greater, trapping pollutants.
*   **Monsoon Dispersion:** Rain and high wind velocity during the monsoon season (July-Sept) effectively wash away pollutants, resulting in the cleanest air of the year.
