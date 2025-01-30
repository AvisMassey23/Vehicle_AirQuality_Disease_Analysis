
# **Quantifying the Impact of Environmental Factors on Chronic Diseases** 🌍🚗💨

## **Overview**
Air pollution, particularly **PM2.5 emissions from vehicles**, has been linked to severe **chronic diseases** such as asthma, chronic obstructive pulmonary disease (COPD), ischemic heart disease, and stroke. This project analyzes the correlation between **vehicular emissions, air quality, and chronic diseases** using data from multiple sources, including the **U.S. Environmental Protection Agency (EPA)** and **Centers for Disease Control and Prevention (CDC)**.

## **Objective**
This research aims to **quantify the impact of air pollution on public health** by analyzing:
- **Air Quality Index (AQI) trends** from 1999 to 2013.
- **Vehicle registration data** to study emission patterns.
- **Chronic disease prevalence** linked to pollution exposure.
- **Policy implications** for reducing pollution-related health risks.

## **Datasets Used**
We gathered and processed three key datasets:
1. **Air Quality Measures (1999–2013)**: Collected from EPA, detailing AQI levels across U.S. states.
2. **Chronic Disease Data (2013)**: Data from CDC, highlighting asthma, COPD, ischemic heart disease, and stroke cases.
3. **Vehicle Registrations (1900–2020)**: Dataset showing the distribution and growth of vehicle emissions over time.

## **Methodology**
- **Data Collection**: Retrieved data from APIs in **CSV** and **JSON** formats.
- **Data Processing**: Cleaned, normalized, and merged datasets using **Python (Pandas, NumPy)**.
- **Database Management**: Stored in **MongoDB (NoSQL)** and **PostgreSQL (SQL)** for structured querying.
- **Analysis & Visualization**:
  - Correlation between **AQI levels and chronic diseases**.
  - Trends in **vehicle registration and emission contributions**.
  - **State-wise impact** of pollution on public health.
  - Visualized findings using **Plotly, Dash, and Matplotlib**.

## **Key Findings**
🚗 **States with the highest AQI levels**—Pennsylvania, West Virginia, Georgia—showed **higher chronic disease prevalence**.  
🌡️ **Vehicle emissions** were a major contributor to PM2.5 levels, increasing respiratory risks.  
💔 **Heart disease & stroke rates** were significantly correlated with poor air quality.  
📉 **States with emission control policies (e.g., California) had lower AQI-related deaths**, highlighting the importance of regulation.  

## **Installation & Usage**
1. Clone the repository:
   ```bash
   git clone https://github.com/avismassey23/Vehicle_AirQuality_Disease_Analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run data processing scripts:
   ```bash
   python preprocess_data.py
   ```
4. Visualize findings:
   ```bash
   python app.py
   ```
