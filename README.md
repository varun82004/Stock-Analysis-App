Stock Analysis Tool
Overview
The Stock Analysis Tool is a web application built using Streamlit, allowing users to analyze stock trends and indicators. The application fetches historical stock data from Yahoo Finance and calculates various technical indicators such as Moving Averages (SMA, EMA), Relative Strength Index (RSI), Moving Average Convergence Divergence (MACD), Bollinger Bands, and Average True Range (ATR). Users can visualize these indicators interactively using Plotly.

Features
Download Stock Data: Fetches historical stock data using the ticker symbol.
Technical Indicators: Calculates and visualizes SMA, EMA, RSI, MACD, Bollinger Bands, and ATR.
Interactive Plots: Utilizes Plotly for zoomable and hoverable charts for in-depth analysis.
User-Friendly Interface: Streamlit provides an intuitive interface for inputting stock ticker symbols and date ranges.
Installation
To run this application, you'll need to have Python installed. Follow these steps to set up your environment:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/stock-analysis-tool.git
cd stock-analysis-tool
Create a virtual environment (optional but recommended):

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages:

bash
Copy code
pip install pandas numpy yfinance plotly streamlit
Usage
Run the application:

bash
Copy code
streamlit run stock_analysis.py
Open your browser: After running the command, a link will be provided in the terminal. Open it in your web browser.

Input Parameters:

Enter the stock ticker symbol (e.g., AAPL for Apple Inc.).
Select the start and end dates for the analysis.
Specify the window for SMA and EMA calculations.
Analyze: Click the "Analyze" button to fetch the data and visualize the stock trends along with the technical indicators.

Technical Indicators
Moving Average (SMA and EMA)
Simple Moving Average (SMA) and Exponential Moving Average (EMA) are calculated to help identify trends.
Relative Strength Index (RSI)
RSI is calculated to indicate overbought or oversold conditions.
Moving Average Convergence Divergence (MACD)
MACD is plotted along with its signal line for trend analysis.
Bollinger Bands
Bollinger Bands help visualize price volatility.
Average True Range (ATR)
ATR is used to measure market volatility.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contributing
Contributions are welcome! Please feel free to submit a pull request or report issues.

Contact
For any questions or suggestions, please contact Your Name.
