# Heart-disease-detection-using-machine-learning
This project aims to detect heart disease using machine learning by employing and combining three different algorithms: Support Vector Machine (SVM), LightGBM (LGBM), and XGBoost (XGB). The process involves evaluating each model individually and then combining them to enhance prediction accuracy.

Imports and Dataset Preparation:
Import the necessary libraries including pandas, numpy, lightgbm, xgboost, sklearn, and joblib.
Load the dataset into a pandas DataFrame and split it into features (X) and target (y).
Model Training:
SVM:
Initialize an SVM classifier.
Train the SVM classifier on the dataset.
Evaluate the accuracy of the SVM model.
LightGBM (LGBM):
Initialize a LightGBM classifier.
Train the LGBM classifier on the dataset.
Evaluate the accuracy of the LGBM model.
XGBoost (XGB):
Initialize an XGBoost classifier.
Train the XGB classifier on the dataset.
Evaluate the accuracy of the XGB model.
Model Evaluation:
Print the accuracy of each individual model to compare their performance.
Combining Models:
Combine the predictions of SVM, LGBM, and XGB using a voting classifier to improve the overall prediction accuracy.
Train the combined model on the dataset and evaluate its performance.
Saving the Model:
Save the combined model using joblib for later use in predictions.
GUI Application:
Create a Tkinter-based GUI to collect user inputs for various medical attributes (age, sex, chest pain type, etc.).
Validate user inputs to ensure they are within acceptable ranges.
Load the saved combined model and use it to make predictions based on user inputs.
Display the prediction result (presence or absence of heart disease) using a message box.
Running the Application:
Set up the GUI layout with labels, entry fields, and a button to trigger the prediction.
Define the function to handle the prediction process when the 'Detect' button is clicked.

The Heart Disease Detection System is a machine learning application using LightGBM for predicting heart disease based on user inputs. It involves two main parts: model training and a Tkinter-based GUI for prediction.

1. Model Training: 
•	Import necessary libraries including `lightgbm`, `pandas`, and `joblib`.
•	Load the dataset into a DataFrame (`df`) and split it into features (`X`) and target (`y`).
•	Train a `LGBMClassifier` model using the feature and target data.
•	Save the trained model using `joblib` for later use.

2. GUI Application:
•	Use `tkinter` to create a graphical user interface for user input.
•	The GUI includes entry fields for various medical attributes such as age, sex, chest pain type, and others.
•	Validate the input data to ensure it falls within acceptable ranges.
•	Load the pre-trained LightGBM model using `joblib`.
•	On clicking the 'Detect' button, the input data is collected and passed to the model for prediction.
•	Display the prediction result (presence or absence of heart disease) using a message box.
•	Use `Pillow` for displaying an image as the background of the GUI.

