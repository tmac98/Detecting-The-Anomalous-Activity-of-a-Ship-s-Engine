# 🚢 **Detecting Anomalous Activity in a Ship’s Engine**

## 📌 **Project Overview**
This project applies **anomaly detection techniques** to monitor and detect irregularities in a ship's engine performance. Using **statistical methods and machine learning models**, the system identifies early warning signs of potential engine failures, reducing **downtime, maintenance costs, and operational risks**. The project focuses on **detecting anomalies in key engine parameters**, including fuel pressure, lubrication oil temperature, and engine RPM.

---

## 📊 **Key Features**

- 🔍 **Data Preprocessing**: Cleaned and standardized engine sensor data.  
- 📈 **Anomaly Detection Techniques**: Implemented **IQR, One-Class SVM, and Isolation Forest**.  
- 📌 **Hyperparameter Tuning**: Optimized detection sensitivity to capture **1-5% anomalies**.  
- 🧠 **Dimensionality Reduction**: Used **PCA** to visualize anomalies in 2D space.  
- 📑 **Business Insights**: Identified **key engine parameters** linked to performance risks.  

---

## 📈 **Results & Insights**

The analysis identified **engine performance anomalies** across key parameters:

- ⚠️ **Lubrication Oil Temperature and Fuel Pressure** were the most critical indicators of engine anomalies.  
- 🚢 **Predictive maintenance strategies** can reduce costly unplanned downtime.  
- 📉 **Isolation Forest provided the most reliable anomaly detection**, detecting **3% anomalies** while minimizing false positives.  

📌 **PCA-based visualizations** effectively separated normal and anomalous engine behavior, making it easier for **decision-makers** to act on insights.

---

## 📂 **Project Files**

- 📄 **[Jupyter Notebook: Detecting The Anomalous Activity of A Ship's Engine](./Detecting_The_Anomalous_Activity_of_a_Ship’s_Engine_Notebook.ipynb)**
- 📑 **[Detailed Report: Detecting The Anomalous Activity of A Ship's Engine](./Detecting%20Anomalous%20Activity%20in%20a%20Ship%20Engine%20Report.pdf)**

---

## 🛠 **Technologies Used**

- 🐍 **Python**: Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib  
- 🤖 **Machine Learning**: One-Class SVM, Isolation Forest, IQR  
- 📊 **Data Visualisation**: PCA plots, Boxplots, Anomaly Distributions  

---

## 🔮 **Future Improvements**

- 📊 **Explore alternative anomaly detection methods** (e.g., Autoencoders, DBSCAN).  
- 📈 **Integrate real-time monitoring** for early detection and automatic alerts.  
- 🖥️ **Develop an interactive dashboard** for shipping operators to track engine health.  
