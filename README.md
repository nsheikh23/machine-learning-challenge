# machine-learning-challenge

#### -- Project status: [Active]

![exoplanets.jpg](Images/exoplanets.jpg)

## Project Objective
The purpose of this project was to build multiple machine learning models and compare them to identify the best model for classifying candidate exoplanets from the data provided by NASA.

### Methods Used
* Machine Learning
* Data Visualization

### Technologies
* Python
* Scikit-Learn
* Pandas, Jupyter
* Matplotlib

## Process
* Preprocessed the dataset prior to fitting the models.
* Scaled the numerical data.
* Separated the data for training and testing.
* Used GridSearchCV to hypertune the models and boost performance.
* Tuned and compared multiple classifiers.

## Analysis
* Logistic Regression model: Training Data Score = 0.84588 / Testing Data Score = 0.87850 (Tuned)
* SVM model: Training Data Score = 0.83730 / Testing Data Score = 0.86610 (Tuned)
* Random Forest model: Training Data Score = 1.0 / Testing Data Score = 0.89185
* KNN model(k=19): Training Data Score = 0.83578 / Testing Data Score = 0.83066
* Deep Learning model: Loss = 0.23516 / Accuracy = 0.90160

In conclusion, based on the results presented above, it is clear that all the models are great. Depending on the limitations, any of these models could be used. However, the Deep Learning models and Random Forest model have the highest accuracy and would be recommended if there are no restrictions.

## Submission

* Create a Jupyter Notebook for each model and host the notebooks on GitHub.

* Create a file for your best model and push to GitHub

* Include a README.md file that summarizes your assumptions and findings.

* Submit the link to your GitHub project to Bootcamp Spot.

* Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file

##### © 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
