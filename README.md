# Bat-Echolocation-Classification
Project examining the accuracy of bat ecolocation software and development of ML classification models

## Summary
Bat echolocation research produces a large amount of data that takes a significant amount of time to process for downstream analysis.  Doing so manually can take many hours to days and weeks of work.  However, the development machine learning classifiers can reduce the amount of time required for processing data down to a matter of minutes.  However, machine learning classifiers are generally not as accurate as manual processing.  In this project it was determined that Kaleidoscope Pro App Version 2.8 software was overall 68% accurate for the species examined, with certain species having overall higher accuracy than others.  The goal of this project was to produce a machine learning classifier model that would improve on this accuracy.  Random Forest, KNN, XGBoost, and multinomial Logistic Regression models were developed for all of the species, as well as the three most common species, in the dataset.  Random Forest was determined to produce the model with the highest accuracy as well as F1 score.  However, this model did not improve on the overall accuracy and F1 score of Kaleidoscope.  Accuracy and F1 scores were also examined for the three most common individual species for the three species Random Forest model.  Random Forest models were also produced for each individual species of the three most common species.  TADBRA from the three species Random Forest model was the only species that outperformed Kaleidoscope.  Individual species Random Forest models consistently underperformed all other models.  TADBRA is the most common species in the southwestern United States and plays an extremely significant role ecologically.  While the best performing model produced in this project did not outperform Kaleidoscope, the Random Forest model produced here can be utilized in conjunction with Kaleidoscope inorder to better identify this particular species.  The practice of utilizing multiple classifiers is a typical practice in echolocation analysis and is often used to aid accurate species identification.  

## Table of Contents
  1. Raw Data
  2. Data Cleaning
  3. EDA
  4. Clean Data
  5. Modeling
