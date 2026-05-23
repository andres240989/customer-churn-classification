# customer-churn-classification

## Business Problem 

The telecommunications company Telecom needs to determine the probability that a customer will cancel their subscription to the service portfolio currently held with the company, in order to offer promotions and special plans to users at risk of churn

## Objetives

Develop a classification model to identify customers with a high probability of churn. The model is designed to provide clear and actionable insights that help the marketing team make data-driven decisions and create effective customer retention strategies

## Technologies used

### Programming Language
- Python

### Data Analysis
- Pandas
- NumPy

### Machine Learning
- Scikit-learn
- CatBoost
- LightGBM

### Data Visualization
- Matplotlib
- Seaborn

### Development Tools
- Jupyter Notebook
- VS Code
- Git
- GitHub

## Methdology

1. Data Upload and Initial Exploration
   - Loaded the dataset and explored its structure, variables, and missing values.

2. Data Preprocessing
   - Cleaned and transformed messy data.
   - Handled null values.
   - Standardized text formatting.
   - Corrected data types.
   - Organized information into structured tables.

3. Exploratory Data Analysis (EDA)
   - Analyzed patterns, correlations, and customer behavior.
   - Created visualizations to identify trends and insights.

4. Feature engineering
  - Creation of a new variable (tenure_days) to determine customer tenure

5. Model Training and Evaluation
   - Trained multiple machine learning models.
   - Evaluated model performance using classification metrics.

6. Conclusions
   - Summarized the main findings and business insights obtained from the analysis.

 ## Key Results and Findings

- Addressed class imbalance (26% vs. 74%) using native model hyperparameters such as `scale_pos_weight` and `auto_class_weights` instead of synthetic oversampling techniques, reducing the risk of overfitting while preserving the original data distribution.

- Missing values and inconsistent data were treated during preprocessing to improve data quality and model reliability.

- Feature engineering played a critical role in model performance. In particular, the creation of the variable *Customer Tenure in Days* helped identify important churn patterns among long-term customers with high accumulated charges.

- CatBoost was selected as the best-performing model due to its superior AUC-ROC (93%) and F1-Score (78%), demonstrating strong predictive capability and balanced classification performance.

- The final model achieved a Recall of 81%, allowing the detection of approximately 8 out of 10 customers at risk of churn before cancellation, enabling proactive retention strategies.

## Strategic Business Insights

1. Identify customers with a high probability of churn in order to develop targeted retention strategies such as personalized promotions and loyalty programs.

2. Once high-risk customers are identified, analyze their level of engagement with the company, including the service packages they currently use, and evaluate opportunities to adapt products or plans according to their profile and customer needs.

3. Further analyze churn patterns to better understand the main causes of customer attrition. For example:
   - Are customers switching to competitors?
   - Is service quality influencing the probability of churn?
   - Are there specific products or services associated with higher cancellation rates?

4. From a managerial perspective, these analytical tools and recommendations can provide significant value to the marketing department when designing targeted retention campaigns and strengthening customer relationship strategies.
  
  
