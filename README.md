![Header](/pics/header.png)

#### Table of Contents

[Project Overview](#project-overview)  
[Resources](#resources)  
[Objectives](#objectives)  
[Summary](#summary)   
[Challenge Overview](#challenge-overview)  
[Challenge Summary](#challenge-summary)  

## Project Overview
In this module, we explore and implement neural networks using the TensorFlow platform in Python. We discuss the background and history of computational neurons as well as current implementations of neural networks as they apply to deep learning. We discuss the major costs and benefits of different neural networks and compare these costs to traditional machine learning classification and regression models. Additionally, we practice implementing neural networks and deep neural networks across a number of different datasets, including image, natural language, and numerical datasets. Finally, we learn how to store and retrieve trained models for more robust uses. 

## Resources
- **Data Source:** [charity_data.csv](/Resources/charity_data.csv)
- **Software:** Jupyter Notebook, Python  

## Objectives 
- Compare the differences between the traditional machine learning classification and regression models and the neural network models.
- Describe the perceptron model and its components.
- Implement neural network models using TensorFlow.
- Explain how different neural network structures change algorithm performance.
- Preprocess and construct datasets for neural network models.
- Compare the differences between neural network models and deep neural networks.
- Implement deep neural network models using TensorFlow.
- Save trained TensorFlow models for later use.

## Summary  
Using our knowledge of machine learning and neural network model building, we created a binary classifier that is capable of predicting whether or not an applicant will be successful if funded by Alphabet Soup using the features collected in the provided dataset. 

## Challenge Overview  
We received a CSV containing more than 34,000 organizations that have received various amounts of funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization such as the following:
- **EIN** and **NAME**—Identification columns
- **APPLICATION_TYPE**—Alphabet Soup application type
- **AFFILIATION**—Affiliated sector of industry
- **CLASSIFICATION**—Government organization classification
- **USE_CASE**—Use case for funding
- **ORGANIZATION**—Organization type
- **STATUS**—Active status
- **INCOME_AMT**—Income classification
- **SPECIAL_CONSIDERATIONS**—Special consideration for application
- **ASK_AMT**—Funding amount requested
- **IS_SUCCESSFUL**—Was the money used effectively 

## Objectives
- Import, analyze, clean, and preprocess a “real-world” classification dataset.
- Select, design, and train a binary classification model of your choosing.
- Optimize model training and input data to achieve desired model performance. 

## Challenge Summary  
[AlphabetSoupChallenge.ipynb](/Notebook/AlphabetSoupChallenge.ipynb)  

**Import and characterize the input data.**  
- What variable(s) are considered the target for your model?
- What variable(s) are considered to be the features for your model?
- What variable(s) are neither and should be removed from the input data?  

**Preprocess all numerical and categorical variables.** 
- Combine rare categorical values via bucketing.
- Encode categorical variables using one-hot encoding.
- Standardize numerical variables using TensorFlow’s StandardScaler class.  

**Using a TensorFlow neural network design, create a binary classification model that can predict if an Alphabet Soup funded organization will be successful based on the features in the dataset.** 
 
**Compile, train, and evaluate our binary classification model.** 
- Final model loss metric
- Final model predictive accuracy  

**Optimize our model training and input data to achieve a target predictive accuracy higher than 75%.** 
  
**Create a new [README.txt](/Notebook/README.txt) file within the same folder as our AlphabetSoupChallenge.ipynb notebook.** 
- How many neurons and layers did you select for your neural network model? Why?
- Were you able to achieve the target model performance? What steps did you take to try and increase model performance?
- If you were to implement a different model to solve this classification problem, which would you choose? Why?
