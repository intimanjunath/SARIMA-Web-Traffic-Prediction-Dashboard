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

## 🖥️ **Screenshots**

### **1. SARIMA Predictions vs Actual Traffic**  
![SARIMA Predictions](<img width="1386" alt="Screenshot 2024-12-17 at 7 15 27 PM" src="https://github.com/user-attachments/assets/5173bc56-dcbe-454a-b539-ea69e0e7b48d" />
)

### **2. SARIMA Model Metrics**  
![SARIMA Metrics](<img width="1212" alt="Screenshot 2024-12-17 at 7 16 23 PM" src="https://github.com/user-attachments/assets/6420ea53-7ba2-4fea-94fa-5cea3edeba84" />
)

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
