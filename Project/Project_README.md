# Fake News Detection 
___
[how to edit .md](https://github.com/darsaveli/Readme-Markdown-Syntax)
___
#### **Team**: Janka Gordos, Nicola Sagay, Princess, Rose Song, Victoria
___
## INDEX

* Executive summary
 * Introduction
 * Methodology
 * Results
 * Conclusion
___
## EXECUTIVE SUMMARY (STEPS)

* Summary of methodologies
 * Collecting data 
 * Data cleaning
 * Merging datasets
 * Exploratory Analysis using Pandas, Numpy
 * EDA with Visualisation
 * Machine Learning Prediction (Classification)
* Summary of all results
  * Exploratory Analysis Results
  * Visualisation Results
  * Predictive Analysis Results
___
## INTRODUCTION

* Project background and context
  * Fake News recognition is one of the most challenging cybersecurity problems of our time. We have never been able to access information so easily before. The widespread use of fake news can cause serious social and political damage. 
  * The United Nations reported on the role Facebook played in fueling genocide in Myanmar. Or more recently, the spread of fake news related to COVID-19 has put global health at risk, of which the WHO released a warning explaining the effects of misinformation related to the pandemic.
  * More and more research focuses on the necessity to identify the impact of fake news, come up with solutions, and reduce the spread of fake news. 

* Problem we want to find answers
  * Our aim is to make an analysis of the detection of fake news and to explore different machine learning models to find the most effective one.
___
## IMPLEMENTATION AND EXECUTIONS (Methodology)

* Development approach
  * Agile development
* Data collection methodology
  * Kaggle API
* Perform data cleaning
  * Dealing with Missing Values, Feature Engineering, Scaling 
* Perform exploratory data analysis (EDA) using Pandas, Numpy, Matplotlib
* Perform predictive analysis using classification models
  * Sklearn (Logistic Regression, SVM, Binary Tree)
  * Parameters tuning, cross validation
___
## DATA COLLECTION

* Kaggle API set up
  * Install kaggle library
  * Genrate API token through Kaggle account
  * Copy token into .kaggle
  * Search for dataset in  !kaggle datasets list -s 'fake-news'
  * Download chosen dataset !kaggle datasets download -d clmentbisaillon/fake-and-real-news-dataset
  * Unzip files and read using pandas (pd.read_csv()) or read using datatable (dt.read_csv(), can read from .zip)
___
## DATA COLLECTION (screenshots)


___

