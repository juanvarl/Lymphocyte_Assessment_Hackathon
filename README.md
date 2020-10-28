# Lymphocyte_Assessment_Hackathon
The objective is to develop a regression model for calculating the number of certain type of cells (called lymphocytes) in a given histopathology image patch.
Extra information about the dataset can be found in: https://lysto.grand-challenge.org/Data/

Question 1, is about explorary analysis of the dataset. 
Question 2, is about obtaining relevant summary statistics over the different channels of the images. Moreover we transform the images into HED format and apply Incremental PCA to facilitate analisis among all the images. We stay with 200 components that explain 83% of the variance. From question 2.ii) we apply diverse methods such as: OLS, Multilayer Perceptron, Ridge Regression and Support Vector Regression.
Question 3 is the final part of our study. We used different Convolutional Neural Networks (CNN) to fit the regression model.
The CNN obtained the best results among all the methods.
