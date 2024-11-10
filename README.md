1. Description of the Data Set
- Features: The Wisconsin breast cancer dataset contains 30 features that describe properties of cell nuclei, such as:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Number of concave points
- Symmetry
- Fractal dimension
- Classes: The target is binary, indicating whether the tumor is:
- Malignant (1)
- Benign (0)
2. Statistical analysis
2.1 Descriptive Statistics
- Mean and Standard Deviation: Descriptive statistics, such as mean and standard deviation, are calculated for each characteristic. This helps to understand the distribution of the data.
- Distribution: Analysis of the distribution of characteristics can reveal whether the data is symmetrical or has asymmetry, which can affect modeling.
2.2 Correlation Matrix
- Correlation between characteristics: The correlation matrix is an important tool for identifying relationships between characteristics.
- Values close to 1: Indicate a strong positive correlation.
- Values close to -1: Indicate a strong negative correlation.
- Values close to 0: Indicate little or no correlation.
- Interpretation: For example, if tumor area and perimeter are highly correlated, this suggests that an increase in one characteristic may be associated with an increase in the other.
3. Predictive modeling
3.1 Logistic regression
- Model: Logistic Regression is a statistical model used to predict the probability of a binary event (in this case, malignant or benign).
- Model evaluation:
- Confusion Matrix: Shows the number of true positives, true negatives, false positives and false negatives. This helps to understand the effectiveness of the model.
- Classification Report: Includes metrics such as precision, recall and F1-score:
- Precision: Proportion of true positives in relation to the total number of positives predicted.
- Recall: Proportion of true positives in relation to total actual positives.
- F1-score: Harmonic mean of precision and recall, useful for assessing the balance between the two metrics.
3.2 Evaluation results
- Precision: A high precision indicates that the model is good at predicting malignant tumors correctly.
- Recall: A high recall indicates that the model is effective at identifying the majority of malignant tumors.
- F1-score: A high F1-score suggests that the model has a good balance between precision and recall.
