Abstract:
This project delves into understanding the patterns in transactions where credit card fraud might have taken place, providing exploratory data analysis and insights based on the dataset provided. Further, we try and develop or feature engineer a model that helps us a determine whether a transaction is fraudulent or not 	based on the data provided.
Problem Statement:
Credit cards have been a revolutionary way of making payments quick and secure but there are still ways that the data of customers might be stolen and can be used for fraudulent purposes. Since the techniques are so advanced, banks often struggle to tell apart the legitimate transactions from the fraudulent ones. One more prominent problem that arises that while studying credit card fraud detection is the unavailability of proper datasets to train models on due to privacy and security reasons. Hence, in this project we aim to understand the patterns that are seen in credit card frauds and develop a model to help us better differentiate legitimate transactions from fraudulent ones. The dataset used here is simulated data due to reason explained before. 
Dataset:
About the Dataset
This is a simulated credit card transaction dataset containing legitimate and fraud transactions from the duration 1st Jan 2019 - 31st Dec 2020. It covers credit cards of 1000 customers doing transactions with a pool of 800 merchants.
Source of Simulation
This was generated using Sparkov Data Generation | Github tool created by Brandon Harris. This simulation was run for the duration - 1 Jan 2019 to 31 Dec 2020. The files were combined and converted into a standard format.

Approach and Methodology:

Results & Evaluation:
Fraud is rare → The dataset is highly imbalanced, with fraud cases making up only a small fraction of total transactions.
Amount patterns → Fraudulent transactions tend to involve higher amounts than legitimate ones, with a long-tailed distribution.
Time-of-day effect → Certain hours (often late night or early morning) show a higher fraud rate despite having fewer overall transactions.
Category risk → Some merchant categories have disproportionately high fraud rates, even if they’re not the most frequent.
Correlation check → Most numeric variables have low correlation with fraud, but amt and time-based features show some predictive potential.
Missing data → Minimal missing values, so no heavy imputation is needed.

Member-wise Contributions:
Aarya:
A major part of my contribution was transforming the timestamp field into several useful components: year, month, day, hour, and weekday. These variables allow models to learn temporal patterns in fraudulent activity, such as higher likelihoods at night or on certain days. I also created a categorical “time bin” feature to group hours into segments (Night, Morning, Afternoon, Evening), which was then one-hot encoded to numerical form. This not only enhances model interpretability but also captures non-linear relationships between time and fraud probability. By the end of my work, was a well-documented resource ready for machine learning modelling. My work on feature engineering created variables that could improve predictive performance. This work lays a solid foundation for training models that can detect fraudulent transactions more effectively.
Jyotika:
Firstly, I tried and made sense of the data. I started by analysing the various field of the data, different kinds of relationship between them and what are the fields that will help me gain insights related to fraudulent transactions or what different fields can help us predict that. Then, I moved on to visualising various fields in various ways and try to gain meaningful insights from them. Making sense of those charts and exploring what could be the hidden meaning behind them so that we can understand the patterns/trends in the credit card fraud transactions.

Challenges Faced:
o	Finding and understanding relevant dataset was one of the key challenges that we faced. Since real datasets were highly processed through various methods to maintain privacy, security and anonymity, we settled on a simulated dataset to gain our insights and train our model.
o	Using new interfaces/sites such as Google Colab and Kaggle was challenging at first, but with the right guidance and practice we were able to comfortably use the platforms to our advantage. 
Learnings:
We learnt ways to gather information and data and learnt how to separate useful data from the non- useful ones. Also, we got to know about the various sources of datasets and how to extract them.
Through this process, we strengthened our skills in Python-based data science workflows such as Pandas, NumPy, Matplotlib and Seaborn, mastered techniques for handling imbalanced datasets thus deepening understanding of feature engineering for temporal data. 
We also improved our ability to communicate findings through clear, impactful visualizations through various charts and graphs. Thus, by the end of the project were successfully understand the dataset, make charts and graphs from it and also derive useful insights from it thus able to determine with the use of model whether a said transaction is fraudulent or not.
Future Scope:
References:
Major points of references are as follows:-
i.	Google
ii.	Kaggle
iii.	ChatGPT or similar models
All these resources have provided extensive support and understanding throughout the  course of completion of this project in various ways.  
