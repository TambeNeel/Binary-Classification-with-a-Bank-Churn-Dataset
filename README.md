# Binary Classification with a Bank Churn Dataset
## Overview
A comprehensive exploratory data analysis (EDA) to gain insights into the dataset's characteristics. Leveraging this understanding, adopted a unique approach by utilizing the Random Forest Regressor for making predictions.

#### Files:
**train.csv:** The training dataset featuring a variety of customer-related features and the binary target variable 'Exited,' indicating customer churn.

**test.csv:** The test dataset for which participants are required to predict the probability of customer churn.

**sample_submission.csv:** A sample submission file in the correct format to guide participants on structuring their predictions.

## Introduction:
The Bank Customer Churn Prediction dataset is used to develop predictive models capable of identifying and forecasting customer churn within a bank's customer base. This methodology outlines a comprehensive approach that incorporates exploratory data analysis (EDA) and leverages a Random Forest Regressor for making predictions.

## Exploratory Data Analysis (EDA):
The first crucial step in understanding the dataset involves exploratory data analysis (EDA). Initially, the training dataset (`train.csv`) is loaded to examine its structure, data types, and basic statistics. Key EDA steps include handling missing values, visualizing the distribution of features, and exploring relationships between variables. Visualization tools such as Matplotlib and Seaborn are employed to gain insights into feature distributions and potential correlations.

## Data Preprocessing:
Following EDA, data preprocessing is essential to prepare the dataset for model training. This involves handling categorical variables through techniques like one-hot encoding, scaling numerical features for consistent units, and addressing any outliers or anomalies identified during EDA.

### Model Selection- Random Forest Regressor:
For this binary classification task, the Random Forest Regressor is chosen as the primary model. Despite being traditionally used for continuous predictions, a strategy is formulated to convert the continuous predictions into binary labels suitable for the binary classification nature.

## Model Training:
The model is trained using the Random Forest Regressor on the preprocessed training data. The features and target variable are appropriately separated, and the model is initialized and fitted to the training data.

## Prediction and Conversion:
After model training, predictions are generated on the training set using the trained Random Forest Regressor. Subsequently, a conversion step is implemented to translate continuous predictions into binary labels. This involves setting a threshold (e.g., 0.5) to categorize predictions as either class 0 or class 1.

## Evaluation:
Evaluation metrics are crucial for assessing the model's performance. Metrics such as accuracy, precision, recall, and F1 score provide insights into the model's ability to correctly classify instances. The evaluation is conducted on the training set using the ground truth labels and the converted binary predictions.

## Submission:
The final step involves making predictions on the test dataset. Following the preprocessing steps applied to the training data, predictions are made using the trained Random Forest Regressor. 

## Conclusion:
In conclusion, the Bank Customer Churn Prediction methodology seamlessly integrated exploratory data analysis, preprocessing, and a Random Forest Regressor. Leveraging insightful EDA, the dataset underwent meticulous preprocessing, ensuring its readiness for training. The strategic use of a Random Forest Regressor, despite its typical application in regression tasks, provided a unique perspective for this binary classification. Model training, evaluation, and submission phases followed, emphasizing adaptability and precision. The methodology aimed to achieve optimal predictions by combining data understanding, effective modeling, and continuous refinement in a succinct and competitive manner.
