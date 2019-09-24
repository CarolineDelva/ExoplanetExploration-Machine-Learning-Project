Create a README that reports a comparison of each model's performance as well as a summary about your findings and any assumptions you can make based on your model
(is your model good enough to predict new exoplanets?
 Why or why not? What would make your model be better at predicting new exoplanets?).

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