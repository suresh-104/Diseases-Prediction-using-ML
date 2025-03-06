🩺 Multiple Disease Prediction using Machine Learning An AI-powered web application that predicts Diabetes, Heart Disease, and Parkinson’s using Machine Learning (SVM). The app provides a user-friendly interface built with Streamlit and ensures real-time health predictions.

Step-by-Step Project Implementation Step-1 Install Dependencies pip install requirements

Step-2 Load and Preprocess Data
Download the dataset and place it in the dataset/ folder.
Perform data preprocessing using Pandas and NumPy.
Apply feature scaling using StandardScaler.

Step-3 Train the Machine Learning Model
Use Support Vector Machine (SVM) as the classifier.
Train the model using Scikit-learn.
Save the trained model using Pickle for later use.

Step-4 Build the Streamlit Web App
Create a user input form in Streamlit.
Load the trained ML model to make real-time predictions.
Display prediction results in the UI.

Step-5 Run the Application Locally streamlit run web.py
Machine Learning Model
Algorithm Used: Support Vector Machine (SVM)
Preprocessing: StandardScaler for feature scaling
Model Storage: Pickled for efficient loading
Performance: Achieved high accuracy after hyperparameter tuning

web app link - https://multiple-diseases-predication-depoly-khzgvx9ftlvwz3waf5fotk.streamlit.app/
