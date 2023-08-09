# mamography_screening


*1. Build Statistical Classification model to detect severity?*

The goal of the this project is to build a statistical classification model to detect the severity of mammographic mass lesions (benign or malignant). I have used Two models, logistic regression, and XGBoost, trained and evaluated.

The logistic regression model performed better, achieving 82% accuracy on the test set. It exhibited perfect precision, recall, and F1-scores for both classes, indicating its excellent ability to distinguish between benign and malignant lesions.

Given the dataset's size and complexity, the simplicity and interpretability of the logistic regression model make it a favorable choice for this task. Its high accuracy and ease of understanding make it suitable for for this severity

In conclusion, the logistic regression model demonstrated superior performance in detecting mammographic mass lesion severity, making it a promising choice for medical diagnosis and decision-making.

# 2. What considerations have been used for model selection?

data set was less so logistic regression perform well , and logistic regression is easy to understand

# 3. What features would you want to create for your prediction model based on data provided?

According to the domain knoledge we can manupulate the data and make new features

# 4. How have you performed hyper-parameter tuning and model optimization? What are the reasons for your decision choices for these steps

Importent parameter has been tuned to optimized the model, so the performence of the matrix will improve , already mentioned in notebook

# 5. What is your model evaluation criteria? What are the assumptions and limitations of your approach?

model evaluation parameter criteria should be precision and recall in this study the recall is most important evaluation parameter becouse the we can slip the negative prediction if there is cancer .

# 6. Determine whether the data is normally distributed visually and statistically.? 
we have to understand he each feature distribution to understand the varibility of the data set.

# 7. How are you detecting and treating outliers in the dataset for better convergence?

with the help of box plot to the quartile range

# 8. What techniques have been used for treating missing values to prepare features for model building? 
for contibnuation replaing with mean(normally distributed), for skewed one with meadian and catorical with mode . # 9. What is the distribution of target with respect to categorical columns? we have to undertand the the distribution and relation of each column with the target varibale with correlation matrix
