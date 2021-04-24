# Predict_customer_responce_SB  

# Installation  
1- python 3.7.  
2- numpy.  
3- pandas.  
4- matplotlib.  
5- seaborn.  
6- sci-kit learn.  
7- jupyter notbook.  

# Project Motivation  
The project aim is to predict if a customer will complete an offer or not.  
P.S: complete means either they use the offer like a discount or buy 1 get 1, or by simply viewing it like an information offer.  

# File Descriptions  
StarBucks_capstone.ipynb- this notebook contains my analysis, trining paramter, results, and conclusion.  
StarBucks_webapp\data - folder contains data files in .csv format.  
StarBucks_webapp\models- folder contains traind ML model.  
StarBucks_webapp\app\run.py- python script to run the web app.  


# How To Interact With Your Project  
unzip StarBucks_webapp then through cmd navigate to run.py, type: (python run.py) in cmd then go to localhost:3001 in your browser.  
Note: make sure to enter data as: age income offer total_tran gender year      each value is seperated by whitespace.  


# Results Summery  
Data was tricky to get in an easy to represent state and even tricker to visulaize and extract data from it. Models performance was bearly better than pure gusseing but it improved with undersampling teacniqe, perhaps with better feature engineering or by using deep learning better results could be achived.

# Acknowledgment  
i would like to thank [Udacity](https://udacity.com), [StarBucks](https://www.starbucks.com), amd [Kaggle](https://www.kaggle.com/ihormuliar/starbucks-customer-data) for providing these simulated data.

