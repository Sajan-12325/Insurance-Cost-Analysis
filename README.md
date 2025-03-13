# Insurance-Cost-Analysis

##### This project uses machine learning techniques to predict medical insurance charges based on various factors like age, BMI, number of children, smoking status, gender, and region. The project demonstrates data preprocessing, visualization, and model training using linear and ridge regression, with pipelines for more streamlined processing.

##### Libraries Used

pandas, matplotlib, numpy, seaborn, sklearn (Pipeline, StandardScaler, PolynomialFeatures, LinearRegression, Ridge, metrics, and model_selection)


#### Data Preprocessing
Loaded data from online source
Renamed columns
Handled null values (mode for 'smoker', mean for 'age')
Converted data types ('age' and 'smoker' to integers)
#### Data Visualization
Regression plot: Charges vs. BMI
Histogram: BMI vs. Charges
Boxplot: Smoker vs. Charges


#### Model Training
Simple Linear Regression (BMI and Smoking status)
Multiple Regression (all features)
Evaluated R-squared score and Mean Squared Error (MSE)
Developed Pipelines
Standardized data
Applied Polynomial Features
Trained Linear Regression model
#### Model Evaluation
R-squared score
Mean Squared Error (MSE)
Ridge Regression
Applied with alpha=0.001
Evaluated on original and polynomial-transformed data
Predictions
Made using trained models
Example predictions for new data points shown


