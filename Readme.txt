## Project Portuguese Bank Marketing
The objective of this task is to compare various classifiers in order to develop the best predictive model to determine the likely outcome of the bank's marketing campaigns, and use the insights gleaned to enhance the effectiveness of future campaigns

## Table of Contents
- Description
- Jupyter Notebook
- Data
- Results
- Visualizations
- Contact Information 

## Description
This project analyzes a dataset related to 17 marketing campaigns for a Portuguese bank. These campaigns occurred between May 2008 and November 2010 and represented a total of 79,354 contacts.

## Jupyter Notebook
Run this [Jupyter notebook] (https://github.com/rsavage2201/Portuguese-Bank-Marketing/blob/main/Portuguese%20Bank%20Marketing.ipynb) to see the analysis 

## Data
The project uses a provided dataset (bank-additional-full.csv). This dataset contains 41,187 entries. 

## Data Cleaning 
In order to ÒcleanÓ the data, the categorical features were encoded, and the numerical features scaled. It did not appear necessary to drop or significantly alter a lot of the data in this case, as reasonably accurate models were generated in a reasonable timeframe. 


## Key Findings
The key findings of this analysis are that call duration, the euribor rate and age of the candidates appear to be the most relevant features, as outlined in [this plot] (https://github.com/rsavage2201/Portuguese-Bank-Marketing/blob/main/top_10_feature_importance.png).

In comparing the performance of the classifiers - Logistic Regression, Decision Trees and KNN models all provided effective models (as shown below), while in this instance using SVMs was less effective..

Model Performance Results:
              Model  Train Time (seconds)  Train Accuracy  Test Accuracy
Logistic Regression                7.9061          0.9103         0.9109
      Decision Tree                1.6952          0.9172         0.9153
                KNN                3.4686          0.9218         0.9090
                SVM              436.5480          0.8862         0.8872

Best Parameters for Each Model:
Logistic Regression: classifier__C: 1, classifier__max_iter: 3000, classifier__solver: lbfgs

Decision Tree: classifier__max_depth: 5, classifier__min_samples_leaf: 10, classifier__min_samples_split: 10

KNN: classifier__metric: euclidean, classifier__n_neighbors: 11, classifier__weights: uniform

SVM: classifier__C: 1, classifier__gamma: 0.01, classifier__kernel: linear

Importantly, this dataset only included those individuals that had been touched by the marketing campaigns, and it would be important to capture come counterfactual data and compare these outcomes with individuals that took out loans but were not touched by marking.
 
## Visualizations
The following visualizations are also included
- model_comparison.png
- model_comparison.png 
- model_performance_comparison.png

## Contact Information
You can contact me on (rowland_savage@yahoo.com)





