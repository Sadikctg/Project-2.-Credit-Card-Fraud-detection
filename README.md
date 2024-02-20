### Credit Card Fraud detection
![Credit Card Fraud detection](https://github.com/Sadikctg/Project_2_Credit_Card_Fraud_Detection/blob/main/images_file/frauddetection.jpg)
### Objectives
In this project, the aim is to utilize machine learning models to predict occurrences of fraudulent credit card transactions.<br>
**1. Detecting Fraudulent Transactions**<br>
The main goal is to classify transactions accurately as either authentic or fraudulent. Utilizing data encompassing transaction time, amount, and transformed features V1 to V28, various classification models are employed. To achieve this, we'll test and compare different model building techniques, evaluating their performance through various metrics.<br>
**2. Exploring Transaction Patterns** <br>
(i). Consecutive Frauds: Do fraudsters tend to strike multiple times in a short period?  By analyzing transaction sequences, we can uncover potential patterns of follow-up scams and strengthen our defenses. <br>
(ii). Amount Matters: Are fraudulent transactions typically larger than legitimate ones? We'll compare the typical amounts of authentic and fraudulent transactions, seeking any significant differences that might raise red flags.<br>
(iii). Fraudulent Peak Periods: Do fraud rates climb during specific times of day or days of the week? Can we identify peak transaction periods with a higher risk of fraudulent activity?<br>
(iv). Fraud in High-Volume Times: When overall transaction volume spikes, does the number of fraudulent transactions proportionally increase, is it simply due to an overall increase in transactions, or are there other hidden factors at play?<br>
(v). High-Fraud Time Points: Why do certain moments stand out for unusually high fraud rates? Is it purely due to a high volume of transactions, or could other factors be influencing this surge?
<br>
### Problem Statemet
**Security Awareness:** Many banks is retaining high-profit customers, but banking fraud poses a substantial threat, leading to financial losses and eroding trust. A bank informs users of an expiring card and requests verification. Users should avoid sharing sensitive details as fraud cases in digital transactions are on the rise.<br>
**Growing Digital Transactions:** Despite a 51% growth in digital transactions, concerns persist due to a substantial increase in fraudulent activities, with 52,304 cases reported in FY 2019.
While making online purchases, regularly monitor account statements for any suspicious transactions and report them to the bank immediately.<br>
**Manual System:** Slow, clunky manual reviews choke banks' efficiency, leading to costly chargebacks, frustrated customers, and missed legitimate transactions. This reactive approach leaves everyone vulnerable.

### Credit card fraud and its impact:
**Financial Protection:**  With an increasing need to detect fraudulent transactions, machine learning models play a crucial role. Understanding model selection, tuning, and handling class imbalances are essential skills for data scientists.
Banks cann utilize machine learning algorithms to analyze transaction patterns, flagging unusual activities and preventing potential fraud. Protect profits, safeguard customers, and thrive in the age of digital payments.<br>
**Preserving Trust:** Detection models play a crucial role in preserving trust between customers and banks. By promptly identifying and addressing fraudulent activities, banks demonstrate their commitment to security, ensuring customers feel secure in their financial transactions.<br>
**Operational Efficiency:** Implementing a robust fraud detection model enhances operational efficiency by automating the identification process. For example, a machine learning model can analyze vast datasets more rapidly than manual reviews, minimizing the time and resources required to detect fraudulent transactions.<br>
**Regulatory Compliance:** Financial institutions must comply with regulations and standards to ensure a secure and trustworthy banking environment. A credit card fraud detection model helps banks adhere to these requirements, avoiding legal issues and reputational damage. For instance, if a bank fails to detect and prevent fraudulent activities, it may face regulatory penalties and lose customer trust.

### Common method of credit card fraud:
Magnetic Mimicry: Skimming steals card data for shady swaps.<br>
Counterfeit Cabal: Fake cards join the plastic party, uninvited.<br>
Lost & Found Lies: Stolen cards fuel fraudulent feasts.<br>
Telephonic Trickery: Sweet-talking scammers swipe cash by extracting information.<br>
Others: Tampered cards & Identity theft play a deceitful game.

### Steps of this project
**1.**	Perform Exploratory Data Analysis (EDA) for an initial overview of the dataset, focusing on feature distribution, class imbalances, and overall data characteristics. <br>
**2.**	Conduct Data Preprocessing, addressing missing values, and applying normalization or standardization to prepare data for model training.<br>
**3.**	Train various fraud detection models, including XGB Classifier, Light GBM Classifier, Gradient Boosting Classifier, Ada Boost Classifier, Random Forest Classifier, Logistic Regression, Support Vector Machine (SVM), Decision Tree Classifier, Hist Gradient Boosting Classifier.<br>
**4.**	Evaluate model performance using metrics such as AUC-ROC, precision, recall, F1-Score, and visualizations like ROC curves and confusion matrices.<br>
**5.**	Select the most suitable model for credit card fraud detection based on comprehensive evaluation metrics.

### Distribution of Time for Normal & Fraudulent Transactions

![Credit Card Fraud detection](https://github.com/Sadikctg/Project_2_Credit_Card_Fraud_Detection/blob/main/images_file/1.1%20Distribution%20of%20Time%20for%20normal%20and%20Fraudulent%20Transactions.png).

** This complete transactions occurs over a two-day period.**
Most of the fraudulent transactions appear to have occurred between the time intervals of 9 hours to 28 hours after a certain event, with another cluster observed between 36 hours and 46 hours thereafter. <br>
These time frames suggest potential patterns or anomalies in the timing of fraudulent activities, which could be further investigated for insights into the nature of the fraudulent behavior or to enhance fraud detection algorithms.

### Distribution of Time for Normal & Fraudulent Transactions

![Credit Card Fraud detection](https://github.com/Sadikctg/Project_2_Credit_Card_Fraud_Detection/blob/main/images_file/1.1%20Distribution%20of%20Time%20for%20normal%20and%20Fraudulent%20Transactions.png).
