# MeXE402_Midterm_PunzalanJhenHazel_FranciscoVincentJeorge

# INTRODUCTION
#### Linear regression and logistic regression are two fundamental statistical methods used for predictive analysis in various fields, including business, healthcare, and social sciences.

Linear regression is a fundamental statistical technique used to model and analyze the relationship between variables. Specifically, it helps us understand how changes in one or more independent variables (also known as predictors or features) affect a dependent variable (the outcome we want to predict). The core idea behind linear regression is to find a linear equation that best fits the data. This means we look for a straight line that can represent the relationship between the independent variables and the dependent variable.

Logistic Regression, on the other hand, is used when the dependent variable is categorical, particularly binary outcomes (e.g., yes/no, success/failure). Instead of predicting a continuous outcome, logistic regression estimates the probability that a given input belongs to a certain category. For instance, it can be applied to predict whether a customer will purchase a product based on various characteristics. The logistic function ensures that the predicted probabilities are between 0 and 1, which is crucial for classification tasks.


# DATASET DESCRIPTION
### Linear Regression Dataset
#### The dataset offers valuable insights into how advertising spending impacts sales. It specifically looks at the effects of investments in TV, radio, and newspaper ads on sales results. By applying linear regression to the data, we can uncover the relationships between these advertising platforms and sales performance. This analysis allows us to determine which advertising channels are most effective for boosting sales, enabling us to allocate resources more efficiently. 

This analysis not only highlights which advertising mediums yield the highest return on investment but also provides a clearer understanding of consumer behavior in response to different types of advertising. By identifying effective channels, businesses can make informed decisions about where to allocate their marketing budgets, ensuring they invest in strategies that maximize sales growth. Additionally, this information can guide future advertising campaigns, helping to refine messaging and targeting for even better results. Overall, the insights gained from this dataset are crucial for developing an effective advertising strategy that aligns with sales objectives.


### Logistic Regression Dataset
This dataset applies logistic regression to investigate how different physicochemical properties affect the quality of red wine. By analyzing factors such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, and more, the model pinpoints which characteristics are key indicators of superior wine quality. This insight can assist winemakers in refining their production processes to craft wines that align with or surpass consumer expectations.

# PROJECT OBJECTIVES
- The main goal of the advertising dataset is to analyze the impact of various advertising channels on sales. By using linear regression you can identify how factors such as TV, radio, and newspaper advertising budgets influence the sales figures.
- We'll aim to predict the continuous sales variable based on sdvertising expenditures in TV, RADIO, and NEWSPAPER.
- We'll classify wines as either "bad quality" or "good quality" based on transformed quality scores (2 for bad, 4 for good).   

### LINEAR REGRESSION
- Part 1 Data Preparation:
Load the dataset and examine its structure.


