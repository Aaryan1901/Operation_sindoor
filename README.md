# 🛰️ Operation Sindoor | Defense Intelligence Analytics using CNN & Power BI

A multi-stage analytics and machine learning project simulating tactical defense signal analysis for national security use cases. Operation Sindoor is built to process raw intercepted signal data, analyze military aircraft activity, and visualize key mission intelligence metrics in a secure and insightful manner.

---

## 🔍 Project Objective

To detect, monitor, and analyze simulated aerial conflict data—particularly focusing on **India vs Pakistan engagement patterns**—through machine learning modeling and strategic dashboarding. The project combines deep learning techniques for **jet coordination prediction** with advanced **Power BI dashboards** for visual intelligence reporting.

---

## 🧠 Technologies Used

| Layer                  | Tools / Libraries                                      |
|------------------------|--------------------------------------------------------|
| Machine Learning       | TensorFlow, Keras, Scikit-learn, NumPy, Pandas         |
| Model Type             | 1D Convolutional Neural Network (CNN Regression)       |
| Evaluation Metrics     | MAE, MSE, R² Score                                     |
| Business Intelligence  | Power BI (Desktop)                                     |
| Data Format            | CSV (Simulated Defense Dataset)                        |
| Development Platform   | Jupyter Notebook (Localhost)                           |

---

## 📁 Project Structure

├── Operation_Sindoor.ipynb # Jupyter notebook with model pipeline
├── dataset.csv # Input dataset (confidential sample format)
├── PowerBI_Dashboard.pbix # Power BI file with dynamic visuals
├── README.md # You're here!


---

## 📊 Power BI Intelligence Dashboard

The **Operation Sindoor Overview** dashboard highlights:

- 🔥 **Total Incidents**: 15,000+ hostile or intercepted events  
- 📡 **Jet Trajectory Monitoring**: XY activity of Jet1 vs Jet2  
- ✈️ **Aircraft Coordination Score**: Predicted jet alignment using CNN  
- 🧠 **Secret Signal Pattern**: Most frequent decoded patterns  
- 📍 **Avg Distance Between Jets**: Indicates tactical efficiency  
- 🧭 **Operation Status**: Ratio of Safe vs Escalated missions  
- 📶 **Signal Filtering**: Dynamic filters for received signal patterns  
- 🧩 **Embedded ML Outputs**: CNN predictions directly tied to visuals  

Power BI makes it easy for intelligence analysts to interactively explore signal behavior, aircraft movement, and critical metrics during operations.

---

## 🧠 Machine Learning Pipeline

### 1. 📥 **Data Parsing**
- Raw intercepted signal sequences and aircraft trajectory data are read from a CSV.
- Sequence strings are converted into numerical tensors suitable for training.

### 2. 🔧 **Model Architecture**
- A **1D CNN** with Batch Normalization, Dropout, and Dense layers.
- Predicts the **XY coordinates** of aircrafts during tactical missions.

### 3. 🧪 **Training & Evaluation**
- Model is compiled with **Adam Optimizer** and trained for 100 epochs with early stopping.
- Metrics evaluated:
  - **Mean Squared Error (MSE)**
  - **Mean Absolute Error (MAE)**
  - **R² Score**

### 4. 📈 **Results**
- The model outputs:
  - Jet 1 & Jet 2 predicted positions
  - Jet Coordination Score based on positional variance
- Test results printed and exported for dashboard integration.

---

## 🔒 Security & Data Ethics

> ⚠️ This dataset is a **simulated format** inspired by real-time defense signal structures. For demonstration only—no classified or sensitive government data is included.  
This version is anonymized and manually reduced to maintain privacy and compliance.


https://github.com/Aaryan1901/Operation_Sindoor.git
