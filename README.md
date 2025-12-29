# Sentinel AI
## Confidence-Aware and Equity-Focused Disease Outbreak Early Warning System

---

## Overview
Sentinel AI is an AI-powered epidemiological surveillance system designed to detect early signals of infectious disease outbreaks and support proactive public health decision-making. The system integrates clinical, pharmaceutical, environmental, and public health data to predict outbreak risks, identify hotspots, and prioritize vulnerable regions before outbreaks escalate.

The project emphasizes interpretability, reliability, and equity to ensure that AI-driven insights are trustworthy and actionable for real-world public health use.

---

## Problem Statement
India experiences frequent outbreaks of infectious diseases such as dengue, malaria, and COVID-19. These outbreaks are often detected only after widespread transmission has occurred, leading to overwhelmed healthcare systems and preventable loss of life. Although large volumes of health-related data exist, the lack of integration and predictive analytics limits early intervention.

---

## Solution Approach
Sentinel AI functions as a sentinel surveillance platform that continuously monitors multi-source data streams and applies machine learning techniques to generate early warnings and regional risk assessments. The system combines predictive modeling with confidence estimation and healthcare equity analysis to enable informed, fair, and proactive public health responses.

---

## Datasets
All datasets used in this project are **synthetic, anonymized, and self-generated**, created solely for ideathon demonstration and research purposes. Each dataset contains **5,000 rows**.

### 1. Clinical Data (`clinical_data.csv`)
Aggregated hospital and clinic visit trends.
- visit_date  
- district  
- facility_type  
- total_visits  
- fever_cases  
- cough_cases  
- respiratory_cases  
- admission_count  
- icu_admissions  

### 2. Pharmaceutical Data (`pharmaceutical_data.csv`)
Pharmacy medicine sales and demand indicators.
- sale_date  
- district  
- medicine_category  
- medicine_name  
- units_sold  
- daily_sales_growth  
- demand_spike_flag  

### 3. Environmental Data (`environmental_data.csv`)
Climate and weather indicators influencing disease spread.
- date  
- district  
- avg_temperature  
- rainfall  
- humidity  
- temperature_deviation  
- rainfall_deviation  

### 4. Public Health Data (`public_health_data.csv`)
Historical outbreak and government health records.
- report_date  
- district  
- disease_name  
- confirmed_cases  
- death_count  
- outbreak_status  
- weekly_case_growth  

> No real patient-identifiable or confidential healthcare data is used.

---

## System Workflow
1. Data ingestion from clinical, pharmaceutical, environmental, and public health datasets  
2. Data preprocessing, normalization, and anonymization  
3. Feature engineering (growth rates, trends, correlations, vulnerability indicators)  
4. Model training and analysis  
5. Risk classification with confidence estimation  
6. Equity-aware prioritization and early alert generation  

---

## AI & Data Science Techniques Used
- Linear Regression for trend and correlation analysis  
- K-Means Clustering for hotspot identification  
- Time-Series Forecasting (Moving Averages, LSTM) for short-term outbreak prediction  
- Anomaly Detection for identifying sudden spikes  
- Random Forest Classification for regional risk categorization  
- Ensemble Learning for confidence-aware risk scoring  

---

## Key Innovations
### Confidence-Aware Risk Scoring
Each regional risk prediction includes a confidence score based on agreement across multiple models, improving trust and decision reliability.

### Equity-Aware Health Risk Index
A composite index that combines disease spread risk with healthcare vulnerability indicators to ensure underserved regions receive timely attention.

---

## Expected Impact
- Early identification of outbreak-prone regions  
- Reduced healthcare system overload  
- Improved preparedness in rural and vulnerable areas  
- Transparent and reliable AI-assisted decision-making  
- Reduction in preventable loss of life  

---

## Scalability & Feasibility
- Built using lightweight and interpretable models  
- Scalable from district-level to national-level deployment  
- Supports multi-disease monitoring and seasonal trends  
- Suitable for real-time dashboards and continuous updates  

---

## Vision
**Data + AI → Early Detection → Preventive Government Action → Lives Saved**

Sentinel AI aims to enable predictive, transparent, and equitable public health surveillance.


