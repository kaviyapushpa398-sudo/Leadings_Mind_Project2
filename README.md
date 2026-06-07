# Leadings_Mind_Project2

🛒 Online Shopper Intention Prediction using Logistic Regression and Random Forest Classifier

📌 Project Overview

This project focuses on predicting whether an online visitor will make a purchase based on their browsing behavior and session information. Understanding customer purchase intentions is a valuable challenge in the e-commerce industry, helping businesses improve marketing strategies, personalize user experiences, and increase sales conversions.

Two machine learning classification algorithms, Logistic Regression and Random Forest Classifier, were implemented and compared to determine the most effective model for predicting customer purchase behavior.

---

🎯 Objective

The primary objective of this project is to predict whether an online shopper will generate revenue (make a purchase) during a browsing session based on website interaction data.

---

📂 Dataset Information

Dataset: Online Shopper Intention Dataset

The dataset contains information about user sessions on an e-commerce website.

Features Used

- Administrative
- Administrative_Duration
- Informational
- Informational_Duration
- ProductRelated
- ProductRelated_Duration
- BounceRates
- ExitRates
- PageValues
- SpecialDay
- Month
- OperatingSystems
- Browser
- Region
- TrafficType
- VisitorType
- Weekend

Target Variable

Revenue

- TRUE = Customer made a purchase
- FALSE = Customer did not make a purchase

---

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

🔄 Machine Learning Workflow

1. Data Collection

Loaded the Online Shopper Intention dataset into a Pandas DataFrame.

2. Data Exploration

- Displayed dataset records
- Examined feature types
- Analyzed dataset structure
- Checked class distribution

3. Data Cleaning

- Checked missing values
- Removed inconsistencies
- Prepared data for modeling

4. Feature Selection

Selected relevant features affecting customer purchase decisions.

5. Encoding Categorical Variables

Applied Label Encoding to convert categorical features into numerical format.

6. Exploratory Data Analysis (EDA)

Performed:

- Customer behavior analysis
- Revenue distribution analysis
- Feature relationship analysis
- Visualization of important variables

7. Train-Test Split

Dataset was divided into:

- Training Set (80%)
- Testing Set (20%)

8. Model Development

Implemented and compared:

Logistic Regression

A supervised classification algorithm that predicts the probability of a customer making a purchase.

Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees to improve prediction performance and reduce overfitting.

9. Model Prediction

Generated predictions using both trained models.

10. Model Evaluation

Compared model performance using classification metrics.

---

📊 Model Performance Comparison

Metric| Logistic Regression| Random Forest Classifier
Accuracy| 88.69%| 90.41%
Precision| 74.43%| 74.06%
Recall| 36.18%| 54.41%
F1 Score| 48.69%| 63.73%

---

🏆 Best Performing Model

Random Forest Classifier

The Random Forest model achieved the best overall performance.

Key Results

✅ Accuracy: 90.41%

✅ Recall: 54.41%

✅ F1 Score: 63.73%

✅ Better customer purchase prediction capability

The Random Forest model demonstrated superior performance in identifying potential buyers compared to Logistic Regression.

---

📈 Visualizations Included

- Revenue Distribution
- Customer Behavior Analysis
- Correlation Heatmap
- Model Comparison Charts
- Classification Performance Metrics

These visualizations helped understand customer behavior patterns and evaluate model effectiveness.

---

🚀 Key Learning Outcomes

Through this project, I gained practical experience in:

✅ Data Preprocessing

✅ Exploratory Data Analysis

✅ Feature Selection

✅ Label Encoding

✅ Logistic Regression

✅ Random Forest Classifier

✅ Classification Problems

✅ Model Comparison

✅ Performance Evaluation

✅ Customer Behavior Analysis

---

📷 Sample Project Output

The developed models successfully predicted customer purchase intentions based on browsing session data.

Among the implemented algorithms, the Random Forest Classifier achieved the highest overall performance and demonstrated better predictive capability.

---

📚 Conclusion

This project successfully applied machine learning techniques to predict online shopper purchase intentions. By comparing Logistic Regression and Random Forest Classifier, it was observed that Random Forest provided better accuracy and classification performance.

The project strengthened my understanding of classification algorithms, customer behavior analytics, model evaluation, and real-world machine learning applications in e-commerce.

---

👨‍💻 Author

Kaviya B

Machine Learning Internship Project

Completed as part of a 30-Day Machine Learning Internship Program at Leading Minds.

---

🔗 Repository

Clone this repository using:

git clone https://github.com/yourusername/online-shopper-intention-prediction.git
