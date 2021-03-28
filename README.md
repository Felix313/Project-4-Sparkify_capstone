# Project 4: Sparkify_capstone

## Table of Contents
[Installation](https://github.com/spreuhs/data_science_nd_capstone_sparkify/blob/main/README.md#installation)

[Project Motivation](https://github.com/spreuhs/data_science_nd_capstone_sparkify/blob/main/README.md#project-motivation)

[File Descriptions](https://github.com/spreuhs/data_science_nd_capstone_sparkify/blob/main/README.md#file-descriptions)

[Results](https://github.com/spreuhs/data_science_nd_capstone_sparkify/blob/main/README.md#results)

[Acknowledgements](https://github.com/spreuhs/data_science_nd_capstone_sparkify/blob/main/README.md#acknowledgements)

## Installation

All necessary libraries to run this code are part of the Anaconda distribution of Python.
The code should run without issues using Python versions 3.* and the following libraries:

    Pyspark
    Pandas
    Numpy
    Matplotlib
    Seaborn

## Project Motivation

Are you interested in the key drives that make a customer love your product or service? 
If you run any kind of company the answer to that question is of course YES.
Let's say you run some kind of subscription based service, consisting of a free and a paid premium version.
To be successful with your endavor you need to understand what makes your customers want to use the premium version and how much they are willing to pay for said service.
This project is intended to give an idea of how one can understand their customer's behaviour better, using the customer data collected from such services or products.
For the sake of time and scope, the focus will be directed towards predicting customer churn. And since it's more tangible to use an easy example, the intent of this project is to predict churn for the fictional company Sparkify. 
The data will be processed using Apache Spark, an open-source unified analytics engine for large-scale data processing.

### Questions answered in the following:

The following tasks will be performed to try and answer what makes Sparkify customers churn:
1. Load and Clean Dataset
    -What information is provided in the dataset?
2. Define churn and label data accordingly
    -How can we define that a customer churned?
3. Check how many users did churn within the dataset
4. What information is provided in the data?
	- how do we define churn?
	- how many users did churn in the past?
	- are activities of churned users different from still active users?
	- can we accurately predict churn?


## File Descriptions

The whole process is gathered in the jupyter notebook found in this directory. Detailed description regarding the code can be found in markdown cells and comments contained in the notebook.

## Results

Most of the results can be found in the notebook. Additional information and formatted results can be found in my Medium post [here](https://medium.com/@felix.kinzius/airbnb-or-long-term-lease-in-berlin-5d78d828a69f).

A brief summary of the results is that we can predict churn somehow well using a Gradient Boost Tree Classifier. As churn is not very likely, so the dataset is a bit imbalanced. Nonetheless, using thought-out Feature Engineering in combination with the GBT Model leads to somewhat reliable results.

## Acknowledgements

Thanks to Udacity for providing the data as part of their Data Science Nano Degree.
