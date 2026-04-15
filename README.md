# EV Grid Stress Prediction System

An end-to-end machine learning system to predict transformer overload risk caused by EV charging demand across Indian states using real-world data, feature engineering, and interactive visualization.

---

## 🚀 Key Features

* Predicts electrical grid load (MW)
* Classifies overload risk (Low / Medium / High)
* Uses ML models: Random Forest, XGBoost, Gradient Boosting
* Feature engineered dataset for improved accuracy
* Interactive dashboard for real-time analysis
* Provides actionable mitigation strategies

---

## 🧱 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib, Seaborn
* Flask (Dashboard)

---

## 📊 Workflow

1. Data Collection (EV + Grid Data)
2. Data Preprocessing
3. Feature Engineering
4. Model Training & Evaluation
5. Risk Prediction
6. Dashboard Visualization

---

## 📊 Output

<img width="1678" height="872" alt="image" src="https://github.com/user-attachments/assets/73a7c01a-aef7-4c86-82cf-3d3b48c999f9" />


---

## 🎯 Project Overview

This system integrates multiple data sources to create a comprehensive solution for:

* **Predicting Grid Load** – Forecast electrical grid load in MW
* **Risk Assessment** – Determine overload risk (Low/Medium/High)
* **Mitigation Strategies** – Provide actionable recommendations
* **Visual Analytics** – Interactive dashboard and detailed analysis

---

## ✨ Features

### Core Capabilities

* Real-time grid load prediction using ML models
* Overload risk classification
* State-specific analysis and forecasting
* Historical pattern recognition
* Automated mitigation recommendations

---

## 📁 Project Structure

```
EV_GRID_STRESS_PROJECT/
│
├── data/            # Raw, processed, and engineered datasets
├── src/             # Core pipeline (preprocessing, training, prediction)
├── models/          # Trained ML models
├── notebooks/       # EDA and analysis
├── dashboard/       # Flask dashboard
├── requirements.txt
└── README.md
```

---

## 💻 Installation

### Prerequisites

* Python 3.7+
* pip

### Setup

```bash
pip install -r requirements.txt
```

---

## 🚀 Quick Start

### Run Full Pipeline

```bash
cd src
python dataset_builder.py
python preprocess.py
python feature_engineering.py
python train_model.py
```

### Run Dashboard

```bash
cd dashboard
python app.py
```

Open in browser:

```
http://localhost:5000
```

---

## 🤖 Models Used

### Regression (Grid Load)

* Random Forest
* XGBoost
* Gradient Boosting

### Classification (Risk Prediction)

* Random Forest
* XGBoost
* Logistic Regression
* Support Vector Machine

---

## 📈 Performance

* Accuracy: ~90–95%
* F1 Score: ~0.85–0.92
* R² Score: ~0.85–0.95

---

## 📊 Dashboard Features

* State-wise selection
* Parameter tuning
* Real-time predictions
* Visual risk indicators
* Mitigation suggestions

---

## 🔍 Risk Levels

* 🟢 LOW → Safe operation
* 🟡 MEDIUM → Preventive action needed
* 🔴 HIGH → Critical overload risk

---

## 📚 Usage Example

```python
from src.predict import EVGridPredictor

predictor = EVGridPredictor()

result = predictor.predict({
    'charging_sessions': 800,
    'transformer_load_percent': 75
})

print(result)
```

---

## 🔧 Troubleshooting

* Train models first if not found
* Ensure dependencies are installed
* Check correct Python version

---

## 👥 Contributors

* Biswa 
* Tumulu Mihika
* Sidharth Satapathy
* Swagat Pradhan
* Shray Das

---

## 📝 License

For educational and research purposes.

---

**Status:** Production Ready
**Year:** 2026
