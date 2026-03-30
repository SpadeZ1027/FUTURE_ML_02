# 📊 Support Ticket Classification & Priority Prediction System

## 🚀 Overview
This project builds an intelligent system to automatically classify IT support tickets into categories and assign priority levels using Natural Language Processing (NLP) and Machine Learning.

The goal is to help support teams respond faster, reduce manual effort, and improve customer satisfaction.

---

## 🎯 Objectives

- Perform text cleaning and preprocessing  
- Convert text into numerical features using TF-IDF  
- Classify support tickets into categories  
- Assign priority levels (High / Medium / Low)  
- Evaluate model performance using metrics  
- Provide business insights through visualizations  

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- NLTK (optional)  

---

## 📂 Dataset

- **Source:** Kaggle - IT Service Ticket Classification Dataset  
- **Columns Used:**  
  - `Document` → Ticket text  
  - `Topic_group` → Category  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Lowercasing text  
- Removing punctuation  
- Stopword removal  
- Text normalization  

### 2. Feature Engineering
- TF-IDF Vectorization to convert text into numerical features  

### 3. Model Used
- Logistic Regression for classification  

### 4. Priority Assignment
Rule-based logic:
- High → urgent, error, failure, not working  
- Medium → slow, delay, issue  
- Low → default  

---

## 📊 Key Results

- ✅ Model Accuracy: **~85%**  
- Strong performance across most categories  
- Balanced precision and recall  

---

## 📈 Visualizations

### 📊 Ticket Category Distribution  
Shows the most common support issues.

### 🚨 Priority Distribution  
Displays urgency levels of incoming tickets.

### 📊 Confusion Matrix  
Shows model performance and misclassification patterns.

### 📊 Category vs Priority Heatmap  
Highlights which categories are most critical.

---

## 🧠 Business Insights

- Hardware and HR Support are the most frequent issues  
- Hardware-related tickets often have higher priority  
- Automation reduces manual workload  
- Faster response improves customer satisfaction  

---

## 💡 How It Works

1. User submits a support ticket  
2. System preprocesses the text  
3. Model predicts the ticket category  
4. Priority is assigned automatically  
5. Output is generated instantly  

---

## 🚀 Future Improvements

- Use advanced models like BERT  
- Improve priority prediction using ML  
- Build a web app using Streamlit  
- Integrate with real-time ticketing systems  

---

# 📜 License (GNU GPL v3)

This project is licensed under the **GNU General Public License v3.0**.
