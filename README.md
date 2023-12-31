# CS210Project
This repository contains data visualization, data cleaning and the machine learning part of the data.
# Cigarette Consumption Analysis - Socio-economic Factors
This project aims to analyze the relationship between cigarette consumption and socio-economic factors such as housing type, education status, and employment. The project involves data cleaning, visualization, and machine learning techniques to gain insights and build predictive models.

# Project Structure
The project is organized as follows:

cs210Project_Data: This folder contains Excel files (.xls) containing the data for housing type, education status, employment status, number of people in the household, size of the household, prices of the cigarette per year and month, etc.
cs210_Project_Data_Analysis_and_DataVisualization.ipynb: Jupyter Notebook containing the data analysis and visualization code.
CS-210_Project_ML.ipynb: Jupyter Notebook containing the data cleaning and the machine learning code.
Data Cleaning and Preprocessing
The data cleaning process involves the following steps:

1-Loading the data from data.xls.
2-Handling missing values by either removing rows or imputing missing values.
  *Remove Unnecessary Rows and Columns*
3-Rename Columnns.
4-Data Segmentation:segment the data into multiple dataframes using a specific pattern and adjust the code to create a dictionary of dataframes.

Data Visualization
The visualization process involves using the seaborn and matplotlib libraries to create visualizations that provide insights into the data. The visualizations include:

Describing and time series plotting for every data.
The code for data visualization can be found in the cs210_Project_Data_Analysis_and_DataVisualization.ipynb notebook.

Machine Learning
The machine learning phase involves building predictive models using the cleaned and combined data. The steps include:

Splitting the data into training and testing sets.
Choosing a machine learning algorithm (e.g., linear regression).
Training the model on the training set.
Making predictions on the testing set.
Evaluating the model performance using metrics which is mean squared error (MSE).
The code for machine learning can be found in the CS-210_Project_ML.ipynb.ipynb notebook.

Requirements
The following libraries are required to run the code:

pandas
numpy
seaborn
matplotlib
sklearn

Conclusion
This project provides insights into the relationship between cigarette consumption and socio-economic conditions. By combining the housing type, education status, and employment datasets, we were able to perform data analysis, visualization, and machine learning tasks. The results contribute to a better understanding of the impact of socio-economic conditions on cigarette consumption.

Feel free to reach out if you have any questions or need further assistance!
Us and our Responsibilities:
Deniz Durmuşoğlu			 28972    for finding the data 
Berkant Umut Özbölük	29577   for finding the data and contribution for the training data
Gülnihal Seda Erdemli 29057  for visualization
Serra Yakupoğlu       31106  for training and testing the data
Yağmur Dolunay        29323  for training and testing the data
