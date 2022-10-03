# Machine-Learning-based-Detection-of-Irrigated-Fields-in-Alabama
### Files
1. Data_download.ipynb: 
This files is used to download the code from earth engine and stores the images on the google drive
2. save_as_df.ipynb: 
This file is used used to convert the downloaded images from google drive into pandas data frame and store the as complete, cultivated and non-cultivated csv files based on the cultivated region for easier use.
3. run_2013_rf.ipynb: 
This file is used to train random forest model on the year 2013 on the cultivated region and tested on 2015 and saves a prediction results of 2015 as a csv
### Post Processing
Once the csv file of the prediction are saved, we use ArcGIS Pro software to convert the csv into shapefiles by merging and dissolving.
