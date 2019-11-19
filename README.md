# Exoplanet Exploration

I completed this project during my time at the [Columbia Engineering Data Analytics Bootcamp](https://bootcamp.cvn.columbia.edu/data/nyc/landing/?s=Google-Brand&pkw=%2Bdata%20%2Banalytics%20%2Bcolumbia&pcrid=392444639754&pmt=b&utm_source=google&utm_medium=cpc&utm_campaign=%5BS%5D_GRD_Data_Brand_ALL_NYC_BMM_New&utm_term=%2Bdata%20%2Banalytics%20%2Bcolumbia&utm_content=392444639754&s=google&k=%2Bdata%20%2Banalytics%20%2Bcolumbia&gclid=Cj0KCQiA2b7uBRDsARIsAEE9XpFH-2wU0-_7jtxCV_PCkGBR0prlyKtvpF2-nAWU1tO4oYci5h1QStsaAsg5EALw_wcB&gclsrc=aw.ds) located in New York, NY.


#### -- Project Status: [Completed]


![exoplanets.jpg](Images/exoplanets.jpg)

## Project Description

The purpose of this project is to process data from NASA Kepler space to create machine learning models capable of classifying candidate exoplanets.

The final report includes the following features:

## Instructions

### Preprocess the Data

* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.

### Reporting

* Create a README that reports a comparison of each model's performance as well as a summary about your findings and any assumptions you can make based on your model (is your model good enough to predict new exoplanets? Why or why not? What would make your model be better at predicting new exoplanets?).

- - -

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

- - -

## Hints and Considerations

* Start by cleaning the data, removing unnecessary columns, and scaling the data.

* Not all variables are significant be sure to remove any insignificant variables.

* Make sure your `sklearn` package is up to date.

* Try a simple model first, and then tune the model using `GridSearch`.

- - -

## Get Started

* Create a Jupyter Notebook for each model and host the notebooks on GitHub.

* Create a file for your best model and push to GitHub

* Include a README.md file that summarizes your assumptions and findings.

* Submit the link to your GitHub project to Bootcamp Spot.


1. Create a new repository for this project called `machine-learning-challenge`. **Do not add this homework to an existing repository**.

2. Clone the new repository to your computer.

3. Give each model you choose their own Jupyter notebook, **do not use more than one model per notebook.**

4. Save your best model to a file. This will be the model used to test your accuracy and used for grading.

5. Commit your Jupyter notebooks and model file and push them to GitHub.


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