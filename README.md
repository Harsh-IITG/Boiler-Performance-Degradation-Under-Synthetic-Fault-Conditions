# Boiler-Performance-Degradation-Under-Synthetic-Fault-Conditions
This project implements a predictive maintenance strategy using artificial intelligence. By continuously analyzing critical operational parameters of the boiler system, the model can detect deviations that may indicate emerging faults or performance degradation.  
This proactive approach enables early intervention, reduces the risk of unexpected failures, and ensures consistent and efficient operation.  
As a result, it supports improved energy efficiency, reduced maintenance costs, and enhanced system reliability in District Heating and Cooling (DHC) networks.

## Project Features

- **Predictive Analytics**: Utilize a Random Forest model for fault prediction.  
- **Visualization**: Generate informative plots for probability distributions and true/false predictions.  
- **Anomaly Detection**: Implement anomaly detection in thermal conductance data.  
- **Flexibility**: Easily configurable for other types of predictive analyses.

## Data Pipeline

- **Data Preprocessing**: The input data undergoes cleaning and normalization.  
- **Model Training**: A Random Forest classifier is trained on pre-processed data.  
- **Prediction**: Model generates probabilities and triggers alerts based on thresholds.  
- **Visualization**: Key metrics are visualized for better interpretability.

## Usage

### Predict Anomalies
- Modify the input dataset or preprocessing steps as needed.  
- Execute the notebook sequentially.  
- Inspect generated plots and prediction results.

### Configurations
- Adjust prediction thresholds in the `alert_trigger` function.  
- Update `fault_var` and other variables to suit your specific use case.

## Plots and Visualizations

- **Probability Distributions**: Visualizes the probability of faults based on thermal conductance.  
- **True/False Alerts**: Plots overlay predictions against actual data to evaluate model performance.



