# Phishing-URL-detection-using-ML
This project implements a machine learning-based system to detect phishing URLs by analyzing various features of URLs. The goal is to classify URLs as either phishing or legitimate.

## Steps to Run the Notebook
1. Clone the GitHub Repository
Open your terminal or command prompt.
Clone the repository using the following command:

        git clone https://github.com/username/repository_name.git
   
3. Navigate to the Cloned Repository
Move into the project directory:
    
        cd repository_name
   
5. Install Jupyter Notebook
Ensure that Jupyter Notebook is installed on your system. You can install it using:
    
        pip install notebook
   
7. Start Jupyter Notebook
Launch Jupyter Notebook in the directory where the .ipynb file is located:
bash

        jupyter notebook
This will open the Jupyter interface in your web browser.

8. Open the Notebook
Locate the .ipynb file in the interface and click on it to open.

9. Verify Dataset Availability
Ensure the dataset is in the correct location as referenced in the notebook (e.g., in the same directory or a subfolder like data/).
If the dataset is missing, download it from the repository and place it in the required location.

11. Run the Notebook
Use the "Run All" option or execute each cell step by step to reproduce the results and view outputs.


## Steps to Run the Notebook in Kaggle
1. Upload the Files
Log in to your Kaggle account.
Navigate to the "Code" section and click on "Create New Notebook".
In the notebook interface, click on the "Add Data" button in the right panel.
Upload both the .ipynb file and the dataset files.

2. Open the Uploaded Notebook
Once uploaded, find your .ipynb file in the notebook editor and open it.

3. Ensure Dataset Accessibility
If the dataset is uploaded separately, ensure the file paths in your notebook match the Kaggle file structure.

4. Run the Notebook
Click "Run All" from the top menu to execute all the cells in the notebook.

## To Load the Saved Pickle File(Best Model) in a new Python File
Once the machine learning model is saved as a .pkl file using the pickle module, you can load it into a new Python file for predictions or evaluation. Below is the process:


    import pickle
    
    # Load the saved model
    with open('best_model.pkl', 'rb') as file:
        loaded_model = pickle.load(file)


