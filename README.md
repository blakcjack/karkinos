# Karkinos

Karkinos is a part of DAAC (Data as a Content) project. This project stores all raw files (image, code, etc) for each project (portfolios) I created.

## DATA ANALYSIS FLOW STANDARD

Data analysis in this part is limited to descriptive, diagnostic or prescriptive analysis.

-   **Problem Statement**. Problem statement is about what is the problem that we are trying to find out. In data analysis, it is crucial to have a question about what will be found out.

-   **Data Collection**. Data collection is a process to collect the data, either it is through API or direct downloading the data from the source.

-   Data Description. A short description about the field of the data. This will give short but powerful understanding about the data field.

-   Data Exploration. The technique to generate data exploration in this section is by answering some business question, and then display the data to answer them. The question asked should support the main problem statement.

-   Data finding and explanation.

-   Conclusion. Conclusion is important part of the data analysis. Without any conclusion the analysis is just an exploration without any mean.

## DATA MODELING FLOW STANDARD

In this project, the following flow is used for every data task.

### 1. Data Collection

Data collection is the first step in data world. The source of data to be collected can be as follow:

-   Extract data from database

-   Scraping data from internet

-   Pooling data from publication/printed material

### 2. Data Understanding

In this part, the data will get summarized on a top level to understand about what is the data about, how many features they have, what each feature is talking about, etc.

### 3. Data Cleaning

Data cleaning comes after collecting. The raw data we collected may contain various data problem, such as missing values in the data, there is error that causing outlier to appear, wrongly assigned data types where some factor assigned as numeric, etc. The process in this basic data cleaning is as follow:

-   Handling missing values. The missing values can be either imputed or deleted

-   Handling outlier. Outlier come for a reason. It can be triggered by some errors or mistakes, it can be there due to some anomaly, or it is just effect of seasonality that causes the data to be outlier.

-   Data conversion. Some data are assigned as string or character. Meanwhile, most of the machine learning model not accepting this type of data. Hence those data needs to be converted into something else.

### 4. Exploratory Data Analysis (EDA)

EDA is one important key to get deeper and further understanding about the data In this part, we can divide the analysis into three type of analysis:

-   Univariate analysis. In this type of analysis, every single data is explored and get deeper understanding. In this part, we can check the distribution of the data, check if the outlier needs to be normalized or accept the values as it is, and so on.

-   Bivariate analysis. In this type of analysis, each independent variable will be compared against the target (dependent variable).

-   Multivariate analysis. Sometimes, we know that some independent variables have an effect towards the dependent variable. In order to make sure their relationship, we can use multivariate analysis to explain that.

### 5. Data Preprocessing

Data preprocessing is meant to preprocess the data after getting explored. The following things will be done in data preprocessing.

-   Data splitting. in this process, the data needs to be splited into 3 parts.

    -   Data training. This type of data is the data that we are familiar with. We assume that this data is the most known data where we will build the model using this data. Since, we assume that we only have this data from beginning, then will apply any preprocessing on this data.

    -   Data testing. This type of data is used to optimize the data model and become the first stage of testing when we assume that this data is unseen. Usually, we will use this data to see, whether the optimization we applied in the model brings better impact or not. this type of data is also used to select the best model that we will use.

    -   Data validation. This type of data is used in the final stage to measure the final performance of the final model before getting deployed in the production.

-   Feature creation. Sometimes, new feature is needed to ensure the model can perform better. hence some features need to be manually created.

-   Feature engineering. In most cases, this step is the part of data preprocessing and i usually put under data preprocessing umbrela. But, I will zoom into this step to expand the section to be more detail.

    -   Feature extraction : this step will create new feature based on existing feature.

    -   Feature transformation : For some algorithms, feature transformation is very crucial. For example, the algorithm that uses gradient descent to optimize the cost function, it will be faster to converge when the numerical values are transformed into unitless data. Here are some transformation that can be applied to the data:

        -   Scaling

        -   Normalization

        -   Dummify

        -   Label encoding

    -   Feature selection : this step will apply some algorithm to choose the best features to be used into the model.

### 6. Data Modeling

Data modeling is the final part of the machine learning flow. It consists of the following steps:

-   Model Training. Model training is a process where

-   Model evaluation phase 1.

-   Model Selection. Have a good data is one thing. Another important thing is have a good and suitable machine learning model to work with. Choosing a model can be a very tricky since it can lead to overfitting or underfitting condition that might have no end.

-   Model tuning.

-   Model evaluation phase 2.

-   Model deployment.
