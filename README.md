# 🚀 IBM Applied Data Science Capstone 🚀

## Project Overview
This capstone project focuses on predicting the success of SpaceX Falcon 9 rocket landings to determine launch costs. By analyzing various factors influencing landing outcomes, the project provides insights that could help competitors bid against SpaceX more effectively.

## Project Goals
- Predict whether the Falcon 9 first stage will land successfully.
- Identify key factors influencing landing success.
- Analyze interactions between features to understand success rates.
- Determine optimal operating conditions for successful landings.

## Methodology
1. **Data Collection**  
   - Used SpaceX REST API and web scraping from Wikipedia to gather launch data.
   - Cleaned and processed data to handle missing values and encode categorical features.

2. **Exploratory Data Analysis (EDA)**  
   - Conducted SQL queries to analyze launch sites, payloads, and mission outcomes.
   - Visualized relationships between flight numbers, payload mass, launch sites, and orbit types.

3. **Interactive Visual Analytics**  
   - Created maps with Folium to mark launch sites and success/failure outcomes.
   - Built an interactive dashboard using Plotly Dash to explore payload ranges and success rates.

4. **Machine Learning Prediction**  
   - Applied classification models (Logistic Regression, SVM, Decision Tree, KNN) to predict landing success.
   - Evaluated models using Jaccard Score, F1 Score, and Accuracy.

## Key Findings
- **Best Model**: Decision Tree achieved the highest accuracy (91.11%).
- **Payload Impact**: Lighter payloads correlated with higher success rates.
- **Launch Sites**: KSC LC-39A had the highest success rate among all sites.
- **Orbit Types**: ES-L1, GEO, HEO, and SSO orbits showed a 100% success rate.
- **Temporal Trend**: Success rates improved steadily over the years.

## Repository Structure
- `1_Data_Collection_API.ipynb`: Data collection using SpaceX API.
- `2_Data_Collection_with_Web_Scraping.ipynb`: Web scraping from Wikipedia.
- `3_Data_Wrangling.ipynb`: Data cleaning and preprocessing.
- `4_EDA_with_SQL.ipynb`: SQL-based exploratory analysis.
- `5_EDA_with_Visualization.ipynb`: Data visualization.
- `6_Interactive_Visual_Analytics_with_Folium.ipynb`: Folium map visualizations.
- `7_Machine_Learning_Prediction.ipynb`: Predictive modeling.
- `spacex_dash_app.py`: Plotly Dash interactive dashboard.
