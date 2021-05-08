[![forthebadge](https://forthebadge.com/images/badges/powered-by-netflix.svg)](https://forthebadge.com)

The code uses the python libraries [numpy](https://numpy.org/doc/stable/), [matplotlib](https://matplotlib.org/stable/contents.html), [pickle](https://docs.python.org/3/library/pickle.html), [pandas](https://pandas.pydata.org/docs/getting_started/overview.html) and [scikit-learn](https://scikit-learn.org/stable/). The official documentations of these libraries have been linked.

Task 1 has been answered in the report ([report.pdf](https://github.com/codelixir/linear-regression/blob/main/report.pdf)). The notebook ([code.ipynb](https://github.com/codelixir/linear-regression/blob/main/code.ipynb)) contains the remaining tasks. The train and test data used in these tasks are in the [data](https://github.com/codelixir/linear-regression/tree/main/data) directory. The report also contains observations and conclusions of tasks 2-4.

#### Contributors
[Dhruvee Birla](https://github.com/dhruvxx) and myself.

<br>
This assignment was done as a part of the Machine, Data and Learning course, Spring 2021.

---

## Task 1: Linear Regression

Understanding Linear Regression, and the method `LinearRegression.fit()`.

## Task 2: Calculating Bias and Variance

Resample and train the given data, and calculate the bias and variance of the trained model.

The bias and variance is calculated for the following class of functions:
```
y = ax + b
y = ax^2 + bx + c
y = ax^3 + bx^2 + cx + d
```
And so on till polynomial of degree 20.

## Task 3: Calculating Irreducible Error

Tabulating values of irredicible error for the models in Task 2, and observing the changes, if any.

## Task 4: Plotting Bias<sup>2</sup> - Variance Graph

Plotting the graph and evaluating which models are underfit or overfit, and then using this plot to determine the type of train and test data.
