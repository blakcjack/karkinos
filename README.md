# Karkinos

Karkinos is a part of DAAC (Data as a Content) project. This project stores all raw files (image, code, etc) for each project (portfolios) I created.

## DATA ANALYSIS FLOW STANDARD

Data analysis in this section is included data visualization, and exploratory data analysis.

* Problem Statement. Problem statement is about what is the problem that we are trying to fix. In data analysis, it is crucial to have the question about what I will be find out.

* Data Collection. Data collection is a process to collect the data, either it is through API or direct dowloading from the source.

* Data Description. A short description about the field of the data. This will give short but powerfull understanding about the data field.

* Data Exploration. The technique to generate data exploration in this section is by answering some business question, and then display the data to answer them. The question asked should support the main problem statement.

* Conclusion. Conclusion is important part of the data analysis. Without any conclusion the analysis is just an exploration without any mean.

## ML FLOW STANDARD

In this project, I applied ML flow standard for all ML projects.

### 1. Data Preparation

Data preparation is the first step in data world. It mainly talks about overall data. Its purpose is to preparing the data so it will be ready to be used as the new data source. This process consists of the following steps:

-   Data collection. Data collection is meant to collecting the data from many sources.

-   Data Exploration. This step is needed to explore the data even further. Not only to gain the fundamental understanding about the data but also to see the pattern in the data and to explain the data with the current issue I am trying to solve. This step is also known as EDA. This steps can be done by using two types of actions: Explore the whole variables data or by asking some questions to be answered using the data.

-   Data Splitting. After gaining some understanding about the data and the issue, I will split the data into training and testing set. To then will be fed into preporcessing needed to be applied.

### 2. Modeling

Data modeling is the final part of the machine learning flow. It consists of the following steps:

* Data preprocessing. Data preprocessing or also known as data wrangling is a step where I will apply some preprocessing step into the data. I will follow 4Cs:

    - Correcting : this step is used to correcting the data due to some errors. For example, the outlier due to human error.
    
    - Completing : the completing process will be useful to fill the missing values in the data.
    
    - Creating : at this step, new data/feature will be created to support the existing data/feature in a hope to increase the model performance.
    
    - Converting : converting step will convert the data into what it should be. For example, some categorical values wight be more appropriate to be stored as factor instead of string, and so on.

* Feature engineering. In most cases, this step is the part of data preprocessing and i usually put under data preprocessing umbrela. But, I will zoom into this step to expand the section to be more detail.
    
    * Feature extraction : this step will create new feature based on existing feature.
    
    * Feature selection : this step will apply some algorithm to choose the best features to be used into the model.
    
    * Feature transformation : For some algorithms, feature transformation is very crucial and might be very needed. For example, the algorithm that uses gradient descent to optimize the cost function, it will be faster to converge when the numerical values are transformed into unitless data and has some scales.
    
* Model Selection. Have a good data is one thing. Another important thing is have a good and suitable machine learning to work with. Choosing a model can be a very tricky since it can lead to overfitting and underfitting condition that might have no end.

* Model training.

* Model tuning.

* Model evaluation.

* Model deployment.
