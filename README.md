# Introduction
# sensorless_drives
Sensor less drives dataset  , classifying it's currents to 11 different classes.
This is a motor drive data which has intact and defective components. 
The data has 49 attributes and 58509 rows, 48 columns are having input data and the last column is the output data. The output column has 11 different classes with different conditions.
All the columns does not have any name in the original data, the input columns which are currents renamed as current_1,current_2……current_48 and the last column renamed as output in the data cleaning part of the project.
There are no missing values in the data and the all the columns are in floating type except the output column which is an integer which is ranging from 1 to 11 for 11 different classes.
There are some outliers in the some of the features of the data, they are replaced with the minimum value for the value which is less than the minimum and maximum value for the value which is greater than the maximum.
(https://github.com/vasu-sketch/sensorless_drives/assets/97977791/98989c33-b201-427f-9a0d-d8ac4b7d3b7d)

# Part -1 
Data Cleaning and Preparation.

# part -2 

After the data cleaning, the data need to be processed before applying the machine learning algorithms.
The data need to be transformed in order to improve the interpretability of the model, to make the computation time and cost less and to meet the statistical assumptions like normality.
There are 2 ways to transform the data 1. Normalization 2. Standardization
After doing the transformation, the data comes in the range of 0 to 1 and follows normal or normal standard distribution.
Using 4 models in the part 2 of project 1. SGD Classifier 2. KNN Classification 3. Random Forest 4. Decision Trees.
SGD Classifier and KNN models requires the transformation, Random forest and decision trees does not require the data transformation.

# part -3 
In the part-3 of the project, the classification analysis is done with the 1. svm Linear 2. SVM Non Linear 3. Multi Layered Perceptron
The first variable selection is done with the lasso regression, by selecting the best varibles for the model.\
The second variable selection is done with the Bi-directional elimation.
The clustering is done using K-means clustering, best clusters with Silhouette score and parallel coordinates.
Visualization part of the project is done with the 2-component and 3-component PCA.
Ensemble model is created with combining all the models from part-2, part-3.

