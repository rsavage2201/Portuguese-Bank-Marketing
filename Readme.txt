## Project Portuguese Bank Marketing
The objective of this task is to compare various classifiers in order to develop the best predictive model to determine the likely outcome of the bank’s marketing campaigns, and use the insights gleaned to enhance the effectiveness of future campaigns

## Table of Contents 
- Description
- Jupyter Notebook 
- Data
- Results 
- Visualizations
- Contact Information 

## Description
This project analyzes a dataset related to 17 marketing campaigns for a Portuguese bank. These campaigns occurred between May 2008 and November 2010 and represented a total of 79,354 contacts.

## Jupyter Notebook
Run the below Jupyter notebook to see the analysis

## Data
The project uses a provided dataset (bank-additional-full.csv). This dataset contains 41,187 entries. Call duration, the Euribor rate and age of the candidates appear to be the most relevant features, as outlined in this graph.

## Data Cleaning 
In order to “clean” the data, the categorical features were encoded, and the numerical features scaled. It did not appear necessary to drop or significantly alter a lot of the data in this case, as reasonably accurate models were generated in a reasonable timeframe. 


## Key Findings
The key findings of this analysis are included in the included report Project Portuguese Bank Marketing Report. 

In summary, Logistic Regression, Decision Trees and KNN models all provided effective models, with a test accuracy of 0.9109, 0.9153 and 0.9090, while using SVMs was less effective only producing an accuracy of 0.8872.

Importantly, this dataset only included those individuals that had been touched by the marketing campaigns, and it would be important to capture come counterfactual data and compare these outcomes with individuals that took out loans but were not touched by marking.
 
## Visualizations
The following visualizations are also included
- model_comparison.png
- model_comparison.png 
- model_performance_comparison.png

## Contact Information
You can contact me on (rowland_savage@yahoo.com)





