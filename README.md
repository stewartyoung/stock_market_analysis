# stock_market_analysis
Analysis of stock market data using a jupyter notebook

## Requirements
Before running, ensure you have the following packages installed in your environemnt so that stocker can be used:
* pip install -U quandl numpy pandas fbprophet matplotlib pytrends pystan plotly  
***or***
* conda install quandl numpy pandas matplotlib pystan 
* pip install fbprophet pytrends plotly 

## Stocker Methods
* init: Retrieve financial data from quandl, and assign parameters
* handle_dates: Converts dates into correct format so that the data can be converted into a pandas dataframe
* make_df: Makes the data frame with specific start and end dates
* plot_stock: Makes basic plots and basic statistics
* reset_plot: Resets plotting parameters to alolow future plotting from a clean slate
* resample: Linearly interpolates prices on the weekends
* remove_weekends: Self explanatory
* buy_and_hold: Caluclate and plot profit from buying and holding shares for a specific date range
* create_prophet_model: Self-explanatory
* evaluate_prediction: 
* retrieve_google_trends: for the given ticker, what was the trends in google search history? (There's currently a problem with this)
* changepoint_date_analysis:
* predict_future price: predict future price for a given range of days
* changepoint_prior_validation:
