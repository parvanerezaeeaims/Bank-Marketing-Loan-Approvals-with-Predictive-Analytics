# Predicting Term Deposit Subscriptions on Bank Marketing Data

## Overview
This project focuses on predicting whether a bank client will subscribe to a term deposit based on historical marketing data. Using machine learning, we analyze customer attributes and past marketing campaign outcomes to improve decision-making and optimize future campaigns.

## Features
- **Target Variable:** `subscription` – Indicates if the client subscribed to a term deposit (`yes` or `no`).
- **Data Analysis:** Identify key factors influencing client subscription decisions.
- **Predictive Modeling:** Build and evaluate machine learning models to predict subscription likelihood.
- **Marketing Insights:** Provide actionable recommendations for campaign optimization.

## Dataset
The dataset consists of the following attributes:

- **age:** Age of the client (numeric)  
- **job:** Type of job (categorical: admin, blue-collar, entrepreneur, etc.)  
- **marital:** Marital status (categorical: single, married, divorced)  
- **education:** Level of education (categorical: primary, secondary, tertiary, etc.)  
- **credit_default:** Whether the client has credit in default (binary: yes, no)  
- **housing:** Whether the client has a housing loan (binary: yes, no)  
- **loan:** Whether the client has a personal loan (binary: yes, no)  
- **contact:** Type of communication (categorical: cellular, telephone)  
- **month:** Month of last contact (categorical)  
- **day_of_week:** Day of the week of last contact (categorical)  
- **duration:** Duration of the last contact in seconds (numeric)  
- **campaign:** Number of contacts performed during this campaign (numeric)  
- **pdays:** Number of days since the client was last contacted from a previous campaign (numeric; -1 means client was not previously contacted)  
- **previous:** Number of contacts performed before this campaign for this client (numeric)  
- **poutcome:** Outcome of the previous marketing campaign (categorical: success, failure, other)  
- **subscription:** Indicates if the client subscribed to a term deposit (binary: yes, no) - target variable  

### Note
Ensure the dataset complies with privacy and ethical standards.

## Installation

### Prerequisites
- Python 3.8+
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/parvanerezaeeaims/Predicting-Term-Deposit-Subscriptions-with-Bank-Marketing-Data.git
