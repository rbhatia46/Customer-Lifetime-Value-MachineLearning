# Customer-Lifetime-Value-MachineLearning

## 3 Questions to answer - 

1. Which customers have the highest spend probability in next 90 days ?

2. Which customers have recently purchased but unlikely to buy ? (look at customers have bought anything in last 90 days but have a lower purchase probability as per the model(less than 20%)) - revive the customer before they die

3. Which customers were predicted to purchase but didn't(missed opportunities) ? (people who were predicted to spend a certain amount and had a higher purchase probability in the next 90 days but actually spent 0 dollars) - get the marketing team to send these people targeted emails because these are missed opportunities that can boost the revenue quite significantly 

## Next Steps for improvement - 

1. Leverage More features rather than just RFM (Customer demographics, Geographic information, etc)
2. Try better models(maybe AutoML) and do a more in depth hyperparameter tuning
3. Apply Interpretable ML techniques like SHAP and LIME to dive deeper and explain the predictions
4. Predict the next purchase day
5. Integrate through a REST API to create a dashboard.
6. Leverage Product/Item catalog(if available)
7. Try a Pareto/NBD Model and other classic statistical approaches.
