## Exploratory Data Analysis Using Python

Exploratory data analysis is a complement to inferential statistics, which tends to be fairly rigid with rules and formulas. At an advanced level, EDA involves looking at and describing the data set from different angles and then summarizing it.


#### Data Analysis:

Data Analysis is the statistics and probability to figure out trends in the data set. It is used to show historical data by using some analytics tools. It helps in drilling down the information, to transform metrics, facts, and figures into initiatives for improvement.


#####  Exploratory Data Analysis(EDA) 

The major topics to be covered are: 

* Handle Missing value

* Removing duplicates

* Outlier Treatment

* Normalizing and Scaling( Numerical Variables)

* Encoding Categorical variables( Dummy Variables)

* Bivariate Analysis


## ## Importing Libraries
~~~python
import pandas as pd
import numpy as np 
import  matplolib.pyplot as plt
import seaborn as sns 
%matplotlib inline 
~~~

## ## Loading the data set 

use pandas to ready .json file, csv file or excel file where the dataset is stored 

~~~python
#reading a csv file use 
data = pd.read_csv("path_to_your_file/yourdataset.csv")

#reading excel file
data = pd.read_xlxs("path_to_your_file/yourdataset.csv")
~~~

## Basic Data Exploration

In this step, we will perform the below operations to check what the data set comprises of. We will check the below things:

* head of the dataset
* the shape of the dataset
* info of the dataset
* summary of the dataset

    1). The head function will tell you the top records in the data set. By default, python shows you only the top 5 records.

    2). The shape attribute tells us a number of observations and variables we have in the data set. It is used to check the dimension of data. 

~~~python
data.shape
~~~

    3). nfo() is used to check the Information about the data and the datatypes of each respective attribute.

~~~python
data.info()
~~~
    
