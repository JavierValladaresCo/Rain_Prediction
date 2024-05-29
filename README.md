# Rain in Australia

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