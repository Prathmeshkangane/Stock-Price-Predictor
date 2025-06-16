📈 Stock Price Prediction Web App
This is a Streamlit-based web application that allows users to predict stock closing prices using a deep learning model trained on historical data. The app leverages yFinance for data collection, Keras for prediction, and Matplotlib for visualization.

🚀 Features
📊 Live Data Input – Fetch stock price data for any ticker using Yahoo Finance

🧠 LSTM Deep Learning Model – Predicts future stock prices based on historical data

📉 Rolling Averages – Visualizes 50-day and 100-day moving averages

📈 Actual vs Predicted Chart – Compare real and predicted stock prices

🖥️ Interactive UI – Built with Streamlit for easy user interaction

🧪 Tech Stack
Python

Streamlit

Keras (TensorFlow backend)

yFinance

Pandas & NumPy

Matplotlib

scikit-learn

🛠️ How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/stock-price-predictor.git
cd stock-price-predictor
Create a virtual environment:

bash
Copy
Edit
python -m venv .venv
.\.venv\Scripts\activate  # For Windows
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the app:

bash
Copy
Edit
python -m streamlit run app.py
📂 Folder Structure
bash
Copy
Edit
├── app.py                  # Main Streamlit application
├── stock_price_prediction.keras  # Pre-trained LSTM model
├── requirements.txt        # All required Python libraries
🧠 Model Info
The model is trained using an LSTM neural network on the stock's historical closing prices. The data is preprocessed with MinMaxScaler, and the model takes sequences of the last 100 days to predict the next closing price.

📸 App Preview
(Add screenshots or a screen recording of your app here)

📌 To Do
Add more technical indicators (RSI, MACD)

Enable date range selection from UI

Deploy to Streamlit Cloud or Hugging Face Spaces# Stock-Price-Predictor
