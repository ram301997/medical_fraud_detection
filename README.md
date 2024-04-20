# Medical Provider Fraud Prediction

## Introduction
Healthcare fraud is a significant issue that costs billions of dollars annually. It encompasses fraudulent billing practices by some medical providers, leading to increased healthcare costs and damaging the reputation of honest practitioners. Addressing this issue is vital for sustaining trust in the healthcare system.

## Objective
The goal of this project is to predict fraudulent activities by medical providers to prevent financial losses and maintain the integrity of healthcare services.

## Data Overview
The dataset used in this project is provided by the Centers for Medicare & Medicaid Services (CMS), comprising information on hospital visits (Inpatient Data), outpatient services (Outpatient Data), and beneficiary details (Beneficiary Details Data).

## Methodology
The approach includes:

- **Data Preparation**: Merging hospital admission records with outpatient visits and aligning beneficiary information, culminating in a dataset enriched with provider details.

- **Data Preprocessing**: Calculating patient ages, analyzing claim times, normalizing data, selecting relevant features, and encoding categorical data.

- **Exploratory Data Analysis (EDA)**: Investigating top procedures and diagnosis codes, assessing the impact of chronic conditions, and analyzing hospital stay durations in relation to fraud indicators.

- **Model Building**: Implementing and evaluating several machine learning and deep learning models such as Logistic Regression, Decision Trees, Random Forest, CNN, LSTM+AE, and RNN.

## Results
The models' performance was assessed using Area Under Curve (AUC) scores, with the Decision Tree model showing the most promise. Deep learning models, particularly LSTM with AutoEncoder, demonstrated potential in recognizing complex fraud patterns.

## Conclusion and Future Work
Findings suggest that reimbursements and diagnosis codes are strong indicators of potential fraud. Future work will involve collaboration with healthcare professionals to identify new types of fraud, experimenting with data encoding methods, enriching datasets, developing instant fraud alert systems, and training models to distinguish between fraud and legitimate billing anomalies.

## Contributors
- [Leela Sai Rushendra Varma Mudunuri](https://www.linkedin.com/in/leela-sai-rushendra-varma-mudunuri-55b5a7215/)
- [Ramachandra Reddy Kolakalapudi](https://www.linkedin.com/in/ramachandra-reddy-16babb159/)

## Code Repository
The code for this project can be found on GitHub: [Medical Fraud Detection Project Repository](https://github.com/ram301997/medical_fraud_detection)

---

© 2024 Medical Fraud Detection Project Team
