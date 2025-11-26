📈 Time Series Analysis — AirPassengers Dataset
A complete end-to-end statistical time series analysis using Python, Pandas, Statsmodels, and SciPy.
________________________________________
📘 Project Overview
This project performs a detailed Time Series Analysis on the classic AirPassengers dataset, which contains monthly airline passenger totals from 1949 to 1960.
The goal is to understand the behavior, structure, and patterns in the data before applying forecasting models.
This analysis includes:
•	Trend detection
•	Seasonal pattern extraction
•	Stationarity analysis
•	Noise identification
•	Detrending & deseasonalization
•	ACF/PACF analysis
•	Lag correlations
•	Granger causality test
This project demonstrates a complete workflow used in real-world business forecasting and analytics.
________________________________________
🧠 Key Concepts Covered
This project includes every major statistical time series step:
🔹 1. Exploratory Time Series Visualization
•	Line plots
•	Seasonal patterns
•	Trend patterns
•	Two-side shaded view of the series
🔹 2. Decomposition (Additive & Multiplicative)
Using statsmodels.seasonal_decompose:
•	Trend
•	Seasonal
•	Residual
•	Correct period=12 for monthly data
🔹 3. White Noise Analysis
•	Generating and visualizing Gaussian noise
•	Understanding randomness patterns
🔹 4. Detrending
Techniques used:
•	Using SciPy’s least squares detrend
•	Removing Trend component via decomposition
🔹 5. Deseasonalization
•	Removing seasonal component to isolate core signal
🔹 6. Autocorrelation (ACF) & Partial Autocorrelation (PACF)
•	Determine AR/MA orders
•	Identify lag correlation memory
•	Important for ARIMA model building
🔹 7. Lag Plots
•	Visualizing autocorrelation behavior
•	Detecting linear and non-linear structure
🔹 8. Granger Causality Test
•	Tests if one variable can predict another
•	Useful in economics & forecasting pipelines
________________________________________
📂 Project Structure
Time-Series-Analysis/
│
├── AirPassengers.csv               # Dataset (1949–1960)
├── dataset.txt                     # Dataset used for Granger test
├── TimeSeriesAnalysis.ipynb        # Main Jupyter Notebook
├── README.md                       # Project documentation
│
└── images/                         # (Optional) Saved plots
      ├── trend.png
      ├── decomposition_add.png
      ├── decomposition_mul.png
      ├── acf_pacf.png
      ├── lag_plots.png
________________________________________
🛠 Technologies Used
Library	Purpose
Pandas	Data handling & cleaning
NumPy	Numerical operations
Matplotlib & Seaborn	Visualizations
Statsmodels	Decomposition, ACF, PACF
SciPy	Detrending
Python	Core implementation
________________________________________
🧪 Steps in the Analysis
✔ Step 1 — Load & Clean the Data
Convert dates → set Date column as index.
✔ Step 2 — Plot Time Series
Understanding trend & seasonality visually.
✔ Step 3 — Decomposition
Break series into:
•	Trend
•	Seasonality
•	Residual
✔ Step 4 — Noise Analysis
White noise helps compare randomness vs structure.
✔ Step 5 — Detrending
Removing long-term trend to improve stationarity.
✔ Step 6 — Deseasonalization
Remove repeating seasonality patterns.
✔ Step 7 — Autocorrelation
ACF helps understand correlation with past values.
✔ Step 8 — PACF
Used to identify AR terms.
✔ Step 9 — Lag Plots
Shows relationships between observations & their lags.
✔ Step 10 — Granger Causality Test
Tests directional influence between variables.
________________________________________
📊 Insights & Findings
🔹 Strong Upward Trend
Passenger numbers grow consistently every year.
🔹 Clear Monthly Seasonality
Peak travel months repeating annually.
🔹 ACF Shows Long Memory
Indicates strong autocorrelation → useful for ARIMA.
🔹 PACF Reveals AR Order
Specifically for ARIMA/SARIMA modeling.
🔹 Detrended & Deseasonalized Series
Shows underlying core fluctuations.
🔹 Granger Causality
Demonstrates predictive relationship between variables.
________________________________________
🚀 How to Run the Project
Install dependencies:
pip install numpy pandas matplotlib seaborn statsmodels scipy
Run the notebook:
jupyter notebook TimeSeriesAnalysis.ipynb
________________________________________
🎯 Why This Project Is Resume-Ready
This project demonstrates strong knowledge in:
•	Statistical time series analysis
•	Trend & seasonality modeling
•	Stationarity concepts
•	Correlation analysis
•	Noise detection
•	Causality testing
•	Understanding patterns required for forecasting models
This is the exact foundation companies expect for roles like:
•	Data Analyst
•	Data Scientist
•	Machine Learning Engineer
•	Forecasting Analyst
•	Business Intelligence Engineer
________________________________________
💡 Possible Next Steps / Future Work
To extend this project:
•	Fit ARIMA / SARIMA models
•	Use Facebook Prophet for forecasting
•	Use LSTM/GRU for deep learning forecasting
•	Compare forecasting accuracy across models
(If you want, I can build forecasting models for you.)
________________________________________
👨💻 Author
Mirza Naveed Baig
Data Science & Machine Learning | Python | Time Series Analytics
________________________________________
⭐ Support
If you find this work helpful, consider starring ⭐ the repository!

