### **Credit Card Fraud Detection Using Machine Learning**

**Abstract**  
Credit card fraud is a major concern globally, leading to billions of dollars in losses each year. This project aims to leverage machine learning algorithms to detect fraudulent transactions by identifying patterns indicative of fraud. Credit card fraud can occur through the physical theft of a card or the unauthorized access to sensitive card information. This project proposes the development of a machine learning model that will be trained on historical credit card transaction data and evaluated using a holdout dataset of unseen transactions.

**Keywords:** Credit Card Fraud Detection, Fraud Detection, Fraudulent Transactions, K-Nearest Neighbors, Support Vector Machine, Logistic Regression, Decision Tree.

---

### **Overview**  
The rising use of credit cards in daily life necessitates robust security measures from credit card companies to protect their customers. According to 2021 credit card statistics, 2.8 billion people worldwide used credit cards in 2019, with most users owning a single card. In 2020, reports of credit card fraud in the U.S. increased by 44.7%. There are two main types of credit card fraud: the first involves identity thieves opening a credit card account under another person's name, with reports of this type increasing by 48% in 2020. The second type occurs when thieves use an existing account by stealing the credit card information, with reports of this type increasing by 9% in 2020 (Daly, 2021). These alarming statistics highlight the need for analytical solutions using machine learning techniques to detect fraudulent credit card transactions.

### **Project Goals**  
The primary goal of this project is to detect fraudulent credit card transactions to prevent customers from being wrongly charged for unauthorized purchases. Multiple machine learning techniques will be employed to identify fraudulent transactions. The performance of each technique will be compared to determine the most effective model for fraud detection, with detailed results and visualizations provided. Additionally, the project will explore previous literature and various approaches to identifying fraud in datasets.

### **Data Source**  
The dataset for this project was obtained from Kaggle and includes data on transactions made by European credit card users over two days in 2013. It contains 284,808 rows and 31 attributes, of which 28 are numeric variables transformed using PCA (Principal Component Analysis) to maintain customer privacy. The remaining attributes are "Time" (elapsed time between the first and subsequent transactions), "Amount" (transaction amount), and "Class" (binary indicator where "1" represents a fraudulent transaction and "0" represents a legitimate one).

**Dataset:** [Kaggle Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

### **Algorithms Used**  
- K-Nearest Neighbors (KNN)
- Logistic Regression (LR)
- Support Vector Machine (SVM)
- Decision Tree (DT)

### **Future Work**  
Future improvements to the model could involve testing it on datasets with varying sizes and data types or adjusting the data-splitting ratios. Incorporating additional data sources, such as telecom data to determine the location of the cardholder, could enhance fraud detection. For example, if a cardholder is in Dubai and a transaction occurs in Abu Dhabi simultaneously, the model could easily flag this as a potential fraud.

### **Conclusion**  
The main objective of this project was to identify the most suitable machine learning model for detecting credit card fraud. By developing and evaluating four models, the project determined that K-Nearest Neighbors (KNN) and Decision Tree (DT) performed the best, achieving 100% accuracy in identifying fraudulent transactions. These results underscore the potential of these techniques to enhance customer satisfaction and security by providing a safer and more reliable credit card experience.
