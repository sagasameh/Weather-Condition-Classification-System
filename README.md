Weather Prediction System for Australia

Overview
This project focuses on building a machine learning model to predict whether it will rain tomorrow based on historical weather data from Australia. The goal is to analyze weather patterns and classify the target variable (RainTomorrow) as Yes or No.

Dataset
The dataset contains real weather observations collected from different locations in Australia. It includes features such as temperature, humidity, wind speed, rainfall, and atmospheric pressure.

Project Steps

Data Preprocessing

- Removed missing values in the target column
- Handled missing data in features using imputation
- Converted categorical variables into numerical format
- Scaled numerical features for better model performance

Model Building
A Random Forest classifier was used to train the model due to its ability to handle large datasets and capture complex relationships between features.

Model Evaluation
The model was evaluated using:

- Accuracy score
- Classification report
- Confusion matrix

Results
The model achieved good performance in predicting rainfall, showing that weather conditions like humidity and pressure play an important role in prediction.

Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

Conclusion
This project helped in understanding how machine learning can be applied to real-world weather data for classification tasks. It also improved my skills in data preprocessing, model training, and evaluation.

Note
This project was done for learning purposes.

