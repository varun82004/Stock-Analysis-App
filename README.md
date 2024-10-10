### 📈 Stock Analysis Tool

Overview
The Stock Analysis Tool is a web application built using Streamlit, allowing users to analyze stock trends and indicators. The application fetches historical stock data from Yahoo Finance and calculates various technical indicators such as Moving Averages (SMA, EMA), Relative Strength Index (RSI), Moving Average Convergence Divergence (MACD), Bollinger Bands, and Average True Range (ATR). Users can visualize these indicators interactively using Plotly.

🛠 Requirements
1) Python 3.x
2) Required libraries (install via requirements.txt):

   -> pandas

   ->numpy

   ->yfinance

   ->plotly

   ->streamlit

### Features:
->Download Stock Data: Fetches historical stock data using the ticker symbol.

->Technical Indicators: Calculates and visualizes SMA, EMA, RSI, MACD, Bollinger Bands, and ATR.

->Interactive Plots: Utilizes Plotly for zoomable and hoverable charts for in-depth analysis.

->User-Friendly Interface: Streamlit provides an intuitive interface for inputting stock ticker symbols and date ranges.

### 🚀 Installation
To run this application, you'll need to have Python installed. Follow these steps to set up your environment:

1) Clone the repository:
   git clone https://github.com/varun82004/stock-analysis-tool.git
   cd stock-analysis-tool


3) Create a virtual environment (optional but recommended):
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

4) Install the required packages:
   pip install pandas numpy yfinance plotly streamlit

5) Run the application:
   streamlit run stock_analysis.py

6) Open your browser:
   After running the command, a link will be provided in the terminal. Open it in your web browser.




Input Parameters:

->Enter the stock ticker symbol (e.g., AAPL for Apple Inc.).

->Select the start and end dates for the analysis.

->Specify the window for SMA and EMA calculations.

->Analyze: Click the "Analyze" button to fetch the data and visualize the stock trends along with the technical indicators.

### Technical Indicators Used
-> Moving Average (SMA and EMA)
   Simple Moving Average (SMA) and Exponential Moving Average (EMA) are calculated to help identify trends.

-> Relative Strength Index (RSI)
   RSI is calculated to indicate overbought or oversold conditions.

-> Moving Average Convergence Divergence (MACD)
   MACD is plotted along with its signal line for trend analysis.

-> Bollinger Bands
   Bollinger Bands help visualize price volatility.

-> Average True Range (ATR)
   ATR is used to measure market volatility.

### 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

### 🤝 Contributing
We welcome contributions to enhance the Stock Analysis Tool. To contribute:
1) Fork this repository.
2) Create a new branch (git checkout -b feature/your-feature).
3) Commit your changes (git commit -m 'Add your feature').
4) Push to the branch (git push origin feature/your-feature).
5) Open a pull request.

👤 Contact
For any questions or suggestions, please contact varunsadhithya@gmail.com.
