# OSHA_Classification-Model-Predicting-if-a-worker-is-hospitalized-by-type-of-severe-injuries
Classification Model: Predicting if a worker is hospitalized by type of severe injuries

We predicted the possibility of a worker that suffered a Labor injury being referred to a hospital or not. The used Data is from Occupational Safety and Health Administration (OSHA), collected from 1/1/2015 through 7/31/2021 https://www.osha.gov/severeinjury 

Form 2015 OSHA requires employers to report all severe work-related injuries, defined as an amputation, in-patient hospitalization, or loss of an eye. The dataset describes the incident and the establishment's name and address. Injuries are coded using the Occupational Injury and Illness Classification System.

We processed the dataset twice to reduce the size and select meaningful information. The final dataset of the model has only three numeric columns, and the target variable is the "Hospitalized" column.

Conclusions:

To get better results, we can apply a non-linear classifier.

Logistic Regression and SVM models have higher accuracy of 92%. Both models have higher False Positives - 1207 than the KNN model - 1023, but we considered it is better to incorrectly remit a worker to the Hospital instead of don't do it. This project is not related to reducing healthcare expenses; rather, it aims to predict the number of Labor injuries that may improve workers' health.
