# Credit-Card-Fraud

Here's a well-structured **`README.md`** file for your project: **"Identification of Credit Card Fraud Utilizing Hybrid Deep Learning Models with Improved Precision"**, based on the uploaded document.

---

## 📌 Identification of Credit Card Fraud Utilizing Hybrid Deep Learning Models with Improved Precision

### 🔍 Overview

This project addresses the critical issue of credit card fraud detection by developing a **hybrid deep learning framework** that minimizes false positives and maximizes detection accuracy. It combines **Autoencoders**, **Conv1D**, **SMOTE**, and **LSTM** to capture both temporal and spatial transaction patterns while addressing class imbalance.

### 🧠 Key Features

* ✅ Uses **SMOTE** to balance class distribution
* 🧠 Leverages **Autoencoders** for complex pattern extraction
* 📉 Applies **Conv1D** for local dependency detection
* ⏳ Uses **LSTM** for long-term temporal sequence learning
* 🔍 Achieves **100% precision, recall, and F1-score** on test data
* 📊 Tested on **European Credit Card Fraud Dataset**

---

### 📂 Project Structure

```
📁 project-root/
├── data/
│   └── creditcard.csv              # Credit card dataset (not included due to size)
├── models/
│   └── hybrid_model.h5             # Trained model 
├── notebook/
│   └── fraud_detection.ipynb       # Colab notebook
├── README.md
└── requirements.txt
```

---

### 📈 Methodology

1. **Data Preprocessing**

   * Handle missing values, normalize features
   * Apply **SMOTE** for balancing classes

2. **Feature Extraction**

   * **Autoencoders**: Detect hidden patterns in data
   * **Conv1D**: Extract local features from transaction sequences
   * **LSTM**: Model long-term dependencies in transaction flows

3. **Model Architecture**

   * Input → Autoencoder → Conv1D → LSTM → Dense Layer → Sigmoid Output

4. **Training**

   * Loss: Binary Crossentropy
   * Optimizer: Adam
   * Regularization: Dropout (0.2) and Batch Normalization

---

### 📊 Results

* **Accuracy**: 100%
* **Precision**: 1.00
* **Recall**: 1.00
* **F1-Score**: 1.00
* **AUC-ROC**: 1.00

> These results were achieved on a balanced dataset using SMOTE and validate the robustness of the hybrid approach.

---

### 🧪 Evaluation Metrics

* **Precision** = TP / (TP + FP)
* **Recall** = TP / (TP + FN)
* **F1-Score** = 2 × (Precision × Recall) / (Precision + Recall)
* **ROC-AUC** = Area under the Receiver Operating Curve

---

### 🚀 Future Work

* ✅ Real-time deployment of the fraud detection system
* 🔍 Model interpretability using SHAP
* 🌐 Integration into financial transaction pipelines

---

### 📚 Technologies Used

* Python
* TensorFlow / Keras
* Scikit-learn
* Pandas / NumPy / Matplotlib
* Google Colab / Jupyter Notebook

---

### 👥 Authors

* N Deshai
* Y Deva
* V Ravi Varma
* A Surya
* N Anil Kumar
* M Chilakarao
  (SRKREC, JNTUK, Bhimavaram)

📧 Contact: [desaij4@gmail.com](mailto:desaij4@gmail.com) | [devayadhala04@gmail.com](mailto:devayadhala04@gmail.com)

