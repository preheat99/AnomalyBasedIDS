# Anomaly-based IDS

This is a project made using WEKA tools.

## Introduction

An Intrusion Detection System (IDS) is a system that observes traffic of the network for suspicious and strange activity and issues alerts when such an activity is identified.

Based on detection method,there are 2 types of IDS: Signature-based and Anomaly-based

In Anomaly-based detection method, the model learns what a normal traffic is. It is upto the user to define what a normal traffic is to the model.


## Dataset used

Dataset used is NSL-KDD.

The dataset contains 43 features per record, with 41 of the features referring to the traffic input itself and the last two are labels(whether it is a normal or attack) and Score(the severity of the traffic input itself ).

This dataset contains the info of the entire payload of each packet in the TCP dump format.


## CFS subset

CFS stands for Co-relational based Feature Selection. 

It is a type of Filter method for feature selection.

#### The CFS measure evaluates subsets of features on the basis of the following hypothesis:<br />
#### Good feature subsets contain features highly correlated with the classification, yet uncorrelated to each other.

I have used CFS subset with Forward selection feature selection.

## Multi-Layer Perceptron(MLP)

In MLP, we can have more than one linear layer. For eg, in a 3-layer network, first layer is the input, last layer is the input and second layer is the hidden layer. We can add as many hidden layers as we like, but the complexity increases.


## References

(1) J. Jabez, S. Gowri, S. Vigneshwari, J. Albert Mayan and Senduru Srinivasulu:     Anomaly Detection by Using CFS Subset and Neural Network with WEKA Tools

(2) Mark A. Hall: Correlation-based Feature Selection for Machine Learning

(3) T. Karthikeyan and P. Thangaraju : Best First and Greedy Search Based CFS-      Naïve Bayes Classification Algorithms for Hepatitis Diagnosis

(4) Prof. Mitesh M.Khapra on NPTEL's Deep Learning course.
