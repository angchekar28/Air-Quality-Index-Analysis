# 📌 Air Quality Index Data Analysis

## 📝 Project Overview
This project analyzes air quality index (AQI) data to understand pollution trends, seasonal variations, and key contributors affecting air quality. Through data visualization and statistical analysis, we gain insights into air pollution levels across different regions.

## 📊 Dataset
- **Source:** Publicly available air quality dataset
- **Columns:**
  - `Date`: Timestamp of data collection
  - `Location`: Monitoring station
  - `PM2.5`, `PM10`, `NO2`, `SO2`, `CO`, `O3`: Pollutant concentrations
  - `AQI`: Air Quality Index value
  - `Category`: Air quality classification (Good, Moderate, Poor, etc.)

## ⚙️ Methodology
1. **Data Preprocessing**
   - Handling missing values
   - Data type conversions
   - Feature engineering for time-series analysis

2. **Exploratory Data Analysis (EDA)**
   - Distribution of pollutants
   - Monthly and yearly AQI trends
   - Seasonal variations in air quality

3. **Data Visualization**
   - Line charts for AQI trends
   - Heatmaps for correlation analysis
   - Bar charts for pollution levels by location

4. **Insights & Findings**
   - Identification of high-pollution regions
   - Correlation between pollutants and AQI
   - Effect of seasons on air quality

## 🛠️ Installation & Usage
```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn

# Clone the repository
git clone <repo_url>
cd <repo_folder>

# Open Jupyter Notebook
jupyter notebook air-quality-index-data-analysis.ipynb
```

## Conclusion:
- This project helps in understanding how air pollution varies over time and space.
- The insights can guide policymakers in making data-driven decisions for environmental improvement.
