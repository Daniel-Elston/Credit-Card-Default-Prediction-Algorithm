
<p align="center">
  
  <img width="555" alt="image" src="https://user-images.githubusercontent.com/98388088/158099842-37825d56-8f39-4de9-bf08-1981bf63fb4f.png">

</p>
<hr>


<h1 align='center'> Credit Default Prediction Algorithm in Bank Marketing Dataset </h1>

<hr>


## Table of contents
- [Status and Details](#status-and-details)
- [Technology](#technology)
- [Introduction](#introduction)
    - [Project Description](#project-description)
    - [Objectives](#objectives)
- [Data Science Methodology](#data-science-methodology)
    - [Problem Formulation](#problem-formulation)
    - [Data Engineering Methods](#data-engineering-methods)
    - [Modeling](#modeling)
    - [Deployment](#deployment)
- [Conclusions](#conclusions)
- [Contributing Members and Contacts](#contributing-members-and-contacts)


## Status and Details
- **Project Status**: [Completed]
- **Date Coded**: 07/03/22
- **Link to Raw Data**: https://archive.ics.uci.edu/ml/machine-learning-databases/00222/
- **Link to Academic Paper**: [Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014
- **Notes**: This analysis was conducted as a technical assessment for a high profile Data Science company.


## Technology
- **Language**: Python 3.6.9
- **Libraries**: pandas, numpy, matplotlib, seaborn, scipy, sklearn, xgboost
- **Set up File**: N/A


## Introduction
The purpose of this project is to reduce the profit loss due to credit card default of Lisbons central bank. A large proportion of money in the economy is created by banks. A large portion of the money generated by banks is through interest on debt. Should someone default on their credit card, not only does the bank lose money from interest, but they do not get their original investment back. 


### Project Description
The dataset used for this analysis consists of many bank customers details (anonymized). Originaly, the dataset was designed for a Lisbon central banks telemarketing campaign. Therefore much of the raw data is either irrelevant or highly bias. Furthermore, highly important features such as salary were in the form of categorical data. Nevertheless, due to the size of the dataset and the presence of  relevant feautures, analysis can be conducted. 

Correlation matrices, box plots and histograms have been used to clearly visualise relationships between customer details and default rates. Classification models were trained on a large preprocessed dataset, yielding suprisingly accurate results. The XGB classifier was deemed the best model for testing. An accuracy of 79% was observed. More importantly, a recall of 96% was achieved.


### Objectives
- The algorithm was designed to identify customers who could potentially default on given credit cards.
- Identify bias in the dataset and make suggestions on how to mitigate any further bias in data gathering techniques.


## Data Science Methodology
The below subsections outline the standard methodology of data scientists.


### Problem Formulation
Banks can reduce loss of profits by identifying customers who could potentially default on given loans or credit. It can be seen in the above [report](https://github.com/Daniel-Elston/Credit-Card-Default-Prediction-Algorithm/blob/main/Default_Prediction_Report.pdf) that defaulters cost the city of Lisbon as much as 500,000 euro in 1997. That figure is likely greater now. In order to see financial growth of both the bank and the economy, defaulter classification algorithms must improve. 


### Data Engineering Methods
- Data Transformation
- Data Preprocessing
- Inferential Statistics
- Data Visualisation
- Machine Learning
- Predictive Modelling


### Modeling 
The preprocessed dataset was statistically analysed. Using principle component analysis, dimensionality reduction was applied before finally training the model. Many classifiers were used, but the XGB classifier was deemed the most well suited for the needs of this analysis. The model had a high accuracy with a relatively low run time. The model showed clear results relating to the classification of credit defaulters. No over/underfitting was observed.


### Deployment
The model was deployed on a previously unseen, transformed test dataset. The model classified defaulters with 79% accuracy and 96% recall. Therefore, when data is collected correctly, the model will perform well in its commercial financial enviroment. When collecting customers raw data, should bias be removed completely, the model will perofrm even better.


## Conclusions
An accuracy of 79% and recall of 96% has been achieved with a highly biased dataset, that was designed for another purpose. This recall value suggests a model that could be deployed in its intended enviroment. The above [report](https://github.com/Daniel-Elston/Credit-Card-Default-Prediction-Algorithm/blob/main/Default_Prediction_Report.pdf) shows a confusion matrix for the algorithm. The matrix shows that of the 76% correctly identified defaulters, the algorithm classifies 96% of them as defaulters. Finally, this shows the bank would miss out on around 24% of non-defaulters to give credit cards too, therefore earning interest. But whats of greater value is only 4% of defaulters are misclassified, greatly reducing loss.


## Contributing Members and Contacts
**Team Lead: [Daniel Elston](https://github.com/Daniel-Elston)**

|Name     |  GitHub Handles   |  
|---------|-----------------|
| Daniel Elston | [Git DE](https://github.com/Daniel-Elston)   |

Please feel free to contact me if you have any questions, require any further information or wish to contribute.<br/>
Email 1: delstonds@outlook.com<br/>
Email 2: ec21024@qmul.ac.uk
