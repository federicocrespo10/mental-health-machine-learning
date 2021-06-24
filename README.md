# mental-health-machine-learning

Project made  out by Federico Crespo, from a dataset extracted from Kaggle, to determine, based on certain characteristics, if a person needs psychiatric treatment or not. 

At the end of the data exploration, Machine Learning Classification models were applied and compared to see which one performed better.

It is divided into:

Packages 

Import of the necessary packages for the correct execution of the code.

EDA and Data Transformation

The process consists of the different transformations.

First, an EDA was elaborated to determine which columns were available, the characteristics of the data, which transformations had to be performed and which columns or data had to be discarded. Then we proceeded to transform the data:
1. The missing data in the work_interfere and self_employed columns were replaced. As there was not much missing data, Python methods were used.
2. Removed the data from the columns containing outliers in the data set ('Age').
3. Normalized the Gender data (there were many genders distributed, only 3 were left, male, female and non-binary).
4.	The string data was encoded to be able to adjust the Machine Learning models.
5.	The age was standardized, because otherwise it was very varied.

Correlation

A correlation matrix was elaborated having the treatment as the main axis. As a result of the correlation graph, it was possible to determine that the main components that determine the treatment or not for a person with a psychiatric illness are:

1- Family history.
2- Work.
3- Presence of mental health care options.
4- Benefits at work.
5- Gender.

Conclusions

For the final part of the project, the dataset is evaluated with different Machine Learning models, being the XGB model the one that gives a better accuracy in the evaluation of the prediction against the test data set.
The results obtained were:

   index                  Model  Accuracy
0      5                    XGB  0.751366
1      4                    SVC  0.737705
2      0          Decision Tree  0.724044
3      1    Logistic Regression  0.704918
4      2          Random Forest  0.696721
5      3  KNeighbors Classifier  0.691257
 



Prerequisites 📋
It is necessary to have python 3.7 onwards.
Author ✒️
- Federico Crespo 
Closing ⌨️
- Any correction or suggestion about the code is welcome as I thought this project to practice my skills.
- Thank you very much for getting this far

