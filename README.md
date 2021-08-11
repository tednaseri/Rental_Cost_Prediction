# Home Rental Cost Prediction
<ul align="justify">
<li>It is a supervised machine learning project based on Kaggle Brazil Houses Dataset which is made of 10692 records and 14 features. Each row represents one home.</li>
<li>The goal is predicting rental cost of homes. Since the target feature is a numerical variable, it is a regression machine learning project where I minimized RMSE as the business metric.</li>
<li>This application includes data cleaning, data preparation, explanatory data analysis, and machine learning modeling.</li>
<li>For the machine learning purposes, linear regression, random forest, XGBoost, and LightGBM models along with hyperparameter tuning are implemented.</li>
<li>By optimizing the XGBoost model as the best model, we could improve the business metric more than 9%.</li>
</ul>
  
# Files in this Repository:
There are two folders in this repository: "Data" and "Code":

<ol align="justify">Data Folder:
<li>houses_to_rent.csv: This file is the original dataset of the project.</li>
<li>rental_houses_Tohid.csv: I have prepared the dataset in two versions. This is the version No.1; To rebuild this version, one can run the Jupyter Notebook file of: "Preparation_Rental_Cost".</li>
<li>rental_houses_Tohid_Final.csv: This is the final version of the dataset which is ready for applying machine learning algorithms.</li>
</ol>

<ol align="justify"> Code Floder:
<li>Utils_Car_Insurance: This file includes common functions for actions like data manipulation or data visualization. These functions will be called through other files.</li>
<li>Preparation_Car_Insurance: This file includes all the preparation steps for this dataset.</li>
<li>EDA_Car_Insurance: This file includes applied steps for the Data Explanatory Analysis.</li>
<li>Modeling_Car_Insurance: This file includes machine learning content of the project.</li>
</ol>

# How to run the project?
To run this project after downloading the dataset, the provided files in Code folder should be run with the above order.

# More Details:
More details is provided in my personal website at http://tednaseri.pythonanywhere.com/rental_cost
