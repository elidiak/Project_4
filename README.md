# Final Project - Team 2
## Predicting Energy Consumption based on Weather Forecast Data
### Team Members: Chris Kellam, Eric Lidiak, Matthew Smith, Molly Fox, Jason Britton
#### DESCRIPTION: 
Create a predictive model based on historical weather and energy consumption data to forecast energy consumption based on weather variables such as minimum, maximum and average temperature, state, and month of year. 

#### RESEARCH QUESTIONS: 
- What types of historical data are available for weather and energy consumption?
- Is weather data a good predictor of energy consumption?
- How do different models’ compare to one another for time-series prediction?

#### DATA AND DELVERY: 
- Each team member took a potential model library (ARIMA, Prophet, Random Forest, LSTM, XGBoost) to compare and contrast the libraries predictive power using the two data sets.
- The weather data began in January 1981 and continued through December 2023. The energy data began in January 2001 and continued through September 2024. We narrowed the scope of the combined data from January 2001 to December 2023. 
- Preprocessing was conducted jointly and individually based on the needs of the various models.

The team used the same features and target to test predictions: 
- Features: tmin, tmax, tavg, year, month, state_Texas
- Target: coal

#### KEY OBSERVATIONS: 
- Weather data serves as a decent predictor of energy consumption, as indicated by the models' predictive capabilities.
- Monthly weather trends reveal that average temperature patterns correlate with energy consumption, highlighting the influence of seasonal changes.
- Weather temperatures—both hot and cold—are likely to impact on future energy consumption, necessitating further analysis to understand their effects.
- Of the models used (ARIMA, Prophet, Random Forest, LSTM, XGBoost), XGBoost performed the best against the dataset. 

Source for usweather_month_1981-2023.csv: https://asmith.ucdavis.edu/data/prism-weather

Source for Total_consumption_for_all_sectors.csv:	https://www.eia.gov/electricity/data/browser/#/topic/2?agg=2,0,1&fuel=f&geo=vvvvvvvvvvvvo&sec=g&linechart=ELEC.CONS_TOT.COW-US-99.M&columnchart=ELEC.CONS_TOT.COW-US-99.M&map=ELEC.CONS_TOT.COW-US-99.M&freq=M&start=200101&end=202409&ctype=columnchart&ltype=pin&columnendpoints=2&columnvalues=1&rtype=s&pin=&rse=0&maptype=0																																																									

