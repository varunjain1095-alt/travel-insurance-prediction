# Travel Insurance Purchase Prediction

This project analyses the likelihood of travel insurance purchase using demographic and socio-economic attributes.

## Business Objective
To identify customer segments with higher likelihood of purchasing travel insurance and support targeted marketing decisions.

## Dataset
- 101,000 customer records
- Demographic, socio-economic, health, and basic behavioural attributes
- Binary target variable: insurance purchase

## Modelling Approach
- CatBoost Classifier
- Stratified K-Fold cross-validation
- Hyperparameter tuning
- Error analysis by income and age groups
- SHAP for global model explainability

## Key Insights
- Income is the strongest driver of predictions
- Model misses buyers in certain age and income segments
- Error patterns highlight limitations of demographic-only data

## Notebook
- `travel_insurance_purchase_prediction.ipynb
