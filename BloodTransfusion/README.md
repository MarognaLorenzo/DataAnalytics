# Blood Transfusion

## Project Description

This project was developed during the Erasmus period at the University of Utrecht. The main goal is to predict whether a blood donor will return to donate within the next month. The dataset used contains information about blood donors such as the number of donations made.

## Methodology

We approached the problem as a classification task, using various machine learning techniques to build predictive models. Some of the techniques are for example:

- **Stochastic Gradient Descent (SGD):** We implemented a classification model using the SGD algorithm, leveraging its computational efficiency on large datasets.

- **K-Nearest Neighbors (KNN):** We used the KNN model to explore neighborhood relationships in the data and make predictions based on the similarity between donors.

## Model Evaluation

We evaluated the models' performance using various metrics, including the F1 Score. This metric is particularly relevant as it takes into account both precision and recall, providing a more comprehensive assessment of the model's predictive ability.

## Parameter Tuning

To optimize the models' performance, we performed parameter tuning using cross-validation. This allowed us to find the best `C` value for the SVC algorithm, improving its F1 Score by 0.3 points.


## Dependencies

- `numpy`
- `pandas`
- `scikit-learn`
- `plotly`
- `seaborn`


## Contributions

We are open to contributions and improvements. Feel free to open issues or pull requests.
