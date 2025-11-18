# Excel – Exploratory Analysis of Stroke Risk Factors
**TL;DR:** TBA	

## Problem
TBA

## Data
- Source: [Stroke Prediction Dataset (by Fedesoriano)](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

## Business Understanding
1. Demographic Risk Factors
  <br> Does gender affect stroke risk?
  <br> Which age groups show the highest stroke incidence?
  <br> Does residence type (urban/rural) differ in stroke likelihood?
2. Medical Conditions
  <br> Is hypertension strongly associated with stroke?
  <br> Is heart disease associated with higher stroke risk?
3. Lifestyle Factors
  <br>  Is smoking status linked to higher stroke rates?
4. Clinical Measurements
  <br> Does BMI have a relationship with stroke incidence?
  <br> Are elevated glucose levels associated with higher stroke risk?
5. Socioeconomic Factors
  <br> Is the patient’s work type related to stroke risk?
    
## Data Understanding 
1. Imported raw CSV
2. Applied text to column
3. Converted dataset to excel table
4. Data Checking (datatype and missing value)

## Data Preparation
1. Remove Duplicates
2. Standardized data types
3. Cleaned data
4. Created calculated columns as needed
5. Loaded cleaned table back to Excel

## Modelling
1. Power Query (ETL Modelling), merge columns/tables to build a clean final table, standardized column names and formats
2. No Power Pivot relationships needed due to single-table model

## Analysis
1. Pivot Table
2. Pivot Chart
3. Slicers for dynamic filtering (gender, residence, work type, age group)

## Visualization
1. KPI cards (Total Patients, Stroke Cases, % Stroke)
2. Breakdown charts by risk factor categories
3. Clean single-page Excel dashboard
