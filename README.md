Data Collection – Laptop dataset containing specifications and prices is used for training.

Data Preprocessing – Features like processor speed, RAM size, and storage are cleaned and prepared.

Model Training – A Random Forest Regressor is trained on the dataset to learn price patterns.

Model Saving – The trained model is saved using Joblib (rf_model.pkl).

Web App Integration – A Streamlit app (app.py) is built to take user input.

User Input – Users enter processor speed, RAM, and storage through an interactive UI.

Prediction – The model predicts the price instantly and displays it in the web app.

Deployment – The app can be run locally or deployed on Streamlit Cloud for public access.
