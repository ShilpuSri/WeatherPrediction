# WeatherPrediction
The objective of this project was to explore data, discover interesting data patterns and built a model that predicts the weather forecast temperature with maximum correlation and minimum mean squared error.

Dataset Description:
The weather forecast temperature dataset is taken from the UCI repository.We observed the data was collected every 15 minutes for selective days in 3
months March, April, May in the year 2012. This dataset contains a total of 24 attributes that include various Indoor(Indoor Temperature, Carbon dioxide,
Relative Humidity, Lightning of dining room and living room) , Outdoor(Rain, Sun dusk, Wind, Sunlight, Sun irradiance, Enthalpic motor, Outdoor temperature, Outdoor Relative Humidity) and Time-series(Date, Time, Day of the Week) attributes with 4137 instances.
https://archive.ics.uci.edu/ml/datasets/SML2010

Project Implementation:
Data Preparation, Exploration and Transformation
    
    1. Handled missing values
    2. Normalized the dataset
    3. Feature correlation using Heatmap
    4. Feature selection
    5. Dimensionality Reduction - PCA
    6. Clustering (k-means, agglomerative and gaussian) to observe data distribution
    7. Outlier Detection using Boxplot

Data Modelling using various Regression algorithms:
    
    1. Linear Regression
    2. Support Vector Regression
    3. Decision Tree Regression
    4. KNN Regression
    5. Bagging Regression
    6. Boosting Regression
    7. Sequential Deep Learning neural net
    8. LSTM

Model Evaluation:

    1. Pearson Correlation
    2. Spearman Correlation
    3. Mean-Squared-Error

Conclusion:

    Best results exhibited by the Bagging Regression model and LSTM Deep Learning model.
    
Attached PDF report with more details about the results.

