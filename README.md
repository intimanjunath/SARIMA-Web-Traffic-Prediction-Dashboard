# 📊 **SARIMA Web Traffic Prediction Dashboard**

**Hosted on Hugging Face Spaces**: [Web Traffic Prediction](https://huggingface.co/spaces/manjunathainti/webtraffic)

---

## 📜 **Project Overview**

This project provides an **interactive dashboard** for forecasting **web traffic** using the **SARIMA** (Seasonal AutoRegressive Integrated Moving Average) model. The dashboard visualizes actual traffic trends and predicts future sessions while displaying key performance metrics.

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
