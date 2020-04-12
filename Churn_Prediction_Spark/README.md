# Sparkify-Capstone-Project
Determine customer churn for a music streaming company called Sparkify.

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
This project uses the following software and python libraries

- [Python 3.6](https://www.python.org/download/releases/2.7/)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)
- [Pyspark-2.4.1](https://spark.apache.org/docs/latest/api/python/index.html)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)
  

## Project Motivation<a name="motivation"></a>
Imagine you are working for music streaming company like Spotify or Pandora called Sparkify.Millions of users stream thier favorite songs everyday. Each user  uses either the Free-tier with advertisement between the songs or the premium Subscription Plan.Users can upgrade, downgrade or cancel thier service at any time.Hence, it's crucial to make sure that users love the service provided by Sparkify. Every time a users interacts with the Sparkify app data is generated. Events such as playing a song, logging out, like a song etc. are all recorded. All this data contains key insights that can help the business thrive. The goal of this project is then to analyse this data and predict which group of users are expected to churn - either downgrading from premium to free or cancel thier subscriptions altogether.

In this project we'll be performing the following tasks:
1. Data Exploration
    - Learn about the data
2. Define Churn and label data based on churn definition
    - Determine which feature or feature value can be user to defin churn
3. Feature Engineering
    - Create features for each user. This data will be used as input to the model
4. Data transformation, data splitting and model training
    - Transform feature engineered data. 
    - Split data into training, validation and test data.
    - Build a machine learning model to train using training data

## File Descriptions <a name="files"></a>
* Sparkify-Capstone-Project : Jputer notebook used for this project
* main_sparkify.py: python script extracted from the notebook

## Results<a name="results"></a>
We have analysed the sparkify dataset and come up with new features to predict churn. We then created a machine learning model and tuned it to improve its performance. We achieved an accuracy score of - and F1 score of - on the test dataset. 

# Conclusion
We are able to achieve an accuracy score of 87% and F1 score of 84% on the test dataset using the tuned Random Forest algorithm. The model peformance can be further improved by creating additional features and includiding some of the features that I have left out for this analysis. The model should also be tested using samples from the left out big dataset which hasn't been used for this analysis. Once we are satified with the result, a large scale of the model can be implemented on the cloud.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit to [Udacity](https://www.udacity.com/courses/all) for creating a happy learning experience.

[Click here to read the post on Medium](https://medium.com/@akessela/predict-customer-churn-for-sparkify-945d373b5f3)
