# 🛡️ Cyber Attack Detection using Big Data Analytics  

## 🔍 Overview  
This project focuses on detecting cyber attacks in network traffic using Big Data Analytics techniques.  
It uses the NSL-KDD dataset to build machine learning models for identifying malicious network connections.

---

## 🎯 Objectives  
- Detect cyber attacks in network traffic  
- Classify normal vs attack connections  
- Identify unknown attacks using anomaly detection  
- Handle large-scale data using PySpark  

---

## 🧠 Key Concepts  
- Classification (Random Forest)  
- Anomaly Detection (KMeans Clustering)  
- Big Data Processing (PySpark)  

---

## 📂 Dataset  
The project uses the NSL-KDD dataset, which contains:  
- 41 features describing network traffic  
- Labels indicating normal or attack  
- Attack types: DoS, Probe, R2L, U2R  

---

## ⚙️ Technologies Used  
- Python  
- PySpark  
- Scikit-learn  
- Jupyter Notebook  

---

## 🧪 Methodology  
1. Data Loading using PySpark  
2. Exploratory Data Analysis (EDA)  
3. Data Preprocessing and Encoding  
4. Feature Engineering  
5. KMeans Clustering for Anomaly Detection  
6. Random Forest for Classification  
7. Model Evaluation  

---

## 📊 Results  
- Detection Rate: ~98–99%  
- False Alarm Rate: ~14–15%  
- F1 Score: ~0.94  

The model effectively detects most cyber attacks, including unseen ones, with a good balance between accuracy and false alarms.

---

## ▶️ How to Run  
1. Clone the repository  
2. Open the notebook in Jupyter  
3. Ensure dataset files are available  
4. Run all cells  

---

## 📌 Conclusion  
This project demonstrates how combining classification and anomaly detection techniques with big data tools can effectively detect cyber attacks in network traffic.

---

## 👨‍💻 Author  
Arjun Durugkar