# BloodGroup
Exploratory Data Analysis (EDA) and Machine Learning concept on  healthcare dataset using Python.
Key Steps

1. Data Preprocessing

Encoding:

Blood Type and Gender were converted to numerical format using one-hot encoding.

Test Results were encoded into numeric categories for the target variable.

Train-Test Split:

Data was split into 80% training and 20% testing sets to evaluate model performance.

2. Exploratory Data Analysis (EDA)

A heatmap was generated to visualize the distribution of test results across blood groups and genders.

Observations revealed no dominant trends, warranting further statistical and model-based analysis.

3. Statistical Test

A Chi-Square Test of Independence was performed to examine relationships between blood group, gender, and test results.

Result: No statistically significant relationship (p = 0.88).

4. Model Comparison

Random Forest:

Accuracy: ~66%

Outperformed XGBoost with better recall and precision.

