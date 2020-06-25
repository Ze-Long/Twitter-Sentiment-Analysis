## Twitter Sentiment Analysis

![alt tag](https://media.sproutsocial.com/uploads/2019/08/twitter-stats.svg)

This data originally came from Crowdflower's Data for Everyone library. This is one of the side projects I've done. I want to know what makes the passengers satisfied or unsatisfied with their flight. This is a simple sentiment analysis using natural language processing techniques.

## Word Cloud
Random Forest

LightGBM

Extreme Gradient Boosting

Multilayer Perceptron
  
Long Short-Term Memory
  
## Model Performance

![alt tag](https://github.com/Ze-Long/Nintendo-Switch-Sales-Forecasting/blob/master/Images/RandomForest.png)

![alt tag](https://github.com/Ze-Long/Nintendo-Switch-Sales-Forecasting/blob/master/Images/XGBoost.png)

![alt tag](https://github.com/Ze-Long/Nintendo-Switch-Sales-Forecasting/blob/master/Images/MLP2.png)

![alt tag](https://github.com/Ze-Long/Nintendo-Switch-Sales-Forecasting/blob/master/Images/LSTM2.png)

## Final Prediction

These 4 models achieve similar performance so I combine them together. I calculate the reciprocals of their MAEs and normalized them in order to give the models their weights respectively. The final result is the weighted sum of their prediction, which is 56638. This number is closest to the actual sales amount so I won 1st place in this competition.
