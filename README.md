# stock-prediction-model
"A stock prediction model trained on historical data using Python and machine learning algorithms."

1. Objective
To predict or classify stock market behavior using historical data and multiple machine learning models.

2. Data Collection
Library: yfinance

Function: get_hist_data(ticker, start, end, interval)

Data Fetched:
->Open, High, Low, Close prices

->Volume

->Date range and interval-based data

3. Database Integration
Tool: MongoDB via pymongo

Functionality:

->Insert historical data into MongoDB

->Retrieve and display stored data

->Enable reuse of data without re-fetching

4. Data Preprocessing
Steps Include:

->Cleaning missing or irrelevant values

->Feature engineering (optional)

->Normalization or scaling (if applicable)

->Splitting into training and testing datasets

5. Machine Learning Models Used
   
The notebook implements and compares the performance of multiple models:

Model	Purpose	Library

->K-Nearest Neighbors (KNN)	purpose -Classification	library-scikit-learn

->Linear Regression	Regression / purpose-trend prediction	library-scikit-learn

->Decision Tree	purpose-Classification or regression	library-scikit-learn

Each model is trained using the historical stock data and evaluated using standard metrics like accuracy or RMSE.

6. Visualization and Output
   
->Display of data fetched from MongoDB in tabular format.

->plotting stock trends or model predictions (if included).

8. Dependencies
   
->pip install yfinance pandas scikit-learn pymongo

10. Applications
    
->Stock market trend prediction

->Financial forecasting and modeling

->Educational demo for ML + database integration
