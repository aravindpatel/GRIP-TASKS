# **Task 7 : Stock Market Prediction using Numerical and Textual Analysis**

**GRIP @ The Sparks Foundation**

### **Author:** Aravind Patel Tulisagari
### Data Science & Business Analytics Intern
**July 2021**

Here, main objective is to create a hybrid model for stock price/performance 
prediction using numerical analysis of historical stock prices, and 
sentimental analysis of news headlines. 

For this purpose, I have downloaded the dataset of the last 17 years' historical stock prices of TCS (Tata Consultancy Services)  from [finance.yahoo.com](https://in.finance.yahoo.com/)  and downloaded textual (news) data from https://bit.ly/36fFPI6.

## **Steps:**

# **Step 1: Stock Price Analysis and Prediction**

  ### Step 1.1: Importing Required Libraries for numerical analysis and prediction of stock prices
  Technical Stack used : 
  * Numpy Array
  * Matplotlib
  * Pandas
  * Keras
  * Scikit Learn
  * Math

### Step 1.2: Importing the Numerical dataset and performing Exploratory Analysis
### Step 1.3: Creating a dataframe for storing the Closing stock data per day
### Step 1.4: Data Normalization and Division into Training and Test sets
### Step 1.5: Creating a LSTM Neural Network Model for Numerical Analysis
### Step 1.6 : Making Predictions of the Model

# **Step 2: Textual Data(News Headlines) Analysis**

### Step 2.1: Importing Required Libraries for Textual (News Headlines) analysis
### Step 2.2: Importing the Textual dataset and performing Exploratory Analysis
### Step 2.3: Representing number of headline text (News Headline) per city
### Step 2.4: Representing Number of News Headlines per year and per city
### Step 2.5: Sentiment Analysis of News Headlines

# **Step 3: Creating Hybrid model for stock price/performance prediction using numerical analysis of historical stock prices, and sentimental analysis of news headlines**

### Step 3.1: Importing Required Libraries
### Step 3.2 : Importing the Numerical and Textual dataset
### Step 3.3: Creating Hybrid data from Numerical and Textual Data
### Step 3.4: Performing Sentiment Analysis on Hybrid Data
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Step 3.4.1: Sentiment Analysis using TextBlob
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Step 3.4.2: Adding subjectivity and polarity Scores to Textual Data (News Headlines)
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Step 3.4.3: Visualizing the polarity and Subjectivity scores
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Step 3.4.4: Performing Sentiment Analysis over the news Headlines of Hybrid Data


### Step 3.5: Training and Testing the Models for Stock Price/Performance Analysis
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Step 3.5.1: Stock Price/Performance analysis using Logistic Regressor Model
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Step 3.5.2: Stock Price/Performance analysis using Random Forest Model
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Step 3.5.3: Stock Price/Performance analysis using Decision Tree Model
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Step 3.5.4: Stock Price/Performance analysis using Linear Discriminant Analyser Model
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Step 3.5.5: Stock Price/Performance analysis using AdaBoost Model
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Step 3.5.6: Stock Price/Performance analysis using Logistic Gradient Boosting Model

# **Conclusion:**

Here, I have used six different Neural Network models to carry out the analysis and prediction of stock price/performance and train them with Hybrid data generated from Numerical data (i.e. Last 17 years Stock price/performance records of TCS (Tata Consultancy Service)) and Textual data (i.e.India News Headlines data).

I have found the accuracy of each model as mention below:

1.	Logistic Regression Model: 83.22032395127025 %
2.	Random forest Model: 81.19986132499133 %
3.	Decision Tree Model: 79.30759245672454 %
4.	Linear Discriminant Model: 83.4484927155308 %
5.	AdaBoost Model: 85.35849908490619 %
6.	**Gradient Boosting Model: 85.5213615950851 %**

In the end, we can see that Gradient Boosting Model gives more accuracy(i.e. 85.5%) as compared to all other models. Gradient Boosting Model has 85.5% accuracy which means it performs better on Analysis and prediction of Stock price/performance than the other 5 Neural Network Models.
