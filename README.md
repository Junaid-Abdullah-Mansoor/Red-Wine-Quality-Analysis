# Red Wine Quality Analysis

This project focuses on analyzing the quality of red wine based on its physicochemical characteristics. The red wine industry has experienced significant growth due to increased social drinking. Quality certificates are crucial for marketing wine products, but the traditional evaluation process conducted by human experts is time-consuming and expensive. Moreover, the subjective nature of wine tasting can lead to varying opinions among wine tasters, making quality assessment challenging. 

To address these challenges, this project aims to connect the chemical characteristics of red wine with human quality perception. By leveraging physicochemical tests, such as acidity, pH level, sugar content, and other chemical qualities, we can establish more standardized and regulated processes for red wine certification and quality assessment.

## Dataset
The dataset used for this analysis consists of 11 columns, including the following physicochemical characteristics of red wine:

1. **Fixed acidity**
2. **Volatile acidity**
3. **Citric acid**
4. **Residual sugar**
5. **Chlorides**
6. **Free sulfur dioxide**
7. **Total sulfur dioxide**
8. **Density**
9. **pH**
10. **Sulphates**
11. **Alcohol**

The output variable, based on sensory data, is the **quality** of the wine, which is scored on a scale of 0 to 10.

## Analysis Algorithms
In this project, four machine learning algorithms were applied to predict the quality of red wine based on its physicochemical characteristics:

1. **Decision Tree**: This algorithm constructs a tree-like model to make decisions based on a set of if-then-else conditions.
2. **Random Forest**: Random forest is an ensemble learning method that combines multiple decision trees to improve accuracy and reduce overfitting.
3. **Linear Regression**: Linear regression models the relationship between the independent variables (physicochemical characteristics) and the dependent variable (quality) using a linear equation.
4. **Logistic Regression**: Logistic regression is used for binary classification tasks, where the goal is to predict the probability of a certain outcome.

## Analysis Findings
After applying the machine learning algorithms, the following accuracies were obtained:

- Decision Tree: 73%
- Random Forest: 81%
- Linear Regression: 71%
- Logistic Regression: 40%

These accuracies indicate the performance of each algorithm in predicting the quality of red wine based on the provided physicochemical characteristics.

## Project Analysis Steps
This project includes the following analysis steps:

1. **Data Preprocessing**: The dataset is cleaned, and any missing or inconsistent values are handled.
2. **Exploratory Data Analysis**: The dataset is explored to gain insights into the distributions and relationships between variables.
3. **ANOVA Testing**: Analysis of Variance (ANOVA) testing is performed to determine if the survey or experiment results are statistically significant.
4. **Algorithm Implementation**: Decision tree, random forest, linear regression, and logistic regression algorithms are applied to predict wine quality.
5. **Model Evaluation**: The accuracy of each algorithm is evaluated to assess its performance.
6. **Conclusion**: Key findings and insights regarding the best indicators of red wine quality are summarized, and predictions for future performance are made using the best-performing algorithm.

## Conclusion
Through this analysis, we aimed to identify the physicochemical characteristics that serve as the best indicators of red wine quality. By applying machine learning algorithms, we achieved promising results, with the random forest algorithm performing the best with an accuracy of 81%. These findings can be valuable for quality certification, assurance, and assessment processes in the red wine industry.

Please refer to the project code and analysis results for detailed implementation and insights.

Feel free to reach out if you have any questions or need additional information.

