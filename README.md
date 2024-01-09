# Horse Racing Outcome Prediction with SHAP Interpretation

Modern horse racing, originating in the mid-to-late 1700s in England, has sustained its popularity in sports betting. This repository presents a study that delves into uncovering the influential factors affecting horse race outcomes. Utilizing the Hong Kong Horse Racing Dataset from Kaggle, we explore and analyze various machine-learning models to predict whether a horse will secure a top-three position. 

The research focuses on interpreting both the optimal model and a pre-trained tabular model using SHAP (SHapley Additive exPlanations). SHAP is an explainability model that is based on the Shapley values method. It explains how individual predictions are made by a machine learning model. 

<img src="horse_SHAP_cover.png" alt="Alt Text" width="720"/>

## Approach
Our focus is using SHAP (SHapley Additive exPlanations) to understand our models better. SHAP helps us see how each model makes predictions. We aim to provide a clear view of why our models choose certain outcomes. We also look at individual races, considering a winning and losing horse for a closer look.

## SHAP Variations
We use different versions of SHAP, like Kernel SHAP and Tree SHAP, to analyze our models. This helps us get a full picture of how the best XGBoost model and a pre-trained TabNet model come to their conclusions.

## Methodology:

1. Dataset Preprocessing- data Integration, data cleaning, and feature engineering.
2. Modelling - Developed and optimized multiple models, including Logistic Regression, Random Forest, and XGBoost. A pre-trained TabNet model also included.
3. Evaluation- Evaluated the performance of models 
4. Interpreting models using SHAP- using SHAP (SHapley Additive exPlanations), including variations like Kernel SHAP and Tree SHAP to analyze models

## Reference:
For in-depth reference on SHAP, consult the following links:

SHAP Documentation-
https://shap.readthedocs.io/en/latest/

What is SHAP- 
https://christophm.github.io/interpretable-ml-book/shap.html
https://towardsdatascience.com/using-shap-values-to-explain-how-your-machine-learning-model-works-732b3f40e137

Guide to interpreting SHAP analysis- 
https://www.aidancooper.co.uk/a-non-technical-guide-to-interpreting-shap-analyses/
