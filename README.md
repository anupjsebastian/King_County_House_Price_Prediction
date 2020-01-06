#Predicting Home Prices

##Project Goals/Overview

The purpose of this project was to use newly acquired skills in predictive regression modeling to accuratley predict home prices on given 2014 & 2015 data in King County Washington (Seattle Area). We additionally took it one step futher and wanted to see if the models on the 2014/15 data would still be able to work for data in 2019. This will be outlined below as the 'Original Model' (for 2014/15 data) and the 'Redfin Model' (for 2019 data).

##README Summary

In this README we will discuss our process for data cleaning, some insights that we noticed in the dataset, model selection, and how/why we applied this to 2019 data.

The final presentaion can be found in the file XXXXXX.pdf

##Team Members

Carson Lloyd, Sam Videlock, Aneeta Khoso, Dylan Lisk, Anup Sebatian

##Process
###Data Cleaning

1. The original dataset is found in the csv 'kc_house_data.csv'
2. The 'Cleanup, EDA and Transformations.ipynb' file shows our complete data processing stage. Notes are compiled in the file.

###Original Model
This is the model using the given data for King County in 2014 & 2015.

1. The 'All_col_GAMS_DL.ipynb' is where our final model is for the orignal data. Comments can be found in the file.
2. This uses data in the 'Cleaned_Housing_Data_vDL.csv' which was derived from the data cleaning python file.

###Redfin Model
This model used webscraped Redfin data to pull 2019 housing data for analysis.

1. The webscraped data was captured from code in the 'CARSONS NOTEBOOK XXXXX.ipynb'. This notebook is commented, and the test data is saved in 'sold_homes_model_validation_data.csv'.
2. We then retrained the Original Model with modified features so the Redfin data would run, this can be found in the 'low_col_GAMS_DL.ipynb'.
3. We then tested this data on 340 sold homes in 2019 (look to the presentation for details).
4. Finally, we predicted home prices on 350 homes that are currently listed to see if we could find potential undervalued homes for flip opportunities -- 'low_col_test.ipynb'.



