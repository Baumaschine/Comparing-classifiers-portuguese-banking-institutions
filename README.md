# Comparing-classifiers-portuguese-banking-institutions
# Summary

# Business Exploration

The dataset revolves around the direct marketing campaigns (phone calls) of a Portuguese banking institution. The objective is to predict whether a client will subscribe to a term deposit (variable y).

In this endeavor, my aim is to construct various classifier models empowering banks to ascertain if a customer is inclined to accept a term deposit. The goal is to enhance revenue and expand the customer base.

# Data Insight

Imported the CSV dataset using Pandas. Employed Plotly to craft diverse histograms, unraveling the distribution nuances within different columns.

# Data Refinement

Utilized one-hot encoding for the conversion of all categorical features into numerical counterparts. Excluded features with unknown labels to streamline data coherence.

# Model Crafting

Standardized numerical and target feature columns. Segregated datasets into Train (70%) and Test (30%). Developed the following classifier models with default parameters: Baseline model using DummyClassifier - Accuracy=51.246% Logistic Regression - Accuracy=73.504% KNN Classifier - Accuracy=72.613% Decision Trees - Accuracy=72.364% SVM Classifier - Accuracy=73.824% Established the following classifier models with hyperparameter tuning using Randomized SearchCV: KNN Classifier - Accuracy=73.748% Decision Trees - Accuracy=78.445%

# Evaluation

The Decision Tree Classifier model exhibited superior performance, characterized by heightened accuracy, precision, recall, and AUC. A visual representation through a bar plot was generated for comparative analysis.

# Conclusion

In this practical application project, I curated multiple machine learning classifier models predicting the likelihood of clients subscribing to a bank's term deposit. The standout performer was the Decision Tree classifier with optimized hyperparameters, boasting an impressive 86.36% accuracy.

With a precision of 0.8734, divided by a prevalence of 0.50, the model surpasses random guessing by 1.74 times. Additionally, it effectively identifies 60% of customers poised to subscribe to a term deposit.

Strategic Insight: Banks can strategically target customers with a high consumer price index and euribor3m (a 3-month indicator for loan repayment), given their significant importance features in both the model and the business context.
Enhancements

Model Tuning: Continuing efforts to boost performance through additional feature engineering and techniques like RFE.
Exploring diverse classifier models, including:
    Gaussian Naive Bayes
    Random Forest
    XGBoost
Implementing data imputation methods to refine data quality.

# License

Author

Fabian Schaberl (fabianschaberl01@gmail.com
