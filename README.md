# Energy_predictor

feat: add weather-energy analysis project

- Imported and cleaned large weather dataset (2006–2010)  
- Parsed date/time, converted strings like "?" to NaN and cast numeric columns  
- Computed energy consumed (kWh) from active power and time intervals  
- Engineered features (hour, sub-metering, polynomial expansion)  
- Applied scaling, RFE for feature selection, and tuned Lasso regression  
- Documented the pipeline and published code for reproducibility  
  txtfile link : https://www.kaggle.com/datasets/uciml/electric-power-consumption-data-set