![Screenshot 2024-11-01 201313](https://github.com/user-attachments/assets/d7dadcdb-9c45-426d-8e6c-bbb6fa3c9f74)

- Part 2 Creating the Training Set and the Test Set :
  Visualize the relationships between advertising budgets and sales.
Check for correlations among the variables.

![Screenshot 2024-11-01 201849](https://github.com/user-attachments/assets/fdcf4d7c-f66d-490d-b4a5-309df196044e)

- Part 3  Modeling:

Split the data into training and testing sets.
Implement linear regression using a library like scikit-learn.

![Screenshot 2024-11-01 204106](https://github.com/user-attachments/assets/6001b8d0-0d88-4173-a18e-c548e6d927ae)

- Part 4 Evaluation:

Assess the model's performance using metrics such as R-squared, Mean Squared Error (MSE), and visualizations like residual plots.

![Screenshot 2024-11-01 204219](https://github.com/user-attachments/assets/328cb8c1-4343-4455-9b47-e7e01e5d7700)
![Screenshot 2024-11-01 204233](https://github.com/user-attachments/assets/91db24a0-d02c-4e9f-8f73-dd6dde5d94df)
![Screenshot 2024-11-01 204242](https://github.com/user-attachments/assets/e7e5efcd-adad-4a4b-a73a-79863d67baab)








### LOGISTIC REGRESSION
![image](https://github.com/user-attachments/assets/f74bc19a-f740-465f-aa39-4eda499ecc73)
- Part 1- Data Preprocessing, signals that this part of the code is focused on preparing the dataset for analysis.
- Imports the Pandas library and Numpy library
- Loads the red wine quality dataset from a csv file named into Pandas Dataframe 
![image](https://github.com/user-attachments/assets/78f720eb-34dc-41c0-b63e-707acb297589)
- This command provide a concise summary of the Dataframe, which includes details about each columns, its data type, and the number of non-null entries.
![image](https://github.com/user-attachments/assets/f3a79af7-68f9-4533-8327-49f37b6c947e)
- This code displays the first 10 rows of the wine dataset, showing key characteristics of each wine sample, potentially for exploratory data analysis or model training.
![image](https://github.com/user-attachments/assets/ef602874-1c4b-4dda-b7b6-7e9e12ceda0b)
- Fixed Acidity: Wines with values above 10 are considered "1" others "0."
- Residual Sugar: Values above 3 are "1" others "0."
- Chlorides: Wines with values above 0.08 are "1" others "0."
- Total Sulfur Dioxide: Values above 50 are categorized as "1."
- Alcohol: Wines with an alcohol content above 10% are labeled "1."
![image](https://github.com/user-attachments/assets/ddb0025c-719d-4f4a-92df-7d43fa8b7e9f)

![image](https://github.com/user-attachments/assets/50c11915-d196-45f7-a112-bf3d6a1bdfb5)

![image](https://github.com/user-attachments/assets/306dfdaa-0cca-47f7-8cc9-36f407614b94)
- Converts the quality column to binary values: if quality is above 5, it becomes 1; otherwise, it becomes 0.
![image](https://github.com/user-attachments/assets/74845789-d132-4d34-a548-b5bf3af7ffc0)
-
![image](https://github.com/user-attachments/assets/b6be29a0-de46-4b52-a0fe-25cd7b651882)

![image](https://github.com/user-attachments/assets/9b76002c-5be4-4797-8951-f236dbcea098)

![image](https://github.com/user-attachments/assets/0a8f6f6b-f465-4bf9-9e46-e8d33c97004b)

![image](https://github.com/user-attachments/assets/3ec84a17-2378-4967-8673-0c0636b22cff)

![image](https://github.com/user-attachments/assets/906b1a8f-fd16-401d-b405-4787daaf16a5)

![image](https://github.com/user-attachments/assets/7c5a13e1-9085-45c0-8f68-7b7ff7d9ec74)

![image](https://github.com/user-attachments/assets/46b66c00-64a3-4a57-9fe9-1c1e284f6749)

![image](https://github.com/user-attachments/assets/22694efa-878b-4b57-ac40-6265c00302b5)
- This code snippet is taking the test data (X_test), scaling it, and then using a trained machine learning model to make predictions. The predicted values are stored in y_pred.
![image](https://github.com/user-attachments/assets/fac1c2d3-4824-4396-a262-c40337386f32)

![image](https://github.com/user-attachments/assets/8b17001c-375d-4159-9ffc-3f6df5dc553d)

![image](https://github.com/user-attachments/assets/7ed63b93-79eb-400a-85a7-05478459f781)
-  This code snippet takes a set of input features, scales them, and uses a trained machine learning model to predict the class of the input data. In this case, the predicted class is '0'.
  
![image](https://github.com/user-attachments/assets/e6c46acd-6d47-4eb7-8661-650f80aa42cb)
- This imports the confusion_matrix function from sklearn.metrics, which is used to evaluate classification models by showing the counts of correct and incorrect predictions for each class.
- confusion_matrix(y_test, y_pred) compares the actual values (y_test) with the predicted values (y_pred) from the model.
- This confusion matrix gives insight into the model’s accuracy and error types, helping identify areas where the model might need improvement.
![image](https://github.com/user-attachments/assets/8ef9d1a2-9cce-4db7-94ac-a323271b665d)
- This imports the accuracy_score function from sklearn.metrics, which is used to calculate the accuracy of a classification model.
- accuracy_score(y_test, y_pred) computes the accuracy by comparing the actual values (y_test) with the predicted values (y_pred).
- This metric provides a general idea of the model's performance, with a higher value indicating better accuracy. However, in cases of imbalanced datasets, accuracy alone may not be enough to evaluate the model's performance comprehensively.
