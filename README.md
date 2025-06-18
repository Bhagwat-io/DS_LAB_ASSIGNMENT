Experiment 1: Data Visualization
Aim:

To explore datasets using various commands.

To create Boxplots and Scatter plots.

Tools Used: R programming

Topics Covered:

Data exploration on “pollutant”, “Hair Eye Color”, and “Germination” datasets.

Boxplot for Sepal.Length (Iris dataset)

Scatter plot for murder data using dslabs package

Key Visuals:

Boxplot of Iris dataset

US murder data scatter plot with region-wise color coding

Experiment 2: Probability and Distributions
Aim:

Calculate probabilities using Binomial and Normal distributions

Verify Normal approximation of Binomial distribution

Tools Used: R programming

Dataset: Travelled Abroad data

Key Results:

Probability of people traveling abroad using binomial distribution for n = 10

Approximate probability using normal distribution for n = 100

Visuals:

Probability distribution plots

Conclusion:
The normal approximation was close to the binomial distribution results. Most likely, 6 out of 10 people have traveled abroad based on given data.

Experiment 3: Hypothesis Testing
Aim:

Perform single and two-tailed hypothesis tests

Tools Used: R programming

Scenarios:

Claim about ball bearing life (one-tailed test)

Caloric value on chips label (two-tailed test)

Conclusion:

Manufacturer's claim can be rejected at 0.05 level but not at 0.01.

Caloric value claim cannot be rejected at either significance level.

Experiment 4: Regression Analysis
Aim:

Construct simple and multiple linear regression models

Tools Used: R programming

Dataset: Toy Sales

Key Results:

SLR: R² = 0.619, Residual Error = 1997

MLR: R² = 0.8588, Residual Error = 1275

Prediction Scenarios:

Scenario A (Price=9.1, Adexp=52K, Promexp=61K) chosen for best sales

Conclusion:
MLR gives better accuracy. Promotion expenditure significantly influences unit sales.

Experiment 5: Nearest Neighbor Classifier
Aim:
Apply:

Nearest Neighbor (NN)

KNN (k=5)

Radius-based NN (R=1.45)

Tools Used: R programming

Dataset: 18-point 2D dataset

Results:
In all three cases, test point P(3,2) belongs to class 3.

Conclusion:
All three classification algorithms assign test point to class 3. Class 3 has the densest presence around the test point.

Experiment 6: Classifier Performance Evaluation
Aim:
Evaluate classifier using:

Accuracy

Sensitivity

Specificity

Precision

Tools Used: R programming

Dataset: Wisconsin Breast Cancer dataset

Results:

Accuracy: 0.95

Sensitivity: 0.91

Specificity: 0.98

Precision: 0.978

Conclusion:
KNN classifier performs with high accuracy and strong sensitivity/specificity balance, making it effective for medical datasets.
