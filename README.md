## Overview:
* Welcome to the Stroke Prediction Project repository! This project focuses on utilizing machine learning algorithms to predict and analyze the likelihood of stroke occurrence, contributing to proactive healthcare strategies.


## 🔍 Key Features:

* Rigorous data preprocessing, handling missing values and outliers, accurately categorizing attributes as either categorical or numerical and ensuring proper assignment. Exploring patient behavior and identifying key features through correlation maps, histograms, and plots.
Implementation of diverse supervised learning models, including Naive Bayes, Random Forest, K-Nearest Neighbors (KNN), and Decision Trees.
Comprehensive evaluation metrics, including accuracy, precision, and recall, to assess and fine-tune predictive models.
Interactive data exploration through visualizations like correlation matrices, pie charts, histograms, and plots.

## 💡 Objective:

* Our main goal is to utilize supervised learning models to develop precise and dependable tools for early stroke detection, predicting the likelihood of a patient experiencing a stroke based on input features. This repository acts as a valuable reference for comprehending the integration of machine learning in healthcare, advocating for proactive health management.


## 🛠️ Technologies Used:

Python: Leveraging the power of Pandas, NumPy, and Scikit-Learn.

Jupyter Notebooks: Transparent and interactive documentation of the entire workflow.


## 📈 Results:

**Naive Bayes Classifier:**
* The findings reveal that the Multinomial Naive Bayes model achieved an overall accuracy of 84%, with a precision rate of 86% for correctly predicting stroke cases. Notably, the classifier demonstrated a high recall of 97%, indicating its effectiveness in correctly identifying the majority of stroke patients when they are present.

**KNN Classifier:**
* The findings indicate that the K-Nearest Neighbors (KNN) model achieved an impressive overall accuracy of 95%. Notably, the precision rate for predicting stroke cases is 100%, signifying that when the model predicts a patient to have a stroke, it is correct 100% of the time. Furthermore, the recall is 95%, demonstrating the model's ability to correctly identify 95% of all actual stroke patients, making it a robust classifier for stroke prediction.

**Decision Tree:**
* The findings reveal that the Decision Tree model achieved an accuracy of 91%. Notably, the precision for predicting stroke cases is 95%, indicating that when the model predicts a patient to have a stroke, it is correct 95% of the time. Additionally, the recall is 95%, demonstrating the model's effectiveness in correctly identifying 95% of all actual stroke patients. Overall, these results signify the robust performance of the Decision Tree classifier in stroke prediction.

**Random Forest:**
* The findings indicate that the Random Forest model achieved a high accuracy of 95%. Specifically, the precision for predicting stroke cases is 100%, highlighting that when the model predicts a patient to have a stroke, it is correct 100% of the time. Moreover, the recall is 95%, demonstrating the model's efficacy in correctly identifying 95% of all actual stroke patients. These results underscore the robust and accurate performance of the Random Forest classifier in stroke prediction.


## Conclusions:

* K-Nearest Neighbors and Random Forest demonstrated strong performance, achieving an accuracy score of 95%. The Decision Tree followed closely with an accuracy of 91%, while Naïve Bayes yielded the lowest accuracy among the four classifiers, registering at 84%. The analysis reveals that both K-Nearest Neighbors (K-NN) and Random Forest achieved high accuracy scores, with Random Forest emerging as the preferable choice due to its faster computation time and superior handling of overfitting. However, if minimizing computation time is crucial, Naïve Bayes and the Decision Tree classifier present more efficient alternatives. Further investigation could delve into the reasons why a significant number of patients who experienced a stroke did not have heart disease, questioning the reliability of heart disease as an indicator for strokes. The collected data holds valuable insights for identifying critical features such as years of smoking and the presence of hypertension when dealing with patients at risk of stroke. This information can benefit hospitals and drug companies in developing targeted preventive measures based on gender, age, BMI, and other factors highlighted in the exploratory data analysis (EDA) findings.


## 🔗 Connect with Me:

LinkedIn: (https://www.linkedin.com/in/faridatlawal/)



## 🌐 Explore the Project:

Feel free to explore the code, datasets, and documentation. Contributions and feedback are highly appreciated!


###### Let's work together towards a healthier future! 🩺✨
