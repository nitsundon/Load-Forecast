State Power Demand Forecasting using SCADA Data

Overview

This repository contains a Python-based implementation for short-term power demand (load) forecasting for a State using SCADA data. The model processes raw SCADA data, handles missing values and anomalies, and integrates Energy Meter data to enhance accuracy. The cleaned and corrected data is then used to predict state demand using machine learning techniques.

Methodology

SCADA Data Preprocessing

Identifies and removes missing values and spikes from SCADA data.

Ensures data consistency for accurate forecasting.

Energy Meter Data Integration

Energy Meter data is used to address discrepancies in SCADA data.

An XGBoost model is trained to predict missing SCADA data using Energy Meter readings.

Load Forecasting

The corrected SCADA data is used as input for short-term load forecasting.

Machine learning techniques, including XGBoost, are leveraged for accurate predictions.



