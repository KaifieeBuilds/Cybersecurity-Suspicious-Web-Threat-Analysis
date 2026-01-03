# Cybersecurity: Suspicious Web Threat Interactions

## Project Overview
This project analyzes web traffic logs collected from a cloud environment to
identify suspicious and potentially malicious web interactions. Data analytics
and machine learning techniques are used to detect anomalies and classify
suspicious activities.

## Objectives
- Analyze web traffic behavior and patterns
- Detect anomalous and suspicious interactions
- Identify risky traffic based on bytes, protocols, and regions
- Apply machine learning for cybersecurity threat detection

## Dataset
- Source: AWS CloudWatch Web Traffic Logs
- Type: Web server traffic data
- Records: ~280+
- Domain: Cybersecurity Analytics

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- VS Code

## Analysis Performed
- Data cleaning and preprocessing
- Feature engineering (session duration, packet size)
- Exploratory Data Analysis (traffic volume, protocol usage, country analysis)
- Anomaly detection using Isolation Forest
- Classification using Random Forest

## Model Performance
- Anomaly detection successfully identified unusual traffic patterns
- Classification model achieved high accuracy in detecting suspicious activity

## Files in This Repository
- `cybersecurity_threat_analysis.ipynb` – Complete analysis and ML models


## Conclusion
The project demonstrates how data analytics and machine learning can be effectively
used in cybersecurity to detect suspicious web threats and enhance system security.
