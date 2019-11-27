# Yuvoh Solution - Airbnb Price Prediction.

The dataset contains data of Airbnb listing details. I've used this data to predict the price based on other parameters.

## Dataset

Dataset used in this project can be found [here]( http://data.insideairbnb.com/united-kingdom/england/london/2019-07-10/data/listings.csv.gz).

## Install

### &nbsp;&nbsp;&nbsp; Supported Python version
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Python version used in this project: 3.6.8

### &nbsp;&nbsp;&nbsp; Libraries used

> *  [Pandas](http://pandas.pydata.org) 0.24.2
> *  [Numpy](http://www.numpy.org) 1.16.2
> *  [Matplotlib](https://matplotlib.org) 3.0.2
> *  [Scikit-learn](http://scikit-learn.org/stable/) 0.20.3
> *  [Seaborn](https://seaborn.pydata.org) 0.9.0
> *  [Keras](https://keras.io/) 2.2.4
> *  [vaderSentiment](https://pypi.org/project/vaderSentiment/) 3.2.1

## Approach
1. Importing the libraries and data.
2. Analyse the features, Feature Extraction.
3. Preprocessing and Cleaning.
4. Replace Sentiment Analysis Score for Summary Feature.
5. Exploratory Data Analysis (EDA)
6. Data Normalization
7. Build, Train and Test the models.
8. Conclusion.

## Code

The code used in this project is inside **Final_Yuvoh_Solution.ipynb**.

## Run

To run this project you will need some software, like Anaconda, which provides support for running .ipynb files (Jupyter Notebook).

## Conclusion

After analysing the features provided, we have dropped some of the features which either have more NAs or of Single category or features which are highly correlated with other features, We have replaced Sentiment Analysis Score for Summary Feature. We've also drawn relevant insights from our **Exploratory Data Analysis (EDA)** then have normalized and modelled the data over various regression algorithms and clearly see that **Random Forest Regressor** provides the best result with a **mean squared error** of **0.1422** and **r2_Score** of **0.7629**
