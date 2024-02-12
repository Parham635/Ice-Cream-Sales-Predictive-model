# Ice-Cream-Sales

This project focuses on predicting ice cream sales based on temperature using various statistical and machine learning techniques. The workflow includes data exploration, visualization, statistical analysis, linear regression, and neural network modeling.

##Overview
The project utilizes Python with libraries such as pandas, numpy, matplotlib, seaborn, statsmodels, and scikit-learn. It also incorporates TensorFlow for neural network modeling.

Dataset
The dataset consists of temperature and corresponding ice cream sales revenue. The data is retrieved from a remote source and converted into a pandas DataFrame.

Data Exploration
Descriptive statistics, histograms, covariance, and correlation matrices are employed to understand the distribution and relationships within the dataset.

Linear Regression
Ordinary Least Squares (OLS) regression is performed to model the relationship between temperature and revenue. The regression results, coefficients, and an ANOVA table are presented.

Residual Analysis
Residuals are analyzed through histograms and Q-Q plots to evaluate the goodness of fit of the linear regression model.

Predictive Analysis
Linear regression and neural network models are trained and evaluated for predictive accuracy. The linear regression model achieves a high accuracy of 98.373%, while the neural network model is trained using TensorFlow with early stopping to prevent overfitting.
