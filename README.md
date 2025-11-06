# AI-Powered Water Use Efficiency Advisor 💧

This project uses satellite imagery, weather data, and AI models to assess water use efficiency in agriculture and provide irrigation recommendations.

## 🌱 Project Structure
- data_raw/ → Unprocessed satellite and weather data  
- data_processed/ → Cleaned and preprocessed datasets  
- notebooks/ → Jupyter notebooks for data analysis & experiments  
- scripts/ → Automation and data processing scripts  
  - earthengine/ → Google Earth Engine data collection  
  - preprocessing/ → Data cleaning and merging  
  - modeling/ → XGBoost and ML modeling scripts  
- models/ → Saved trained ML models  
- frontend/ → User-facing dashboard (built with Streamlit/React)  
- backend/ → Flask-based API for serving predictions  
- docs/ → Project documentation  

## 💡 Purpose
To create a scalable AI system that leverages satellite and IoT data for optimizing water usage in agriculture.