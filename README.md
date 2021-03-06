# lstm-stock-predictions
This program is a Jupyter Notebook script that takes a user input for a stock symbol
(ex: AAPL - Apple, TSLA - Tesla) and generates an LSTM Neural Network prediction based on
the close prices in the last 5 years. It also generates its predicted price for the day after
the program is run.

# Installation and run guide
## Prerequisites
### Install the latest version of Anaconda
### Python 3.10 with the following libraries: 
- NumPy
- Pandas
- Pandas_datareader 
- Sklearn
- Tensorflow 
- Keras
- Matplotlib
- default Python libraries

## Simple console command to install all libraries
	pip3 install numpy pandas pandas_datareader sklearn tensorflow keras matplotlib
## Steps to run
1. Install the prerequisite Applications and Libraries
	- a. To install libraries open cmd and type: pip install library_name
		- i. Examples
			- 1. pip3 install numpy
			- 2. pip3 install pandas
			- 3. etc...
2. Download and extract LSTM_Stock_Predictions-main.zip into directory application will run from
3. Open cmd and type: conda activate
4. Now type: jupyter notebook
5. Navigate file system in jupyter notebook that should open in a browser 
    to the directory you extracted the zip to and go into stock_predictor folder
6. Click on dashboard.ipynb to open the file
7. Run the code cell to run the application
