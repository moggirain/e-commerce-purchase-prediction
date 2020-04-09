# e-commerce-purchase-prediction

## Problem Statement ## 
Consumer behaviors offered insights into the demands of the market and web analytics provided fast and clear results that gauge e-commerce growth strategy.

The goal of analysis is to generate business insights on consumer revenue generated behavior and predict whether the consumer visit leads to the purchase of items.

## Procedure ## 
![lifecycle](https://github.com/moggirain/e-commerce-purchase-prediction/blob/master/lifecylce.png) 

## Highlight ##

### Exploratory Analysis ###  
![flow](https://github.com/moggirain/e-commerce-purchase-prediction/blob/master/flow.png) 

The [code](https://github.com/moggirain/e-commerce-purchase-prediction/blob/master/Online_Shopper_Intention_V4.09.ipynb) could be found here 

Insight gained from EDA: 

  Less transactions triggered by returning visitors
   - Incentives for returning visitors: e.g, promotions on holidays and weekend, social media notification,       customer loyalty program 
 Low conversion rate in May holiday season 
   - Marketing campaign strategy
 In-depth analysis on Region 2, Region 5 and Region 9  
   - Identify the triggers  
   - Growth strategy 
Bounce Rate on Different Web pages
  - Tracking mechanism on bounce rate and exit rate 

### Data Preprocessing ### 

![flow](https://github.com/moggirain/e-commerce-purchase-prediction/blob/master/dataprocessing.png) 

The [code](https://github.com/moggirain/e-commerce-purchase-prediction/blob/master/Online_Shopper_Intention_V4.09.ipynb) could be found here 

### Modeling ### 
The [code](https://github.com/moggirain/e-commerce-purchase-prediction/blob/master/Modeling%20.ipynb) could be found here 

#### Pipeline #### 

![](https://github.com/moggirain/e-commerce-purchase-prediction/blob/master/ModelingPipeline.png) 

#### Evaluation Metrics #### 

![evaluation](https://github.com/moggirain/e-commerce-purchase-prediction/blob/master/Evaluation%20Metric.png) 

#### Result ####

![result](https://github.com/moggirain/e-commerce-purchase-prediction/blob/master/Baseline.png) 

#### Model Comparision #### 
![comparison](https://github.com/moggirain/e-commerce-purchase-prediction/blob/master/ModelComparison.png) 

#### Feature Importance ####
![comparison](https://github.com/moggirain/e-commerce-purchase-prediction/blob/master/FeatureImportance.png)

### Further Study ### 

1. Better interpretation of results 
   - Soluton: [SHapley Additive exPlanations](https://christophm.github.io/interpretable-ml-book/shap.html#shap-feature-importance) 
   
2. Other hyperparameter tuning 
   - Solution: [Bayes Optimization](https://towardsdatascience.com/a-conceptual-explanation-of-bayesian-model-based-hyperparameter-optimization-for-machine-learning-b8172278050f)
   
3. Better Visualization 
   - Solution: 
   [Plotly Dash](https://dash-gallery.plotly.host/Portal/)
   


