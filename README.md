The repository contains the Machine Learning module of my college group project, AI-based Financial Fraud Detection System.


The deployed application can be accessed here:
Live Application: https://ai-powered-financial-fraud-detection-nbnze8mkfwqvnc7okth2bs.streamlit.app/


My responsibility in this project is to design, develop, and evaluate the machine learning models that detect fraudulent financial activities and generate transaction risk scores.The web application and user interface were developed by other members of the team, while this repository currently focuses on the ML implementation.
The objective is to identify potentially fraudulent transactions and assist users by providing an estimated fraud risk score for different payment scenarios.
As Machine Learning Engineer for this project, I worked on:
* Data preprocessing and cleaning
* Exploratory Data Analysis(EDA)
* Feature Engineering
* Training ML models
* Model evaluation
* Hyperparameter tuning
* Explainable AI
* Model saving for deployment
* Developing separate fraud detection models for multiple transaction types( e.g. QR code, UPI, Bank transaction)
Main Fraud Detection Model (The primary notebook containing the end-to-end ML workflow)
Bank Transaction Risk Score (Predicts fraud risk associated with bank transaction-related features)
UPI Id Risk Score (Detects suspicious UPI transactions by analyzing account and transaction behaviour)
QR Code Risk Score (Evaluates QR Code related transaction risks using features extracted from QR code metadata and transaction information)
Technologies used:
* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Random Forest Classifier

The machine learning implementation has been completed and integrated into the project.
The repository primarily showcases my ML contribution,while the complete application was developed collaboratively with my teammates by integrating individual contributions into a Streamlit-based web application.
