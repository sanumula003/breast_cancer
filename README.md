# breast_cancer
Cancer Diagnosis Prediction
Overview
This project aims to predict cancer diagnosis (Malignant or Benign) based on various features extracted from diagnostic images. The dataset used in this project contains information about the radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension of cell nuclei present in the images.

Dataset
The dataset used in this project is stored in Cancer_Data.csv. It contains 569 instances and 32 features including an ID column and the diagnosis column (target variable).

Preprocessing
Checked for missing values and removed columns with missing data.
Encoded the diagnosis column to convert categorical labels (M, B) to numerical labels (1, 0).
Split the dataset into training and testing sets (75% training, 25% testing).
Standardized the features to ensure uniformity in scale.
Models
Three classification models were implemented for predicting cancer diagnosis:

Logistic Regression
Decision Tree
Random Forest
Evaluation
Each model was trained on the training set and evaluated on the testing set.
Performance metrics such as accuracy, precision, recall, and F1-score were computed.
Confusion matrices were generated to visualize the model's performance.
Results
Logistic Regression achieved a testing accuracy of 94.41%.
Decision Tree achieved a testing accuracy of 95.10%.
Random Forest achieved a testing accuracy of 96.50%.
Usage
Clone the repository:
bash
Copy code
git clone https://github.com/your_username/cancer-diagnosis-prediction.git
Install the required dependencies:
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook Cancer_Diagnosis_Prediction.ipynb to train the models and evaluate their performance.
Contributors
Anumula Swetha Sri
