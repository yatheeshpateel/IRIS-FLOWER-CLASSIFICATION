# IRIS FLOWER CLASSIFICATION
                                                                              
This project aims to build a machine learning model that can classify the three species of Iris flowers based on their measurements. The three species are Setosa, Versicolor, and Virginica.

![51518iris img1](https://user-images.githubusercontent.com/120399980/234676915-7184753a-10de-4922-8300-80f2433fb2a4.png)

# Dataset
The dataset used in this project is the Iris flower dataset, which contains measurements of the sepal length, sepal width, petal length, and petal width for 150 Iris flowers, with 50 flowers from each species. The dataset is available in the UCI Machine Learning Repository.



# Logistic Regression                                      
Logistic Regression is a supervised machine learning model used mainly for categorical data, and it is a classification algorithm. It is one of the widely used algorithms for classification using machine learning. Seeing the name logistic regression, you may think it will be a regression algorithm. But the fact is that it is a classification algorithm, and it is a generalization of the linear regression model.                                   
                              
Logistic Regression is used to find the relationship between dependent and independent variables. This is done by using a logistic regression equation. This is a very easy to implement, understand, and also easy method to train the model.


# Model
We will use a supervised learning algorithm to train the model. We will split the dataset into training and testing sets to evaluate the performance of the model. We will use the popular scikit-learn library to build the model. 

We will use the following steps to build the model:                
Load the dataset                            
Preprocess the dataset                                  
Split the dataset into training and testing sets                            
Train the model on the training set using Logistic Regression                                 
Evaluate the performance of the model on the testing set                            
Logistic Regression is a binary classification algorithm that can be extended to multi-class classification by using the One-vs-Rest (OvR) method. In the OvR method, we train a binary classifier for each class and predict the class with the highest probability.                         

# Requirements
Python       
cikit-learn     
pandas         
numpy           


# Conclusion on Classification                                   
Flower classification is a very important, simple, and basic project for any machine learning student. Every machine learning student should be thorough with the iris flowers dataset. This classification can be done by many classification algorithms in machine learning but in this i used logistic regression. Overall in this  we have seen

Mainly we focused on Logistic Regression              
We took Iris Flowers dataset and performed a logistic regression algorithm                
Finally, it classified flowers into their species.               
And we got an accuracy of 97.37%, which shows that the model we built is very accurate                     
