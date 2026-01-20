Aadhaar Service Stress Index ASSI

Project Overview
Aadhaar Service Stress Index ASSI is a data driven analytics project that quantifies and forecasts enrolment related service pressure across Indian states and districts.
The project introduces a composite stress index that helps identify where and when enrolment infrastructure is likely to face overload, enabling proactive planning instead of reactive response.
This project was developed for the UIDAI Data Hackathon 2026 and is designed as a real world governance analytics use case.

Why This Project Matters
Most enrolment analysis focuses only on historical volume.

This project answers a more important question:
Which regions are likely to face service stress next and why
By combining demographic composition growth trends volatility and anomaly detection the project provides a practical decision support framework rather than simple reporting.

Key Features
1. Composite stress index on a 0 to 100 scale
2. Demographic aware service load modeling
3. Monthly district level stress analysis
4. Detection of sudden enrolment surges
5. Prediction of future high stress regions
6. Interpretable and policy oriented design

Dataset Summary
1. Anonymised Aadhaar enrolment data
2. Final dataset size 212595 records
3. Granularity:
   State
   District
   Pincode
   Date
4. Age groups
   0 to 5
   5 to 17
   18 and above
No personal or sensitive information is used.

Methodology At a Glance:
1. Consolidated enrolment data from multiple files
2. Cleaned and standardized temporal data
3. Engineered stress indicators
   Total enrolments
   Age weighted enrolment load
   Growth rate
   Volatility
   Anomaly detection
4. Aggregated data at monthly district level
5. Constructed the Aadhaar Service Stress Index ASSI
6. Classified regions into Low Medium and High stress
7. Forecasted future stress using machine learning

Aadhaar Service Stress Index ASSI
ASSI is a weighted composite score where:
   1. Low values indicate stable enrolment demand
   2. High values indicate potential service overload
The index is designed to be:
   1. Easy to interpret
   2. Scalable across regions
   3. Useful for administrative planning

Machine Learning Component:
A regression based machine learning model is used to predict future ASSI values using historical stress indicators.
The model enables early identification of regions that may transition into high stress in upcoming periods.

Project Structure
.
├── UIDAI_Hackathon.ipynb     # Data preprocessing and exploratory analysis
├── ASSI_Index.ipynb          # Stress index construction and classification
├── prediction.ipynb          # Forecasting future service stress
├── README.md

Tech Stack:
1. Python
2. Pandas and NumPy
3. Scikit learn
4. Matplotlib and Seaborn
5. Jupyter Notebook

Key Takeaways:
1. Service stress is driven by more than enrolment volume alone
2. Demographic composition significantly impacts operational load
3. Growth rate and volatility are strong early warning signals
4. Composite indices can effectively support governance decisions

Future Enhancements:
1. Integration of Aadhaar update and correction datasets
2. Inclusion of population and migration indicators
3. Real time stress monitoring dashboards
4. Infrastructure and staffing capacity modeling

Author
Varun Mhatre
Engineering Student AI and Data Science
UIDAI Data Hackathon 2026 Project
