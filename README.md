# CS6140 Final Project

## Machine Learning Group 7 Project Proposal

Vineela Goli, Arjun Ramachandrula, Josh Jestine Chiriyankandath, Elizabeth Hwang

### Data Source

We’re planning to use the “Adult” Dataset from UCI’s Machine Learning Repository, which contains
demographic data about adults. The authors used the census information to predict whether the
person’s annual income was above or below $50k. <https://archive.ics.uci.edu/dataset/2/adult>

File Structure of our dataset:

1. adult.data					
2. adult.test					
3. adult.names					
4. old.adult.names		
5. Index						

### Objective

For our project, we’d like to take a thorough look at each of the variables in the dataset and evaluate
their correlation to income. We’ll primarily use matplotlib and seaborn for visualizing data. Our goal is to
analyze the model performance by implementing a couple of regression and a couple of classification
models. We will utilize existing models from the scikit-learn library instead of implementing from scratch.
We want to analyze each model’s performance on the data, tune parameters to get the best fit, and see
which features impact income the most.
Workload Distribution:
We will divide the variables from the dataset among the members. Each person will analyze the
correlation between their variables and the dependent variable (income) using visualization tools and
appropriate regression/classification models. Towards the end, we will come together to discuss our
analyses to produce a consolidated report about the dependent variable from our findings.
At this point, we should have a good idea of which features are the most important. Then, we can
experiment with training the models on specific subsets of features, and find which combinations of
classification methods and features yield the best prediction results.
Lastly, we aim to produce a report in the form of a paper, showcasing all the results we have obtained via our prior methods and findings.

### Evaluation

We will be using a set of metrics such as MSE, R^2, classification reports, etc. as well as visualization
techniques to evaluate our model performance.
