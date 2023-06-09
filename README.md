# News-Sentiment-Analysis-using-Spark

### Introduction
This project is aimed at analyzing the sentiment of news headlines collected over a period of four years (2017-2021). The dataset consists of 200k news headlines with sentiment, URL, date, and confidence level. The sentiment can be either positive or negative, and the confidence level indicates how strong the sentiment is.

Used Apache Spark for data preprocessing and analysis, and Azure Databricks for creating Spark clusters and stored the data in Azure Blob Storage. 

### Exploratory Data Analysis (EDA)
Performed EDA on the data to gain insights into the news headlines. Converted the date column to a date format and added additional columns such as year, month, quarter, and week of the year. Analyzed the number of positive and negative headlines per year and the number of days and weeks where there were more positive headlines than negative or vice versa. Analyzed the number of monthly positive and negative headlines per each year, and the months that had the most positive and negative headlines for each year.

Visualized the results using Matplotlib and plotted positive and negative headlines yearly, monthly, quarterly, and weekly.

### Count Vectorization and Modeling
Performed Count Vectorization on the text data (headlines) to prepare it for modeling. Built machine learning models using various algorithms such as Naive Bayes, Random Forests, Logistic Regression, and Support Vector Machines. Obtained the highest accuracy with SVM.

### Topic Modeling
Topic modeling is a technique used in natural language processing and machine learning to discover latent topics or themes within a large corpus of text documents. The goal of topic modeling is to identify patterns in the text data that are not immediately apparent to the human eye. This can be useful for many applications, such as content analysis, recommendation systems, and search engines.

The Latent Dirichlet Allocation (LDA) model is a generative statistical model used for topic modeling. It assumes that each document in the corpus is a mixture of multiple topics, and that each topic is a distribution over words in the vocabulary. The LDA model infers the topic mixture for each document in the corpus, as well as the word distribution for each topic, by iteratively estimating the parameters of the model using a statistical technique called Gibbs sampling.

Performed topic modeling using the Latent Dirichlet Allocation (LDA) model to identify the topics in the news headlines.

### Conclusion
In this project, I analyzed the sentiment of news headlines using Spark and Azure Databricks and performed EDA, visualized the results using Matplotlib, built machine learning models using various algorithms, and performed topic modeling using the LDA model. This project can be useful for anyone interested in analyzing news sentiment or building machine learning models for sentiment analysis.
