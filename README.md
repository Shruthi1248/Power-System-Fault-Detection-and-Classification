# ⚡ Power System Fault Detection and Classification using Machine Learning

This project focuses on Detecting and Classifying faults in power systems using Machine Learning Techniques. It leverages Electrical Signal data (such as voltage and current readings) to accurately identify fault types as Three-Phase faults. The model was developed and deployed using IBM Watson AutoAI and IBM Cloud.


## 📌 Problem Statement

Power systems are prone to various Electrical Faults that can disrupt supply and damage infrastructure. Early Detection and Classification of these faults are essential for grid reliability. This project aims to automate the classification process using real-time sensor Data and Machine Learning.



## 📂 Dataset

- **File**: `fault_data.csv`  
- **Fields**: Voltage, Current, Load, Maintenance, Weather, Fault Location (Lat, Long), Fault Type  
- **Classes**: Line Breakage, Transformer Failure, Overheating

> Data was either simulated or collected from system logs and cleaned for model training.



## 📌 Proposed Solution

1. **Data Preprocessing**  
   - Handled missing values, noise, and normalization.
   - Engineered features like voltage deviation and current imbalance.

2. **Model Development**  
   - Used IBM Watson AutoAI to automatically train multiple models.
   - The best-performing model was selected based on accuracy and F1-score.

3. **Deployment**  
   - Final model deployed as a REST API using IBM Watson Machine Learning.
   - Real-time predictions enabled using test data inputs.


## ⚙️ Tools & Technologies

- IBM Watson Studio
- IBM Cloud Object Storage
- IBM Watson Machine Learning


## 📊 Results

- Achieved up to **90%+ classification accuracy** in some pipelines.
- AutoAI selected a **Random Forest Classifier** as the optimal model.
- Predictions showed high precision for all fault types.

> ✅ Fault types predicted: Line Breakage, Transformer failure, Overheating
