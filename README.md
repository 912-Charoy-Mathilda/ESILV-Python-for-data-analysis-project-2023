# ESILV_FinalProject2022_Python_Allanic_Charoy_DIA1
*Created by Lila ALLANIC and Mathilda CHAROY, DIA students at ESILV (DIA1)*

## Estimation of obesity levels based on eating habits and physical condition

We were given a dataset for this project, on which we had to perform data visualization and machine learning, as well as implement the best selected machine learning model into an API. We also had to find a problematic concerning our dataset.
The dataset we were given was "ObesityDataSet_raw_and_data_sinthetic.csv", about the different habits of thousands of individuals and their weight index (ranging from "Insufficient Weight" to "Obesity Type II").
Mathilda took care of the data cleaning and visualizations, while Lila did the data cleaning for the machine learning part, the machine learning and the API part.

### 1. Data  visualization

Concerning the visualization, we were able to assert that this or that variable is determining or not: we were able to study the features of the population (weight, height, age, gender, family history, according to the status).
Then we could study the consumption habits of the individuals (eating between meals, smoking, drinking alcohol, transport used). 
All this could be visualized by numerous plots (pie plots, histograms,...).

### 2. Machine Learning

For this part, we tested several classification models: Logistic Regression, Gradient Boosting Classifier, K-Nearest Neighbours, Support Vector Machine, Random Forest and XGBoost. After performing accuracy calculations and plotting the results, we concluded that the best model was XGBoost, which we then implemented in our API.

###### Quick note : while coding on google colab, the best model was indeed XGBoost, but when transferring the notebook to jupyter notebook and running our code on it, the best model became Gradient Boosting Classifier, even though both models almost have the same accuracy score. This is why on the plot we can clearly see Gradient Boosting Classifier as the most accurate but we chose the XGBoost, we didn't predict this outcome and it came at the last minute, so we didn't have the time to modify the whole API part. Sorry !

### 3 - L'API

We used Dash, implementing the following concept: following a questionnaire, the user can estimate his weight index or his risk to suffer from obesity in the future.

### 4 - Conclusion

During this project, we were able to use various libraries that we had discovered during the Practical Works of the semester. As we studied our dataset, we could also come to the conclusion that obesity is very much linked to eating habits and physical conditions. 
