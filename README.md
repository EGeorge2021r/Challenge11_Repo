# Challenge11_Repo
Analyzing the company's financial and user data in clever ways to make the company grow

# User Story
Role: Growth analyst at MercadoLibre e-commerce site in Latin America with over 200 miliion users

Goal: Tasked with analyzing the company's financial and user data in clever ways to make the company grow.

Reason: Want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock


# General information 
In a bid to drive revenue, a Jupyter notebook will be produced that contains data preparation, analysis, and visualizations for all the time series data that the company needs to understand. Text and comments will also be used to document findings, and answer the question prompts in the instructions.
The deliverables will include the following:
•	Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.
•	An evaluation of how the company’s stock price correlates to its Google Search traffic.
•	A Prophet forecast model that can predict hourly user search traffic.
•	Answers to questions in the instructions that you write in your Jupyter Notebook.
•	(Optional) A plot of a forecast for the company’s future revenue.

# Technology
Jupyter notebook that contains data preparation, analysis, and visualizations 
%matplotlib inline
Python

# Libraries used in the analysis
The following libraries were imported and used in the project.
import pandas as pd
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline

# Analysis and Visualisation
Identify unusual patterns in time series data by using Pandas and other tools.
Mine for patterns in seasonality by using the hvPlot visualization tool.
Build sales-forecast and user-interest predictive models for the firm by using Facebook Prophet.