# Network-Anomaly-Detection using Machine Learning 
This project focuses on detecting anomalies in network traffic using various machine learning algorithms. Network anomalies can indicate potential security threats, cyber-attacks, or unusual behavior. This system aims to improve the accuracy and reliability of anomaly detection through model comparison and evaluation.

---

## 💡 Features

- Preprocessing of raw network traffic data
- Supervised and unsupervised learning models
- Evaluation using metrics like accuracy, precision, recall, F1-score
- Comparison of different algorithms
- Data visualization and model results

---

## 🧪 Machine Learning Models Used

1. **Isolation Forest** – Unsupervised model to detect outliers in high-dimensional data.
2. **DBSCAN** – Clustering-based approach to group similar traffic and isolate anomalies.
3. **Random Forest** – Supervised classifier that learns from labeled data.
4. **Neural Network** – Deep learning model trained to classify normal vs. abnormal traffic.

---

## 🗂️ Dataset

The dataset is split into:
- `train_data.csv`: Used for training the supervised models.
- `test_data.csv`: Used for model evaluation.

Each sample includes multiple features extracted from network traffic, with a binary label indicating whether it's **normal (0)** or **anomalous (1)**.


## 📊 Evaluation Metrics

Each model is evaluated using:

- ✅ Accuracy  
- 🎯 Precision  
- 🔁 Recall  
- 📉 F1-Score  
- 📉 Confusion Matrix  
- 📈 ROC/AUC Curve (optional)

---

🛠️ **Technologies Used**
Python 3.x

Scikit-learn

Pandas & NumPy

Matplotlib & Seaborn

TensorFlow / Keras or PyTorch (for Neural Networks)

👨‍💻 **Author**
Rithwin Reddy
GitHub: @Rithwin09

