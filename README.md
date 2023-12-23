# Karkinos

Karkinos is a part of DAAC (Data as a Content) project. This project stores all raw files (image, code, etc) for each project I created.

## DATA ANALYSIS FLOW STANDARD

Data analysis in this part is limited to descriptive, diagnostic or prescriptive analysis.

-   **Problem Statement**. Problem statement is about problem that we are trying to answer. In data analysis, it is crucial to have a question about what will be found out.

-   **Data Collection**. Data collection is a process to collect the data, either it is through API or direct downloading the data from the source.

-   **Data Description**. A short description about the field of the data. This will give short but powerful understanding about the data field.

-   **Data Exploration**. The technique to generate data exploration in this section is by answering some business question, and then display the data to answer them. The question asked should support the main problem statement.

-   **Conclusion**. Conclusion is important part of the data analysis. It is strongly recommended to have conclusion in each analysis.

## DATA MODELING FLOW STANDARD

For modeling standard, the following flow will be applied

### 1. Data Collection

Data collection is the first step in data modeling world. The source of data to be collected can be as follow:

-   Company's database system

-   Scraping from internet

-   Pooling data from publication/printed material

### 2. Data understanding

In this part, the data will get summarized on a top level to understand about what is the data about, how many features they have, what each feature is talking about, etc.

### 3. Data Cleaning

Data cleaning comes after collecting. The raw data we collected may contain various data problem, such as missing values, some error that causing outlier to appear, wrongly assigned data types where some factor assigned as numeric, some numeric assigned as character, etc. The process in this basic data cleaning is as follow:

-   Handling missing values. The missing values can be either imputed or deleted

-   Handling outlier. Outlier come for a reason. It can be triggered by some errors or mistakes, it can be there due to some anomaly, or it is just effect of seasonality that causes the data to be outlier.

-   Data conversion. Some data are assigned as string or character. Meanwhile, most of the machine learning model not accepting this type of data. Hence those data needs to be converted into something else.

### 4. Exploratory Data Analysis (EDA)

Exploratory data analysis or also known as EDA is a step to explore the data even deeper and further to find some pattern in the data. I usually divide the process into three part.

-    Univariate analysis. In this type of analysis, every single data is explored and get deeper understanding. In this part, we can check the distribution of the data, check if the outlier needs to be normalized or accept the values as it is, and so on.

-   Bivariate analysis. In this type of analysis, each independent variable will be compared against the target (dependent variable).

-    Multivariate analysis. Sometimes, we know that some independent variables have an effect towards the dependent variable. In order to make sure their relationship, we can use multivariate analysis to explain that.

### 5. Data Preprocessing

Data preprocessing is a step that we have to do after exploring the data and find some insights regarding the data condition. Here, more advance and complex calculation might be done to preprocess the data. The following things might be done in the data preprocessing part.

-   Data splitting. In this part, the data will be divided into three (3) parts.

    -   Data training

    -   Data testing

    -   Data validation

-   Feature creation

-   Feature engineering

    -   Feature extraction

    -   Feature transformation

        -   Feature scaling

        -   Feature normalization

        -   Dummify

        -   Label encoding

    -   Feature selection

### 6. Data Modeling

Data modeling is the final part of the machine learning flow. It consists of the following steps:

-   Model training. The first step in data modeling is training the data to fit the model that we have. There are so many machine learning model that might not work best for every situation but some of them might work best on our problem. Hence, fitting or training many model will help us finding the best one.

-   Model evaluation phase I.

-   Model selection

-   Model tuning

-   Model evaluation phase II

-   Model deployment.
