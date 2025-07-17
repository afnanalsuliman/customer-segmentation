# Customer Segmentation Based on Marketing Response

This project applies machine learning techniques to segment customers based on their responses to a direct marketing campaign by a Portuguese bank. The aim is to identify key characteristics of customers who are likely to subscribe to a term deposit, helping improve marketing effectiveness.

## 📊 Dataset
- **Source:** UCI Machine Learning Repository  
- **File:** `bank-additional-full.csv`  
- **Records:** 41,188  
- **Features:** 20 input variables (e.g., age, job, education, campaign info)

## 🎯 Objective
Use supervised learning models to predict whether a client will subscribe to a term deposit and analyze the most influential features.

## 🛠️ Tools & Technologies
- Python (Jupyter Notebook)  
- Scikit-learn  
- Pandas  
- Matplotlib, Seaborn  

## ⚙️ Data Preprocessing
- Handled class imbalance (undersampling)
- Label and one-hot encoding for categorical features
- Normalized numerical data

## 📈 Models Used
- Logistic Regression  
- Random Forest  
- Naïve Bayes  

## 📊 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- Confusion Matrix  

## 🧠 Key Findings
- Age, contact method, and previous campaign outcome were among the most important features.
- Random Forest performed best in terms of accuracy and generalization.

## 🧪 How to Run
1. Clone the repository  
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:  
   `CustomerSegmentationBasedonMarketingResponse.ipynb`

## 📂 Files Included
- `bank-additional-full.csv` – Raw dataset  
- `CustomerSegmentationBasedonMarketingResponse_Paper.pdf` – Final project report  
- `CustomerSegmentationBasedonMarketingResponse_Proposal.pdf` – Project proposal  

## 👤 Team
- Afnan AlSuliman

> 📚 This project was completed as part of the Data Mining course at King Saud University.