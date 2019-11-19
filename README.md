# Exoplanet Exploration

I completed this project during my time at the [Columbia Engineering Data Analytics Bootcamp](https://bootcamp.cvn.columbia.edu/data/nyc/landing/?s=Google-Brand&pkw=%2Bdata%20%2Banalytics%20%2Bcolumbia&pcrid=392444639754&pmt=b&utm_source=google&utm_medium=cpc&utm_campaign=%5BS%5D_GRD_Data_Brand_ALL_NYC_BMM_New&utm_term=%2Bdata%20%2Banalytics%20%2Bcolumbia&utm_content=392444639754&s=google&k=%2Bdata%20%2Banalytics%20%2Bcolumbia&gclid=Cj0KCQiA2b7uBRDsARIsAEE9XpFH-2wU0-_7jtxCV_PCkGBR0prlyKtvpF2-nAWU1tO4oYci5h1QStsaAsg5EALw_wcB&gclsrc=aw.ds) located in New York, NY.


#### -- Project Status: [Completed]


![exoplanets.jpg](Images/exoplanets.jpg)

## Project Description

The purpose of this project is to process data from NASA Kepler space to create machine learning models capable of classifying candidate exoplanets.

The models includes the following features:

#### Preprocessed data

* Preprocessed dataset prior to fitting the model.
* Feature selection and removal of unnecessary features.
* Scaled numerical data with `MinMaxScaler`.
* Data seperated into training and testing data.

#### Tuned Model Parameters

* Tuned models parameters with `GridSearch`.

#### Selected models
* Support Vector Machine 
* Logistic Regression
* Deep Learning 




## Methods Used
* Machine Learning
* Data Analysis 
* Data Processing
* Statistical Analysis

## Technologies
* Python (Pandas, Scikit-Learn, Tensorflow, Jupyter Notebook)

## Output 

####  * Split data into training and testing data 

![split data](Images/splitdata.PNG)

#### * Numerical data scale using `MinMaxScaler`

![MinMaxScaler](Images/Minmaxscaler.PNG)

#### * Tuned models parameters with `GridSearch`.


![grid search](Images/gridsearch.PNG)


#### * Logistic Regression Model Training and Testing Scores

![Logistic Regression](Images/logisticregressionscore.PNG)

#### * Support Vector Machine Model Training and Testing Scores

![SVM](Images/SVM.PNG)

#### * Deep Learning Model Accuracy and Loss

![deep learning](Images/deeplearning.PNG)


## Get Started


1. Clone this repository (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Find the [exoplanet_data.csv](https://github.com/CarolineDelva/ExoplanetExploration-Machine-Learning-Project/blob/master/starter_code/exoplanet_data.csv) csv.
3. Find the Python scripts in the [starter_code](https://github.com/CarolineDelva/ExoplanetExploration-Machine-Learning-Project/tree/master/starter_code) folder.

4. Run the script for each model in their own [Jupyter Notebook](https://jupyter.org/).

## Conclusion

There were three machine learning model that were used to predict the exoplanets. 

The first model was logistic regression, which generated a training data score of 0.8226206370398627 and a
testing data score of 0.8140732265446224. Once the model was fined tuned with a gridsearch, this was the new score of 
{'C': 10, 'penalty': 'l1'} 0.8525653251954988.

The second model was the support vector machine, which generated a training data score of 0.8271981689872211 and a 
testing data score of 0.8146453089244852. Once the model was fined with gridsearch, this was the new score of 
{'C': 10, 'gamma': 0.0001} 0.8390234598512302

The third model was a deep learning model which had a Loss: 0.27107809173706193 and Accuracy: 0.8867276906967163. 

The best model to predict exoplanets is the deep learning model because it provided the best accuracy score. This is model is also 
great to use because it does not have a perfect score of 100. A score of 100 would mean that the model would be overfitted and that would 
not be great for when you introduce new data. To improve this model, I would add more data, add more layers, or let the model run for more epochs.
Trying multiple models is the best way which model is best at predicting the exoplanets.  