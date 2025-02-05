
---

# **💳 Credit Default Prediction & Customer Segmentation**  
## **📊 k-Nearest Neighbors (kNN) & k-Means Clustering Analysis**  
This project aims to predict **credit card defaults** using **supervised (kNN classification) and unsupervised (k-Means clustering) machine learning**. By analyzing **financial behavior, demographics, and repayment history**, we can classify **high-risk customers** and segment users for better risk management.  

📌 **Key Highlights**  
- 💰 **Business Problem:** Financial institutions need to assess credit risk and identify high-risk customers.  
- 🔍 **Feature Engineering:** Data cleaning, handling missing values, and normalization.  
- 🏆 **Modeling Approach:** **k-Nearest Neighbors (kNN) for prediction & k-Means for customer segmentation.**  
- 📊 **Evaluation Metrics:** Accuracy, Precision, Recall, ROC Curve (AUC), True Positive Rate, and Customer Clusters.  

---

## **📂 Project Structure**  
```
📂 credit-default-prediction/
 ├── 📂 data/ (Datasets)
 │   ├── default_of_credit_card_clients.csv *(Raw data file)*
 │   ├── cleaned_credit_data.csv *(Processed dataset)*
 │  
 ├── 📂 notebooks/ *(Jupyter Notebooks & R scripts for model building)*
 │   ├── credit_default_analysis.ipynb *(Exploratory Data Analysis & Model Training)*
 │   ├── model_evaluation.ipynb *(Confusion Matrix, ROC Curve, AUC computation)*
 │  
 ├── 📂 images/ *(Screenshots & visualizations for better insights)*
 │   ├── Modelflow.png *(KNIME Workflow Overview)*
 │   ├── Confusion Matrix.png *(Model Performance - Confusion Matrix)*
 │   ├── kNN ROC Curve.png *(ROC Curve for kNN Model)*
 │   ├── k-Means Clusters.png *(Customer Segmentation Clusters)*
 │   ├── Default Rates by Education.png *(Which education level has the highest defaults?)*
 │   ├── Default Rates by Age.png *(Age distribution of defaulters)*
 │   ├── PAY_AMT Distribution.png *(Repayment amount distribution)*
 │   ├── BILL_AMT Distribution.png *(Bill statement distribution)*
 │  
 ├── 📂 models/ *(Stored trained models if applicable)*
 │   ├── knn_model.pkl *(Trained kNN Model)*
 │   ├── kmeans_model.pkl *(Trained k-Means Model)*
 │  
 ├── 📜 README.md *(Project documentation and guide)*
 ├── 📜 requirements.txt *(Python dependencies)*
```

---

## **📌 Workflow Overview**  
This **KNIME Workflow** outlines the complete **data preprocessing, model training, and evaluation process**.  

![Workflow](https://github.com/EvidenceM290/Credit-Default-Prediction/blob/main/images/Modelflow.png)  

---

## **📈 Results & Visualizations**  
### **1️⃣ Model Performance Metrics**  
#### **🔹 kNN Model Performance**  
The **kNN Model** effectively classified **defaulters and non-defaulters** with a strong balance between **precision and recall**.  

📌 **Confusion Matrix & Metrics**:  
![Confusion Matrix](https://github.com/EvidenceM290/Credit-Default-Prediction/blob/main/images/Confusion%20Matrix.png)  

---

#### **🔹 ROC Curve Analysis**  
The **Receiver Operating Characteristic (ROC) Curve** evaluates how well the kNN model differentiates between **defaulters and non-defaulters**.  

📌 **kNN Model ROC Curve**:  
![kNN ROC Curve](https://github.com/EvidenceM290/Credit-Default-Prediction/blob/main/images/kNN%20ROC%20Curve.png)  

---

### **2️⃣ Customer Segmentation Using k-Means Clustering**  
By applying **k-Means clustering**, we segmented customers into distinct groups based on their **age, repayment behavior, and credit history**. This segmentation helps in **personalized risk assessment & credit offering strategies**.

📌 **k-Means Customer Segments**:  
![Customer Clusters](https://github.com/EvidenceM290/Credit-Default-Prediction/blob/main/images/k-Means%20Clusters.png)  

---

### **3️⃣ Insights from Exploratory Data Analysis (EDA)**  
#### **🔹 Default Rates by Education**  
Certain education levels show **higher default rates**, suggesting differences in **financial literacy and risk behavior**.

📌 **Default Rate by Education**:  
![Default Rates by Education](https://github.com/EvidenceM290/Credit-Default-Prediction/blob/main/images/Default%20Rates%20by%20Education.png)  

#### **🔹 Default Rates by Age**  
📌 **Younger borrowers (below 30) tend to default more frequently**, highlighting a potential risk for lenders.  

![Default Rates by Age](https://github.com/EvidenceM290/Credit-Default-Prediction/blob/main/images/Default%20Rates%20by%20Age.png)  

#### **🔹 Repayment & Bill Statement Distribution**  
📌 **Higher repayment amounts correlate with lower default risks**. Analyzing repayment behavior allows for **better risk-based pricing strategies**.  

![Repayment Amount Distribution](https://github.com/EvidenceM290/Credit-Default-Prediction/blob/main/images/PAY_AMT%20Distribution.png)  

![Bill Statement Distribution](https://github.com/EvidenceM290/Credit-Default-Prediction/blob/main/images/BILL_AMT%20Distribution.png)  

---

## **🔹 Key Takeaways for Strategic Decision-Making**  
✔ **High-risk customers can be segmented using k-Means**, allowing for targeted risk management strategies.  
✔ **Young borrowers (under 30) have higher default rates**, requiring **stricter risk assessment or financial literacy programs**.  
✔ **Repayment behavior strongly correlates with default risk** – customers who regularly **pay off large amounts are less likely to default**.  
✔ **Education level affects default probability**, suggesting a need for **tailored credit offerings** based on borrower profiles.  

📌 **How Management Can Use These Insights:**  
🔹 **Risk-based loan pricing:** Adjust interest rates based on repayment behavior & risk segmentation.  
🔹 **Targeted financial literacy programs:** High-risk groups can receive **budgeting & financial planning guidance**.  
🔹 **More aggressive collection strategies for young borrowers:** Higher-risk applicants can be subject to **stricter credit checks & lower initial credit limits**.  

---


---

## **📬 Connect With Me**  
📧 **Email:** emadhume@smu.edu  
🔗 **LinkedIn:** [Your Profile](your-linkedin-url)  
📂 **GitHub Portfolio:** [Your GitHub](your-github-url)  

---
