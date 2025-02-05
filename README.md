
---

# **💳 Credit Default Prediction & Customer Segmentation**  
---

# 📌 Loan Default Prediction Using kNN & k-Means Clustering

## 🔍 Project Overview
This project focuses on predicting **loan default risks** for **30,000 bank customers** using **k-Nearest Neighbors (kNN) classification** and **k-Means clustering**. By segmenting customers based on **age**, we aim to optimize risk management strategies for financial institutions.

### 🎯 **Business Objective**
- Identify **high-risk customers** likely to default.
- Improve **credit risk assessment** using **customer segmentation**.
- Compare **segmented vs. non-segmented** kNN models to **enhance accuracy**.
- **Optimize lending strategies** through data-driven decision-making.

---

## 📌 **Business Implications & Strategic Recommendations**
### 🔹 Risk Mitigation Strategies:
- **Personalized Credit Limits**: Higher-risk groups should have **stricter credit caps**.
- **Financial Education**: **Lower-education customers** should receive **financial training**.
- **Behavioral Risk Models**: **Past repayment behaviors** should be included in future risk assessments.

### 🔹 Banking Strategy Optimization:
- **Automated loan approvals** integrating **kNN models** for **real-time decision-making**.
- **Segmented customer targeting** for **better loan pricing and risk management**.
- **Marketing campaigns tailored to risk segments** to **reduce default rates**.

---

## 📂 Project Structure

```
Credit-Default-Prediction-Customer-Segmentation/
│── data/                      <- Dataset and processed data files.
│── images/                    <- Visualizations and workflow screenshots.
│── notebooks/                 <- Jupyter notebooks for EDA and model building.
│── knime_workflows/           <- KNIME workflow files (.knwf).
│── src/                       <- Python and R scripts used for additional analysis.
│── README.md                  <- Project documentation.
│── requirements.txt           <- Dependencies needed to run the project.
```

---

## 📊 **Exploratory Data Analysis (EDA)**

### 📌 Dataset Overview
- **30,000 customers** included in the dataset.
- **Key predictors**: Credit amount, repayment history, bill statements, past payments, age, education, and marital status.
- **Target variable**: **DEFAULT** (1 = Default, 0 = No Default).

### 📌 Distribution of Bill Statements
- Customers show **high variability** in **bill amounts** across six months.
- **Outliers detected**, requiring transformation.

![Bill Statement Distribution](https://github.com/EvidenceM290/Credit-Default-Prediction-Customer-Segmentation/blob/main/images/Bill%20Statement%20Distribution.png)

### 📌 Default Rates by Age
- **Younger customers** have a **higher probability of defaulting**.
- Customers **below 30 years old** are **high-risk borrowers**.

![Default Rates by Age](https://github.com/EvidenceM290/Credit-Default-Prediction-Customer-Segmentation/blob/main/images/Repayment%20Amount%20by%20Age.png)

### 📌 Default Rates by Education Level
- Customers with **lower education levels** (high school or below) **default more frequently**.
- **Graduate school attendees have the lowest default rates**.

![Default Rates by Education](https://github.com/EvidenceM290/Credit-Default-Prediction-Customer-Segmentation/blob/main/images/Default%20Rates%20by%20Education.png)

### 📌 Correlation Heatmap
- **Strongest correlations** found between **past repayment behaviors (PAY_X) and loan default**.
- Weak correlation between **age and default**.

![Customer Clusters](https://github.com/EvidenceM290/Credit-Default-Prediction-Customer-Segmentation/blob/main/images/Default%20Rates%20by%20Age.png)

---

## 🏗 **Model Development**

### 📌 Workflow Overview:
The **KNIME workflow** processes data, applies **kNN classification**, and segments customers using **k-means clustering**.

![Workflow](https://github.com/EvidenceM290/Credit-Default-Prediction-Customer-Segmentation/blob/main/images/ModelFlow.png)

### 📌 kNN Model Performance:
#### 🔹 Confusion Matrix
- **Model Accuracy**: **78%**
- **True Positive Rate (Recall)**: **95.7%**
- **Precision**: **80.1%**
- **Misclassification Rate**: **22%**

![Confusion Matrix](https://github.com/EvidenceM290/Credit-Default-Prediction-Customer-Segmentation/blob/main/images/Confusion%20Matrix.png)

#### 🔹 ROC Curve for kNN Model
- **AUC Score**: **0.667**, indicating a moderate predictive ability.

![ROC Curve](https://github.com/EvidenceM290/Credit-Default-Prediction-Customer-Segmentation/blob/main/images/kNN%20ROC%20Curve.png)

---

## 🎯 **Clustering Insights (k-Means)**
### 📌 Optimal k Selection:
- **Elbow Method suggests k=3**, segmenting customers by **age**.

![Customer Clusters](https://github.com/EvidenceM290/Credit-Default-Prediction-Customer-Segmentation/blob/main/images/Customer%20Clusters.png)

### 📌 Cluster-Specific kNN Models:
- **Cluster 0** (Older customers) → **AUC = 0.671** (Best performing segment)
- **Cluster 1** (Middle-aged customers) → **AUC = 0.658**
- **Cluster 2** (Younger customers) → **AUC = 0.638**

### 📌 Performance Comparison:
- **Segmented models outperform the non-segmented model**.
- **Cluster 0 is more predictable**, ideal for **customized credit policies**.
  
---

## 🔥 **Key Takeaways**
✅ **kNN achieves 78% accuracy** in predicting defaults.  
✅ **Customer segmentation enhances model performance**.  
✅ **Cluster 0 customers show the best predictive accuracy (AUC = 0.671)**.  
✅ **Banks can use these insights to refine credit risk policies and customer engagement strategies**.  

---

## 🏆 **Final Thoughts**
This project showcases the power of **kNN classification and k-means clustering** in **credit risk analysis**. By segmenting customers, financial institutions can **improve loan decision-making** and **reduce default risk** effectively.

---

## 🚀 **Future Enhancements**
🔹 **Feature Engineering**: Incorporate **additional financial variables**.  
🔹 **Deep Learning Models**: Compare kNN with **Neural Networks**.  
🔹 **Real-Time Model Deployment**: Implement as a **live loan approval system**.  

---

## 📩 **Connect With Me**
📧 **Email:** emadhume@smu.edu  
🔗 **LinkedIn:** [LinkedIn](https://www.linkedin.com/in/evidence-madhume-874540204/)  
🌍 **GitHub**: [EvidenceM290](https://github.com/EvidenceM290)  

---
