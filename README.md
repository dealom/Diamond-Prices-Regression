# Diamond-Prices-Regression
I analyze and use different regressor models on a diamond dataset from kaggle (https://www.kaggle.com/datasets/shivam2503/diamonds).
After cleaning the data, I use the volume of the diamond and the carat as features for my model to predice the price of the diamond.
Visualizations of the metrics of each model:
![](https://i.imgur.com/fOPmzyx.png)
![](https://i.imgur.com/WmHjq8a.png)
![](https://i.imgur.com/WmHjq8a.png)

I used 10 regressor models from the sklearn library. The green bars are from ensemble models. The top 3 for each metric were ensemble models. The Passive Aggressive model have the worst metrics. The Gradient Boosting model is the best since it has the lowest errors and highest r2 score.