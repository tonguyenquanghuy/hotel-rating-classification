# HOTEL RATING CLASSIFICATIONS
## GOALS OF THE PROJECT
Manually analysing each review is labour-intensive and inefficient to capture the overall picture of customer satisfaction. Therefore, this project aims to resolve this problem by automating review classification using machine learning, sorting them into positive or negative categories. This automation allows businesses to take targeted actions (such as addressing negative reviews to reduce churn or engaing satisfied customers with personalised offers), ultimately improving marketing strategies, customer satisfaction, and overall decision-making.


## DATASET
The dataset is sourced from a large open TripAdvisor review dataset available on Kaggle, consisting of 878,561 rows and 19 attributes. To reduce processing time and cost, we work with a subset of these instances.


## METHODS
In this project, preprocessing techniques such as text cleaning, tokenisation, and lemmatisation are applied to prepare customer reviews for analysis, ensuring that review texts are standardised for analysis. Descriptive techniques like word clouds and rating distributions are used to highlight key themes in guest experiences via their reviews, which help uncover sentiment trends among hotel guests. Exploratory methods, including correlation analysis and visualisations, identify key factors that influence customer ratings.


In this project, predictive techniques play a central role in automating review classification. For sentiment classification, baseline models like Logistic Regression and Naive Bayes are employed to classify hotel reviews as positive or negative. To enhance accuracy, more robust models such as Support Vector Machines (SVM) are used. Additionally, deep learning models like LSTM, GRU, or Transformer-based models (e.g., BERT) will provide advanced sentiment analysis, capturing the context and nuances of guest reviews. For rating prediction, hybrid models combine sentiment classification outputs with numerical features, enabling the prediction of ratings to better inform hotel decision-making. 

