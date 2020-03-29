# Data Scientist Nanodegree
# Introduction to data science
## Project: Seattle Airbnb listings analysis

### Installations

This project requires **Python 3.x** and the following Python libraries installed:

- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
- plotly

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)


### Project Motivation

As per Udacity Data Scientist Nanodegree project Term 2 project to write a Data science blogpost using CRISP-DM. I was intriguted to analyze and find business related questions about airbnb listings for Seattle city. This interest stem from being a frequent user of airbnb and a curious traveler that is  interested in knowning the trends in prices and what can affect.


for more information refer to the medium blogpost for this project: 

### summary of the project

In this notebook I wanted to analyze the Seattle airbnb listings. I used descriptive statistics and data modelling techniques such as Kmean clustering and xgboost to answer the following questions:


1) What are some most expensive property type in Seattle City?

I first had a look at the distribution of property type across the city then grouped the data by property to get the average price for each type of property.

2) Effect on booking prices at different times of the year?

After looking at the average monthly price of listings across the year, I compared the listings prices with the availability of listings and got inverse relationship between these two, Cheapest time to visit Seattle is during the start of the year to March.  

3) Most expansive and least expansive Neighbourhood in Seattle?
- Most Expensive neighourhood is Fair-mount park followed by Industrial District, Portage Bay ranging between $150 to $350.

- Least Expensive ones are Roxhill, Olympic Hills ranging from $50 to $100 showing a huge difference compared to expensive ones. 
 

4) What are the attributes associated with the price of a listing?

    - Availability
    - Neighbourhood
    - Property Type
    - Room Type 
    - Cancellation Policy
    - No. of Reviews


### File Descriptions

- Seattle_Airbnb_Data_Analysis.ipnyb:a notebook containing the analysis for the data.

### Run

In a terminal or command window, navigate to the top-level project directory `Write_BlogPost/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Seattle_Airbnb_Data_Analysis.ipynb
```  
or
```bash
jupyter Seattle_Airbnb_Data_Analysis.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

The data used in this project was acquired from kaggle for Seattle city using the following [link](https://www.kaggle.com/airbnb/seattle). 

create a data directory containing the following required downloaded files from the above repo:
 - calendar.csv: data of availability, dates and price of the listings.
 - listings.csv: detailed listings data for Seattle city.
 - reviews.csv : Unique Identifier for each host and detailed comments.

### Licensing, Authors, Acknowledgements 

- data was acquired from kaggle [repo](https://www.kaggle.com/airbnb/seattle)
- This project is part of Data scientist Nanodegree from udacity 

This work is licensed under a [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/). Please refer to [Udacity Terms of Service](https://www.udacity.com/legal) for further information.
