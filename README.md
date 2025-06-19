# GenAI-Product-MLModelMonitoring-Airflow-Docker
<H2><B> Title </B></H2> ML Model Monitoring using Airflow and Docker


<H2><B> Description </B></H2> In this project, we will build an end-to-end pipeline to monitor any changes in the
model's predictive power or degradation of data, commonly known as Model and Drift
Monitoring. The model is built to classify whether or not a loan is to be given or rejected
based on data fetched from PostgreSQL. This project also demonstrates the
orchestration of ML pipelines using Docker and Airflow.

<br>
<U>AIM: </U> 
    1. To fetch the data from the PostgreSQL server
    2. To Build a Loan Eligibility classification mode that predicts whether the loan is to
    be given or refused
    3. To monitor Concept, Data, and Model drift
    4. Orchestrate monitoring pipeline with Airflow
<H2><B> Approach </B></H2>
1. Extracting Data from PostgreSQL
2. Data Preprocessing
  a. Train-Test split
  b. Encoding Categorical Variables
  c. Imputing Missing Values
  d. Rescaling the Data
  e. Feature Engineering
3. Model Training and Evaluation
  a. Random Forest
  b. Gradient Boosting
4. Model Monitoring
  a. Concept Drift
  b. Data Drift
  c. Model Drift
5. Orchestration with Airflow

# Code Structure
