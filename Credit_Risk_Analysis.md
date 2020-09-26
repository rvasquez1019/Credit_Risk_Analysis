# Credit Risk Analysis
In this analysis, we build and evaluated several machine learning models to assess credit risk, using data from LendingClub, a peer-to-peer lending services company.  We first compared resampling methods using logistic regression models. Then we evaluated the performances of some ensemble classifiers and made recommendations.  As we all know credit risk is an unbalanced classification problem that many companies face.  As the number of good loans easily outnumber the number of risky loans, many different techniques are applied to train and evaluate models with unbalanced classes.  

# Objectives

- Evaluate and implement the performance of machine learning models.
- Balanced Random Forest Classifier, combines resampling ad model training in a single step.
- Easy Ensemble Classifier, combines resampling ad model training in a single step.
- Use resampling to attempt to address class imbalance. 
- Oversample the data using the RandomOverSampler and SMOTE algorithms.
- Use a combination approach with the SMOTEENN algorithm.  
  
# Analysis 

#### Describe the precision and recall scores.

- Random Oversampling: precision 99%, recall 58%, F1 73%.
- SMOTE Oversampling: precision 99%, recall 68%, F1 81%.
- Undersampling: precision 99%, recall 41%, F1 58%.
- Combination: precision 99%, recall 57%, F1 72%.
  
# Final Recommendation

SMOTE oversampling in my opinion is the most ideal as it has the highest balanced accuracy score of all the overall models.  