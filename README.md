# Bat-Echolocation-Classification
Project examining the accuracy of bat ecolocation software and development of ML classification models

## Summary
Bat echolocation research produces a large amount of data that takes a significant amount of time to process for downstream analysis.  Doing so manually can take many hours to days and weeks of work.  However, the development machine learning classifiers can reduce the amount of time required for processing data down to a matter of minutes.  However, machine learning classifiers are generally not as accurate as manual processing.  In this project it was determined that Kaleidoscope Pro App Version 2.8 software was overall 68% accurate for the species examined, with certain species having overall higher accuracy than others.  The goal of this project was to produce a machine learning classifier model that would improve on this accuracy.  Random Forest, KNN, XGBoost, and multinomial Logistic Regression models were developed for all of the species, the three most common species, and individual species.  

Random Forest was determined to produce the model with the highest accuracy as well as F1 score.  However, this model did not improve on the overall accuracy and F1 score of Kaleidoscope.  Accuracy and F1 scores were also examined for the three most common individual species for the three species Random Forest model.  TADBRA from the three species Random Forest model was the only species that outperformed Kaleidoscope.  While the best performing model produced in this project did not outperform Kaleidoscope, the Random Forest model produced here can be utilized in conjunction with Kaleidoscope inorder to better identify this particular species.  

## Table of Contents
  1. [Raw Data](https://github.com/haberkornm/Bat-Echolocation-Classification/tree/main/Raw_data)
      - Mexico Library - Echolocation call library created in Mexico [Reference](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.12556)
          -Mexico library was examined in EDA and determined to not be compatable with Truthed Library, therefore it was not used in modeling.
      - Truthed Library - Echolocation call library created by Matt Haberkorn in Arizona
      - Truthed Library Kal - Cleaned-up version of Truthed Library for the purpos of testing accuracy of Kaleidoscope Pro
  2. [Data Cleaning](https://github.com/haberkornm/Bat-Echolocation-Classification/blob/main/Bat_Echolocation_datacleaning.ipynb)
  3. [EDA](https://github.com/haberkornm/Bat-Echolocation-Classification/blob/main/Bat_echolocation_EDA.ipynb)
  4. [Clean Data](https://github.com/haberkornm/Bat-Echolocation-Classification/tree/main/Clean_data)
      - Clean csv files ready for modeling.  Produced in data cleaning and EDA.  Contains files for all or three species modeling as well as scaled and unscaled data.
  6. [Modeling](https://github.com/haberkornm/Bat-Echolocation-Classification/blob/main/Bat_Echolocation_Modeling.ipynb)
  7. [Final Report](https://github.com/haberkornm/Bat-Echolocation-Classification/blob/main/Bat%20Echolocation%20Classification%20Final%20Report.pdf)
  8. [Slide Presentation](https://github.com/haberkornm/Bat-Echolocation-Classification/blob/main/Echolocation%20Presentation%20Slides.pdf)
