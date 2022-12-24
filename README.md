# Anomaly-Detection-Tennesse-Eastman-Process
Building a fault detection system using Machine Learning Models. Application of ML/AI in the process plant and design. Real time fault diagnosis. Formulation of defence mechanism using Adversarial Machine Learning-Random Forest/SVM. 

Tennesse Eastman Process Simulation Data for Anomaly Detection in Process Design using Machine Learning.
#### Basic Idea of TEP:

Tennesee Eastman Process is an industrial process widely used as a benchmark in test fault diagnosis and process control.

# Case Studies:
* Plant Wide Control
* Statistical Process Monitoring
* Sensor fault detection
* Identification of data-driven models.


# Aim and Objective of the Project:

Our Aim: To predict correct Fault between 1 to 20 as possible with high precision.

#### Incorrect Fault detection will impact the cost of maintenance and waste worker's time in resolving incorrect fault.

Some Basic information to know:
Anomaly means something that deviates from what is standard, normal, or expected.

## Outline of the Project:
* Data Preprocessing
* EDA
* Feature Selection and Feature Engineering
* Model Building
* Hyperparameter Optimization
* Accuracy Check


1. Data Preprocessing and Exploratory Data Analysis:  Data preprocessing, a component of data preparation, describes any type of processing performed on raw data to prepare it for another data processing procedure. It has traditionally been an important preliminary step for any Predictive Modelling. Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns,to spot anomalies,to test hypotheses and to check assumptions with the help of summary statistics and graphical representations.

2. Checking Null values or missing values : Missing Data can occur when no information is provided for one or more items or for a whole unit. Missing Data is a very big problem in real-life scenarios. Missing Data can also refer to as NA(Not Available) values in pandas. In DataFrame sometimes many datasets simply arrive with missing data, either because it exists and was not collected or it never existed. For Example, Suppose different users being surveyed may choose not to share their income, some users may choose not to share the address in this way many datasets went missing. In order to check missing values in Pandas DataFrame, we use a function isnull() and notnull(). Both functions help in checking whether a value is NaN or not. These functions can also be used in Pandas Series in order to find null values in a series. Using both the commands, it has been observed that there are no null values in the dataset. There are also various graphical methods to see the Nan values like heatmap, bar graph, missingno. Missingno library offers a very nice way to visualize the distribution of NaN values. Missingno is a Python library and compatible with Pandas. Data is free of null values as per both methods.

3. Normal Distribution: In Machine learning, data satisfying Normal Distribution is beneficial for model building, it makes the math easier, algorithms works efficiently without unwanted complexity. Note : Normality is an assumption for the ML models. It is not mandatory that data should always follow normality. ML models work very well in the case of non-normally distributed data also. Models like decision tree, XgBoost, don’t assume any normality and work on raw data as well. Now there are two methods to see whether your data is normally distributed or not, they are: Statistical Tests and Graphical Method. Statistical methods include the Shapiro-Wilk Test. Graphical methods include Histograms, Box Plots, kdeplot and Quantile-Quantile Plot.

4. Shapiro Wilk Test : The Shapiro-Wilk test is a way to tell if a random sample comes from a normal distribution. The test gives you a W value; small values indicate your sample is not normally distributed (you can reject the null hypothesis that your population is normally distributed if your values are under a certain threshold). The null-hypothesis of this test is that the population is normally distributed. Thus, if the p value is less than the chosen alpha level, then the null hypothesis is rejected and there is evidence that the data tested are not normally distributed. On the other hand, if the p value is greater than the chosen alpha level, then the null hypothesis (that the data came from a normally distributed population) can not be rejected (e.g., for an alpha level of .05, a data set with a p value of less than .05 rejects the null hypothesis that 

5. Graphical Method: QQ (Quantile-Quantile)[10] Plot- Quantiles=particular part of a dataset i.e. a quantile determines how many values in a distribution are above or below a certain limit. QQ Plot - When Quantiles of two variables are plotted against each other. The quantile-quantile (q-q) plot is a graphical technique for determining if two data sets come from populations with a common distribution. A q-q plot is a plot of the quantiles of the first data set against the quantiles of the second data set. By a quantile, we mean the fraction (or percent) of points below the given value. That is, the 0.3 (or 30%) quantile is the point at which 30% percent of the data fall below and 70% fall above that value. 

6. Feature Selection: The biggest challenge of ML is to create models that have robust(strong) predictive power by using as few features as possible. Feature selection is the process of choosing a subset of the most important features while trying to retain as much information as possible. There are various techniques of Feature selection. But most common is finding correlation between features using Hypothesis testing.

7. Machine learning model is a file that has been trained to recognize certain types of patterns. You train a model over a set of data, providing it an algorithm that it can use to reason over and learn from those data. Building a model in machine learning is creating a mathematical representation by generalizing and learning from training data. Then, the built machine learning model is applied to new data to make predictions and obtain results. Model building can be classified into seven parts including collecting the data, Preparing the data, extraction and selection, splitting the data into train and test datasets, choosing a Machine learning model, Training the model, evaluating the model, parameter tuning and finally predicting the results. 


8. Results and conclusions : Machine learning models in anomaly detection: XGBoost turns out to be the most suitable algorithm for fault detection with an accuracy and a precision score of more than 99 %. Followed by Random Forest, Logistic Regression and Naive Bayes. Successful in creating a system that can predict an anomaly or fault in the process. Various insights and data analysis techniques are also being conducted to extract resourceful information that will benefit the future of this project. This completes the very first objective of this Project, that is of coming up with a fault detection system. Now, as per the core objective, we need to apply adversarial machine learning to our fault detection system. Attacking the model with external measures that will eventually drop the accuracy of the system. On the basis of that, we will come up with a defense mechanism that will protect the Model from such attacks and thus make it more effective from an Industrial Point of view.

* XGBoost 99.78 
* Random Forest 98.68 
* Logistic Regression 96.89 
* Naive Bayes 95.67  







