#  AirPassengers Forecasting with LSTM

This project builds a **time series forecasting model** using an **LSTM (Long Short-Term Memory)** neural network in **PyTorch** to predict the number of airline passengers based on historical data.

---

## Project Overview

- **Dataset:** [AirPassengers.csv](https://datamarket.com/data/set/22u3/airline-passenger-monthly-total-international-us-carriers-jan-1949-dec-1960) (Monthly total of international airline passengers, 1949–1960)
- **Goal:** Predict future passenger numbers based on past patterns.
- **Model:** LSTM Neural Network.
- **Framework:** PyTorch.

---

##  How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/airpassengers-lstm.git
   cd airpassengers-lstm
   ```

2. **Install the required libraries**
   ```bash
   pip install pandas numpy matplotlib scikit-learn torch
   ```

3. **Run the script**
   ```bash
   python lstm_airpassengers.py
   ```

4. **Visualize**
   - The script will plot actual vs. predicted passenger numbers to evaluate performance.

---

##  Project Structure

- `AirPassengers.csv` : Historical dataset.
- `lstm_airpassengers.py` : Main script to train, predict, and visualize.
- `README.md` : Project documentation.

---

## Model Highlights

- **Preprocessing:** Data normalization using `MinMaxScaler`.
- **Sequence Building:** 12 months input → 1 month prediction.
- **Model:** 1 LSTM layer + 1 Linear layer.
- **Optimizer:** Adam.
- **Loss Function:** Mean Squared Error (MSE).

---

## Future Work

- Predict multiple months ahead.
- Hyperparameter tuning for better accuracy.
- Save model checkpoints and reload for production use.
- Deploy as a web application using Streamlit or FastAPI.

---

## 🤝 Contributions

Pull requests, suggestions, and ideas for improvement are welcome!  
Let’s build and grow together 🚀
