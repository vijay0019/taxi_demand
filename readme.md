# README


### 1. Data Loading

- Load the dataset, convert timestamps to datetime objects, and set the timestamp as the index.

### 2. Temporal Aggregation

- Aggregate demand data into 15-minute intervals for model input.

### 3. Feature Engineering

- Extract temporal features (hour of the day, day of the week) for model input.

### 4. Model Selection and Training

- Trained **XGBOOST** and **ARIMA**
- XGBoost is good for capturing complex relationships.
- ARIMA is good for capturing temporal dependencies.

### 5. Evaluation and Visualizations

- Assess model performance using Mean Absolute Error (MAE) and visualize predictions against actual demand.

## Trends Discovered

- The temporal features (hour of the day, day of the week) play a significant role in taxi demand.