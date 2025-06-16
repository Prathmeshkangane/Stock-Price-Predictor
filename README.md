📈 Stock Price Predictor
A deep learning-powered web app to forecast stock prices using historical data, built with Streamlit, Keras, and yFinance.

🚀 Demo
Launch the app locally with:

streamlit run app.py
🔍 Overview
This project predicts future stock prices based on historical closing prices using a trained LSTM model. It provides:

📉 Historical data visualization

📊 Moving average trend analysis (MA50 & MA100)

🤖 Deep learning predictions vs. actual prices

🧠 Streamlit interface for easy use

✨ Features
🔎 Fetch real-time stock data via yfinance

📈 Plot 50 & 100-day moving averages

🧠 Predict future stock prices using a trained LSTM model

🎯 Compare predicted vs. actual stock prices

🖥️ Clean and interactive Streamlit UI

🧰 Tech Stack
Category	Tools Used
Frontend	Streamlit
Backend	Python, Keras (TensorFlow), NumPy
Data Source	Yahoo Finance (yfinance)
Visualization	Matplotlib, Streamlit
Model	LSTM (Pre-trained Keras model)
Scaler	scikit-learn MinMaxScaler

📂 Folder Structure
├── app.py                      # Main app file
├── stock_price_prediction.keras  # Pre-trained LSTM model
├── README.md                   # Project README
├── requirements.txt            # Python dependencies

⚙️ Installation
1. Clone the repository
git clone https://github.com/Prathmeshkangane/Stock-Price-Predictor.git
cd Stock-Price-Predictor
2. Create a virtual environment
python -m venv .venv
.\.venv\Scripts\activate  # For Windows
3. Install dependencies
pip install -r requirements.txt
▶️ Run the App
streamlit run app.py
Open the link shown in the terminal, usually:
http://localhost:8501

