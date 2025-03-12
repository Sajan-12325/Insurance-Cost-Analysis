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


