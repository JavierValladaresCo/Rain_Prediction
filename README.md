# Rain in Australia


The purpose of this project was to predict the days that precede a rainy day based on weather parameters. The key steps of this project were data transformation and balancing, as these two steps had a significant impact on the model's predictions. Finally, the model selected for this project was logistic regression, chosen to set a threshold probability and potentially improve the prediction results.

Rain in Australia was access in 27/05/2024 from https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package


![Rain Prediction](/Images/dataset-cover.jpg)

## Methods Used

- Machine Learning
- Data Visualization
- Data Classification
- Logistic Regression

## Technologies

- Python3
- Numpy
- Pandas
- Seaborn
- Scikit Learn

## Needs of this project

- Exploratory Data Analysis
- Statistical Modeling
- Data Transformation
- Data Balancing Strategy

## Conclusions

Finally, although the obtained metrics for the model were not what we expected, the data imbalance prevented us from improving the results. In the context of the problem, it is almost 80% more likely that it won't rain than it will, so it is difficult to train the model to accurately detect rain in the presence of this data imbalance.

Nevertheless, we improved the recall score for the category of interest by almost 15% compared to the naive model we set. Thus, the logistic regression model enhanced the data prediction as expected.

![Confusion Matrix](/Images/confusion-matrix.png)


## Challenges

The main challenges of this project were data imbalance and data transformation. The data imbalance skewed the prediction metrics, resulting in higher accuracy when trained with the imbalance data, but the recall for the category of interest was lower than 50%. On the other hand, data transformation significantly affected the model's predictions.

## What else i might have done?

I might have conducted a more detailed analysis of the data imbalance or approached this problem differently, such as treating it as an unsupervised problem. For example, I could have clustered the days based on different weather parameters patterns.

## Authors

- [@JavierValladaresCo](https://www.github.com/JavierValladaresCo)