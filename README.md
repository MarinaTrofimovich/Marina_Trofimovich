# [Project 1. Bank customer churn prediction](https://github.com/MarinaTrofimovich/Projects)

The project solved the problem of predicting the churn of bank customers. Using churned customers as a means of understanding why customers are leaving, I analyzed how and when churn occurs in a customer's life cycle with the bank and predicted the customer's churn. In the future the bank can use that information to put into place preemptive measures.

## Overview

- Identified and visualized which factors contribute to the customer churn (using pandas, numpy, matplotlib, seaborn, plotly).

- Built a prediction model which can classify if a customer is going to leave or not (trained Logistic Regression, k-nearesr neighbors, SVM, Random Forest and optimized them using GridSearchCV).

- Chose the best model in accordance with business goals (max recall).

## Tools

***Python version:*** 3.8.3.

***Packages:*** pandas, numpy, matplotlib, seaborn, plotly, sklearn 

![](/images/1.png)
![](/images/2.png)


# [Project 2. Sentiment analysis for the customer's task](https://github.com/MarinaTrofimovich/sentiment_analysis_yandex)

## Overview

- Created a tool that predict the sentiment of smartphone's review.

- Scraped over 23000 reviews on smartphones from the Yandex market using Python and Selenium.

- Performed data cleaning and selection and found the best way of labeling the data (final number of reviews 6500+).

- Optimized a pepiline "CountVectorizer(), TfidfTransformer(), LinearSVC()" using RandomizedSearchCV to reach the best model.

- Built a client facing API using Flask.

- The accuracy on customer's data is 95.5%.

## Tools

***Python version:*** 3.8.3.

***Packages:*** selenium, BeautifulSoap, sklearn, pickle, joblib, pandas, seaborn, nltk, json, flask.

## Flask API screenschots


![](/images/Screenshot1.png)
![](/images/Screenshot2.png)

