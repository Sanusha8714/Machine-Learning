🏡 Housing Price Prediction Using Machine Learning
📌 Overview
This project focuses on analyzing and predicting house prices using Machine Learning techniques.
The California Housing Dataset is used to explore different factors affecting house prices, such as median income, geographical location, housing age, population, and ocean proximity.The project uses Python for data cleaning, Exploratory Data Analysis (EDA), data visualization, preprocessing, and Machine Learning model development.A Linear Regression algorithm is implemented to predict median house values.
🎯 Objectives
.Understand and analyze the California Housing Dataset.
.Identify important factors influencing house prices.
.Perform data cleaning and handle missing values.
.Conduct Exploratory Data Analysis (EDA).
.Visualize relationships between housing features.
.Apply categorical encoding and feature scaling.
.Build a Machine Learning model using Linear Regression.
.Predict median house prices.
.Evaluate model performance using regression metrics.
📊 Dataset Information
- Dataset Name: California Housing Dataset
- File Name: housing.csv
- Number of Records: 20,640
- Number of Original Columns: 10
- Target Variable: median_house_value
Dataset Features
| Feature | Description |
|---|---|
| `longitude` | Geographic longitude of the area |
| `latitude` | Geographic latitude of the area |
| `housing_median_age` | Median age of houses in the area |
| `total_rooms` | Total number of rooms |
| `total_bedrooms` | Total number of bedrooms |
| `population` | Population of the area |
| `households` | Number of households |
| `median_income` | Median income of the area |
| `median_house_value` | Median house value (target) |
| `ocean_proximity` | Location category based on proximity to the ocean |
🛠️ Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
⚙️ Workflow
1)Import the required Python libraries.
2)Load the California Housing Dataset.
3)Understand the dataset structure and features.
4)Check and clean missing values and duplicate records.
5)Perform Exploratory Data Analysis (EDA).
6)Visualize relationships and patterns in the data.
7)Select input features and the target variable.
8)Encode categorical data and scale the features.
9)Split the dataset into training and testing sets.
10)Train the Linear Regression model.
11)Predict house prices using the test data.
12)Evaluate the model performance.
13)Actual vs Predicted Visualization
14)Key Findings
15)Conclusion
📊 Exploratory Data Analysis
Exploratory Data Analysis was performed to understand the dataset and identify patterns in housing prices.

- Statistical analysis of numerical columns.
- Distribution of median house values.
- Relationship between median income and house value.
- Average and median house prices by ocean proximity.
- Correlation analysis using a heatmap.
- Geographical distribution of house prices using latitude and longitude.
- ⚙️ Data Preprocessing
- The following preprocessing techniques were used:

Missing values in total_bedrooms were replaced with the median.
Categorical data was converted using One-Hot Encoding.
Numerical features were standardized using StandardScaler.
Dataset was divided into 80% training data and 20% testing data.
🤖 Machine Learning Algorithm
Linear Regression

Linear Regression is a supervised Machine Learning algorithm used to predict continuous numerical values.
In this project, Linear Regression is used to predict median house prices based on different housing features.

📈 Model Evaluation
The model was evaluated by comparing actual house prices with predicted house prices using the following metrics:
| Evaluation Metric | Result |
|---|---:|
| Mean Absolute Error (MAE) | 50,670.74 |
| Mean Squared Error (MSE) | 4,908,476,721.16 |
| Root Mean Squared Error (RMSE) | 70,060.52 |
| R² Score | 0.6254 (62.54%) |
nterpretation: The R² score indicates that the Linear Regression model explains approximately 62.54% of the variation in median house values in the test data. MAE and RMSE describe the size of prediction errors in the dataset's house-value units.

The notebook also uses an Actual vs Predicted graph to visually compare model predictions with actual house values.
💡 Key Findings
-The dataset contains 20,640 housing records and 10 original columns.
-Median income has a positive correlation (0.688) with median house value.
-House prices vary according to proximity to the ocean.
-Inland areas generally have lower median house values than coastal categories.
-The Island category has the highest median house value, but it contains only five records.
-Total rooms and total bedrooms have a strong positive correlation (0.927).
-Population and households have a strong positive correlation (0.907).
-Population and median house value have a very weak negative correlation (-0.025).
-House prices vary across different geographical locations in California.
⚠️ Limitations
.The dataset contains limited information about housing features.
.Linear Regression may not capture complex relationships between variables.
.House prices are influenced by factors that are not included in the dataset.
.The model's R² score of 62.54% indicates that some price variations remain unexplained.
.Outliers in the dataset may affect prediction performance.
🏁 Conclusion
This project analyzed and predicted house prices using the California Housing Dataset. Exploratory Data Analysis and visualization helped identify patterns and relationships between housing prices, median income, location, and ocean proximity.
A Linear Regression model was developed and evaluated using MAE, MSE, RMSE, and R² Score. The model achieved an R² score of 0.6254 (62.54%), showing that it explains approximately 62.54% of the variation in house values.
Overall, the project demonstrates the steps involved in data analysis, data preprocessing, visualization, and Machine Learning-based house price prediction.
