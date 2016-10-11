# Introduction To AI

### Modeling Problems

* Data Classification
* Regression Analysis
* Clustering
* Time Series

#### Data Classification

Attempts to classify the input data. Classification uses supervised training where the user provides data and expected results. The result of data classification is a class.

**Supervised training always requires known data. The goal is that the algorithm will be capable of identifying unknown data once trained**

Fisher's Iris Data set is an example of data classification.

#### Regression Analysis

The output of regression analysis is not a class, but instead it's a number. Regression analysis attempts to calculate a result based off of the input data.

An example of regression analysis would be predicting the MPG of a vehicle.

http://www.heatonresearch.com/wiki/MPG_Data_Set

#### Clustering

Similar to classification. Clustering algorithms take input data and place it into clusters. The programmer typically sets the number of clusters before training the algorithm. The algorithm places similar items together without any guidance from the user. Clustering is useful when you have no expected output, which means that it's unsupervised.

Clustering gives the algorithm the freedom to find order in the data, whereas classification attempts classify an input based on known data.

Clustering and classification also handle new data differently. Clustering makes no provision for new data. If you want to add new data to the existing groups you must recluster the entire data set.

#### Time Series

It is sometimes necessary to consider several inputs from a time span when working with machine-learning. For example predicting the current price of stock might require several days of input.

### Modeling Input and Output

All machine learning algorithms accept input and produce output. The output is affected by the algorithms short-term and long-term memory.

The input and output of machine learning algorithms are vectors. A vector is an array of decimals like the following : 

    var input = [ -0.23, .51, 0.0];
    var output = [ .284, .002];

The number of inputs and outputs typically do not change. The input values can be considered parameters. The example above has 3 inputs, and produces 2 outputs.

### Understanding Training

#### Evaluating Success

Evaluation is the process of grading (scoring) a trained algorithm. This score can be used to guide the algorithm in order to maximize or minimize the score.

#### Batch and Online Training

Batch and online training refer to training sets. Online training occurs after each element of a training set.

#### Supervised and Unsupervised Training

Supervised training happens when you know the desired output of the algorithm. Unsupervised training occurs when you don't know the output of the algorithm.

#### Stochastic and Deterministic Training

A deterministic training algorithm will always perform the exact same way, given the same input. Whereas stochastic training makes use of random numbers. This will cause the algorithm to train differently, even with the same starting state.