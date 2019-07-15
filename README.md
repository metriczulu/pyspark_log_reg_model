# Predicting low birth weight with logistic regression in Spark

## Overview

This project was part of an assignment for my DATA650 Big Data course.  The dataset was provided for the assignment and, while small, is still sufficient to demonstrate proficiency with various parts of the model building process using the PySpark library.  A full description of the dataset and it's variables is available at the beginning of the analysis notebook in this repository.  The verbatim problem statement for this assignment is reproduced below.

This repository contains three files:  this README.md, the dataset used, the notebook containing the EDA and model building pipeline, and the required writeup for the assignment.

The notebook is decently large.  If you have issues viewing it through github, a link to it on nbviewer is available here [here](https://nbviewer.jupyter.org/github/metriczulu/pyspark_log_reg_model/blob/master/lowbirthweight_notebook.ipynb)

## Problem Statement

### Build Logistic Regression model for low birth weight data
Use the lowbtwt.csv data that you downloaded from Assignment 2 folder to build the logistic regression model in a new notebook.

**Required Notebook Content:**  
•	Markdown cell with the dataset description at the top of the notebook  
•	Table of contents  
•	Code to load the necessary packages  
•	Credentials  
•	Write a parsing function for the new data by carefully considering what the input variables should be and what the training target variable should be   
•	Data exploration and visualization prior to running logistic regression.  Include the histogram for the age variable, the frequency counts for the target variable, and the plots/frequency tables to check which variable could be a predictor for the target variable    
•	Split the data into a training and test set   
•	Use the training set to build the logistic regression model  
•	Tabulate the predicted and actual outcome  
•	Evaluate the model on the test set.  Tabulate the predicted and actual outcome for the test set  
•	The precision, recall, and F-measure for the training and test set  
•	Roc curve plot  
•	Markdown cells with comments on what the code does and headings  

Once the code works as expected, download the notebook.

**Required Writeup Content:**  
•	Define the purpose of the study and the target variable. Which variables are used as predictors?  
•	Interpret the data exploration and visualization results.  What did you learn about the low birth weight data from data exploration, including possible relationships between predictors and the target variable?  
•	Discuss the method results, including the classification accuracy for training set and test set and model evaluation metrics (precision, recall, ROC curve area).  
•	Is the logistic regression method suitable for this study?  Why or why not?  
•	How would you improve the accuracy of your model?  
•	Discuss at least 2 alternative machine learning methods that could be suitable for this problem and explain why?  
 
**Assignment Grading Rubric:**  
The assignment deliverable must be an original work and must comply with the APA format and with the graduate standards.  
Logistic regression on low birth weight data. (15 points for notebook submission and discussion; 25 points for answering questions)  
No credit will be given for this part if the submission is missing the notebook file  
•	The submitted notebook file shows the working code and the code output  
•	The notebook must include all required content    
•	The notebook includes markdown cells with comments, dataset description, and table of contents   
•	Clear definition of the study purpose and an identification of the target variable   
•	Data exploration and data visualization discussion  
•	Method results interpretation, study limitations, and discussion of 2 alternative methods, including the rationale  
•	Model evaluation metrics and an approach to improve the accuracy  
•	Demonstrate the concepts application through depth of analysis and findings discussion  
		


  