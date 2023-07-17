# Capstone-Project-Module-3-E-commerce-Customer-Churn-Analysis-and-Prediction-Zahra-Rizkita-Putri

## Created by : Zahra Rizkita Putri

The objective of this project is to examine customer churn within an e-commerce platform and identify specific customer characteristics that indicate a higher likelihood of churn. The aim is to create a machine learning model capable of predicting which customers are more likely to churn and derive meaningful insights to mitigate customer churn effectively.

### Outline

- Business Understanding
- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Modelling
- Hyperparameter Tuning
- Post Modelling
    1. Final Model Evaluation
    2. Feature Importances
    3. Confusion Matrix
    4. Implementation for Business
- Conclusion and Recommendation

### Business Understanding
    1. Background
E-commerce is a type of business that operates online, allowing customers to buy and sell products and services without the need for face-to-face interaction with sellers. In this industry, it is crucial to understand and address customer churn.
Customer churn refers to the rate at which customers leave a particular group or company within a specific timeframe. This concept can be applied to various situations, such as employees leaving a company or customers canceling their subscriptions. In e-commerce, a high churn rate can be detrimental because acquiring and retaining customers is essential for business growth. Therefore, many e-commerce companies analyze customer churn through datasets to better understand and tackle this issue.
Customer churn datasets typically contain information about customers' purchase history, including the number of purchases, the most recent purchase, and the types of products bought. This data is used to analyze churn rates and devise strategies to reduce them. For example, businesses can identify customer segments that are most prone to churn and develop retention strategies accordingly.
    
    2. Problem Statement
Loyal customers who churn can pose a loss for the company if not addressed. Therefore, it is essential for the company to retain the engagement of loyal customers on the e-commerce platform. One way to achieve this is by offering promotions. However, the cost and resources expended may be less effective if promotions are carried out without a strategic approach.
        
    3. Objective
To assist companies in identifying customers who may switch to competitors or cease shopping with them, it is valuable to forecast the customer churn rate in e-commerce. By accurately predicting customer churn, businesses can proactively implement strategies to retain those customers and mitigate any detrimental effects on their operations. Machine learning plays a crucial role in this process by analyzing past customer data and constructing models capable of predicting future churn rates.
        
    4. Metrics Evaluation
    
|       | N-Pred| P-Pred |
| --- | --- | --- |
| *N-Act*     | TP | FP |
| *P-Act*      | FN | TP |

Target:   
- 0   : Customer is loyal (not going to churn in certain period of time)
- 1   : Customer will churn

FP : False Positive (Customer predicted to churn but does not churn within the specified period)
FN: False Negative (Customer predicted not to churn but churns within the specified period)

False Negative rate should be minimized or Recall should be optimized.

### Dataset
The dataset used for this analysis is the E-commerce Customer Churn Dataset from Kaggle

### Analysis
The main analysis performed in this project includes:

1. Data understanding and data cleaning to prepare the data
2. Exploratory data analysis to understand the characteristics of the dataset
3. Preprocessing to prepare the dataset for modeling
4. Feature engineering to create new variables for modeling
5. Building machine learning models to predict customer churn including modellin and hyperparameter tuning
6. Do the Post Modelling process
7. Evaluating model performance and selecting the best model

All analysis are provided in the Jupyter Notebook

### Results
- From the final model evaluation, the best model for e-commerce churn prediction will be Logistic Regression. 
- From the classification report, there are metrics that can be gained which are accuracy, recall, precision, and f-1 score. 
- Recall is used as metrics evaluation in this analysis and the recall value is 83.18%. Additionally, the model has a 78% chance of correctly predicting customers who will churn.

### Conclusion and Recommendation
Conclusions and Recommendation are provided in the Jupyter Notebook

# Thank You
