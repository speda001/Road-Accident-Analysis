# Road-Accident-Analysis


## Abstract

A Road accident is the most unexpected thing to happen to a person. The rapid growth of the population has resulted in the continuous growth of motor vehicles which in turn increases traffic accidents. In order to prevent road accidents and reduce their consequences, they need to be systematically analyzed. Analysis of accidents is very important as it can find the relationship between the different types of attributes that commit to an accident. Analyzing the accident dataset can provide information about the contribution of these attributes which can be utilized to reduce the accident rate.

This project explores a rich dataset that includes vehicles and the persons driving the vehicles' attributes related to collisions and is based on Python's data analysis capabilities. With an emphasis on the vehicle's manufactured years, driver's license status, and significant contributing factors, the analysis reveals important patterns. This also involves the prediction of major contributing factors in vehicle collisions using machine learning.

## Data Source

Motor Vehicle Collisions-Vehicles: The motor vehicle collisions-Vehicles data contains information on each vehicle involved in an accident from all police-reported motor vehicle collisions in New York city. The data is taken from 2012 to 2020. Each row represents a motor vehicle involved in an accident. https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Vehicles/bm4k-52h4

Motor Vehicle Collisions-Persons: The motor vehicle collisions-Persons data contains information on persons involved in an accident from all police-reported motor vehicle collisions in New York city. Each row represents a person involved in an accident. https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Person/f55k-p6yu

## Analysis of Data 

Find out how the vehicle age influences the accident rate
Find out how the age of the person driving the vehicle influences the accident rate
Analyze the major reason for accidents in the past few years
Create a visualization based on the results
Predict the major contributing factor to accidents

## Results

Our RandomForest model achieved an overall accuracy of 55%, suggesting that it performs slightly better than random guessing, there is scope for improvement though.

Precision is the ratio of correctly predicted positive observations to the total predicted positives. The recall is the ratio of correctly predicted positive observations to all observations in the actual class, and the F-1 score is the weighted average of precision and recall. Our model performs well for some classes such as class 0, 4, 14, 17, and 36 with high precision and recall. However, for many classes, the precision and recall are lower, indicating potential challenges in correctly predicting those classes. Support represents the number of actual occurrences of the class in the dataset. Some classes have low support, which means there are fewer instances of those classes in the dataset. This can impact the reliability of metrics for these classes. The similarity between macro and weighted averages suggests a relatively balanced class distribution, with no single class dominating the dataset.
