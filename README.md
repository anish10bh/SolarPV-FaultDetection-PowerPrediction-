# SolarPV-FaultDetection-PowerPrediction-
# SolarPV-FaultDetection-PowerPrediction

This project applies machine learning and deep learning techniques to predict power output and classify faults in solar PV panels. It uses real-world voltage, current, temperature, and environmental sensor data collected from a PV system.

## 🌞 Project Objectives

- Predict solar panel power output using regression models.
- Classify panel faults due to:
  - Dust accumulation (Low, Medium, High)
  - Shading or obstruction (P1 to P8)
  - Abnormal operating conditions (voltage/current drop)
- Evaluate model performance using real sensor data.

---

## 📂 Project Structure
├── data/
│   └── solar_data.csv
├── notebooks/
│   ├── preprocessing.ipynb
│   ├── regression_models.ipynb
│   └── classification_models.ipynb
├── requirements.txt
├── README.md
└── .gitignore

---

## 🧠 Models Used

### Power Prediction (Regression)
- Linear Regression
- Polynomial Regression
- K-Nearest Neighbors (KNN)
- Random Forest
- Huber Regression
- Artificial Neural Networks (ANN)

### Fault Classification
- Random Forest
- Support Vector Machine (SVM)
- XGBoost
- TabNet
- Multilayer Perceptron (MLP)

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/anish10bh/SolarPV-FaultDetection-PowerPrediction-.git
   cd SolarPV-FaultDetection-PowerPrediction-

## 📌 Future Work
Real-time panel monitoring using a dashboard

Deployment with FastAPI, Docker, and cloud (Render/AWS)

Integration with IoT-based sensor systems
