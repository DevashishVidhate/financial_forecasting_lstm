# Financial Forecasting with LSTM

This project demonstrates how to build a time-series forecasting model for financial data using LSTM (Long Short-Term Memory) neural networks. The model is trained to predict trends in financial data, making it a strong tool for use cases like stock price forecasting or business KPIs.

## 📁 Project Structure

- `Financial_Forecasting.ipynb`: Colab notebook with the full code pipeline
- `starbucks_open_7year.csv`: Sample dataset for forecasting (upload required)
- `requirements.txt`: Python dependencies

## 🧠 Model Architecture

- **Preprocessing**: Missing date handling, duplicate removal, normalization
- **Architecture**: LSTM with dense layers and dropout
- **Evaluation**: MAE, RMSE, and R² metrics

## 📈 Sample Output

- Visuals: Training vs validation loss
- Forecast plots: Predicted vs actual values

## 🚀 How to Run

1. Upload `starbucks_open_7year.csv` in the Colab notebook.
2. Run all cells step by step to train and evaluate the model.
3. Use the final section to visualize forecasts and analyze performance.

## 🔧 Requirements

```bash
pip install -r requirements.txt
