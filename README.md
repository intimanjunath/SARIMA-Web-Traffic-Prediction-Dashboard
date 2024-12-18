# 📊 **SARIMA Web Traffic Prediction Dashboard**

**Hosted on Hugging Face Spaces**: [Web Traffic Prediction](https://huggingface.co/spaces/manjunathainti/webtraffic)

---

## 📜 **Project Overview**

This project provides an **interactive dashboard** for forecasting **web traffic** using the **SARIMA** (Seasonal AutoRegressive Integrated Moving Average) model. The dashboard visualizes actual traffic trends, predicts future sessions, and displays key performance metrics.

---

## 🌟 **Features**

- **SARIMA Forecasting**:
  - Predicts web traffic for the next **24–48 hours**.
  - Visualizes **actual traffic vs predicted traffic**.

- **Interactive Gradio Dashboard**:
  - User-friendly web interface.
  - Dynamic generation of predictions and performance metrics.

- **Performance Metrics**:
  - Displays **Mean Absolute Error (MAE)** and **Root Mean Squared Error (RMSE)** for easy model evaluation.

- **Visualizations**:
  - Actual vs Predicted Traffic.
  - Residual Analysis.
  - Anomaly Detection.

---

## 🚀 **Live Demo**

Access the project here:  
👉 [SARIMA Web Traffic Prediction](https://huggingface.co/spaces/manjunathainti/webtraffic)

---

## 📊 **Performance Metrics**

The model's performance on test data:

| **Metric**                   | **Value**           |
|-----------------------------|--------------------|
| **Mean Absolute Error (MAE)**| **1,038,700,035.95** |
| **Root Mean Squared Error (RMSE)** | **1,278,503,081.11** |

---

## 📈 **CRISP-DM Methodology**

This project follows the **CRISP-DM** methodology for a structured approach to time-series forecasting.

### 1️⃣ **Business Understanding**
   - **Goal**: Forecast web traffic sessions for decision-making and anomaly detection.
   - **Objective**: Build an interactive tool to predict traffic trends and measure model performance.

### 2️⃣ **Data Understanding**
   - **Dataset**: `webtraffic.csv`
   - **Exploration**:
     - Trend analysis (daily, weekly patterns).
     - Histograms, boxplots, and rolling averages.
     - Checked for missing values and anomalies.

### 3️⃣ **Data Preparation**
   - Converted `Hour Index` into `Datetime` for time-series analysis.
   - Engineered features:
     - Rolling statistics (6H, 24H, 7D rolling means).
     - Lag features for historical dependency.
     - Time-based features: `Hour`, `Day`, `DayOfWeek`, `IsWeekend`.
   - Handled missing values using **backfilling** and **forward-filling**.

### 4️⃣ **Modeling**
   - **SARIMA**:
     - Optimized SARIMA parameters using `auto_arima`.
     - Generated hourly forecasts.
   - **LSTM (Optional)**:
     - Scaled and reshaped data for LSTM modeling.
   - **Visualizations**:
     - Actual vs Predicted Plots.
     - Anomaly detection plots using rolling statistics.

### 5️⃣ **Evaluation**
   - **Performance Metrics**:
     - MAE: `1,038,700,035.95`
     - RMSE: `1,278,503,081.11`
   - Residual Analysis:
     - ACF plots to check autocorrelation.
     - Highlighted anomalies using threshold-based techniques.

### 6️⃣ **Deployment**
   - **Gradio Dashboard**:
     - Deployed locally and on Hugging Face Spaces.
     - Interactive dashboard for SARIMA predictions and metrics.

---

## 🛠️ **Technologies Used**

- **Python**: Core programming language.  
- **Gradio**: Interactive dashboard development.  
- **Statsmodels**: For SARIMA time series modeling.  
- **Pandas**: Data manipulation and preprocessing.  
- **Matplotlib & Seaborn**: Visualization libraries.  
- **Scikit-learn**: Performance evaluation metrics.  

---

## 🧰 **Setup Instructions**

### **1. Clone the Repository**
```bash
git clone https://huggingface.co/spaces/manjunathainti/webtraffic.git
cd webtraffic
