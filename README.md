# Capstone-Project
To access the Project, select the folder name Part 4. This folder consists of 4 python files named Argentina, Europe, Global and Hillesdon as well as their corresponding data resource files saved as either a .csv or a zip file. Each notebook contains a report on each of the 4 datasets.

The Capstone project was aimed at trying to predict the Value Output of crops across various land mass sizes. These sizes were the entire globe, Europe, Argentina and a region in the UK called Hillesdon. Including predicting the value output of the crops was also seeing what impacted the predictions the most. For example does being Organic have a positive or a negative impact on predicting the Value Output?

A variety of Regression models were used to see how the predictions would work. This included Random Forests and Decision trees as well as regularization of standard Linear regression. To find which predictors had the biggest impact on the models, absolute coefficients were used. Decision trees and Random forests were done via gridsearching to provide the best possible scores and parameters for the predictions.

To see which coefficients were negative and which were positively affecting the predictions, they were displayed as a red (negative) and blue (positive) histogram. The most impactful predictors were the locations for each of the datasets. One dataset contained organic and inorganic methods. The organic methods proved to be a negative coefficient while inorganic was positive. This can be due to the fact organic methods are more expensive to maintain and implement into farming as well as the crops produced are not always 'perfect' for commercial use.

All models performed above the baseline with scores  which showed relatively good accuracy of my models. Further work on the project is to tweak the models and create new ones using different predictors and targets.
