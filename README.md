# Machine Learning–Based Power Quality Analysis in Power Systems

This repository contains a comprehensive machine learning and deep learning
project focused on **power quality (PQ) disturbance analysis in modern power systems**.
The project uses signal processing and data-driven techniques to identify and
classify common PQ disturbances affecting power system performance and reliability.

---

## 📌 Project Objective
The objective of this project is to:
- Analyze power system signals in both **time domain** and **frequency domain**
- Extract meaningful statistical and spectral features
- Apply **machine learning and deep learning models** to classify power quality disturbances
- Evaluate and explain model predictions for improved interpretability

---

## ⚡ Power Quality Disturbances Considered
The following PQ events are analyzed and classified:
- **Harmonics**
- **Voltage Sag**
- **Voltage Swell**
- **Interruptions**
- **Flicker**

---

## 🔍 Methodology Overview

### 1. Data Loading and Preparation
- Power quality datasets are loaded from CSV files
- All datasets are unified into a single structured DataFrame
- Class labels are assigned for supervised learning

### 2. Signal and Frequency Domain Analysis
- Time-domain signals are analyzed
- **Fast Fourier Transform (FFT)** is applied to study frequency-domain characteristics
- Harmonic components are identified using the frequency spectrum

### 3. Feature Extraction
- Statistical features are extracted from signals, including:
  - Mean
  - Standard deviation
  - Skewness
  - Kurtosis
  - Energy
- Feature scaling and cleaning are performed to handle missing and infinite values

### 4. Dimensionality Reduction
- **Principal Component Analysis (PCA)** is used to reduce feature dimensionality
- Explained variance and cumulative variance are analyzed

### 5. Machine Learning Models
Multiple ML models are trained and evaluated, including:
- Random Forest
- XGBoost
- Support Vector Machine (SVM)
- Extra Trees
- Multi-layer Perceptron (MLP)
- Stacking Ensemble Model

### 6. Deep Learning Models
- **Artificial Neural Network (ANN)** for multi-class classification
- **Long Short-Term Memory (LSTM)** network for sequence-based learning

### 7. Model Evaluation and Explainability
- Performance evaluated using:
  - Accuracy
  - Confusion matrix
  - Precision, recall, and F1-score
- **LIME (Local Interpretable Model-Agnostic Explanations)** is used to explain model predictions

---

## 🛠 Tools and Technologies
- **Python**
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- TensorFlow / Keras
- Jupyter Notebook

---

## 📊 Key Outcomes
- FFT effectively reveals harmonic components in power system signals
- ML and DL models successfully classify PQ disturbances
- Ensemble and deep learning models show improved classification performance
- Explainability techniques enhance trust in model predictions

---

## 🚀 Applications
- Power quality monitoring systems
- Smart grids and intelligent substations
- Power system protection and diagnostics
- Academic and research-oriented studies in power systems and ML

---

## 🔮 Future Scope
- Real-time PQ monitoring using streaming data
- Deployment using edge devices or cloud platforms
- Integration with SCADA or smart grid frameworks
- Advanced feature learning using CNN-based models

---

## 👨‍💻 Author
**Pamudu Sachintha**  
Electrical Engineering | Power Systems | Machine Learning  

---

## 📎 Note
This project is intended for educational, research, and professional demonstration
purposes in the field of **power systems and data-driven analysis**.
