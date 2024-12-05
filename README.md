# Phishing-URL-detection-using-ML
This project implements a machine learning-based system to detect phishing URLs by analyzing various features of URLs. The goal is to classify URLs as either phishing or legitimate.


## To Load the Saved Pickle File(Best Model) in a new Python File
Once the machine learning model is saved as a .pkl file using the pickle module, you can load it into a new Python file for predictions or evaluation. Below is the process:

'''
import pickle

# Load the saved model
with open('best_model.pkl', 'rb') as file:
    loaded_model = pickle.load(file)

'''
