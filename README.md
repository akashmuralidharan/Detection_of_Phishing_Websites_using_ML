# Detection_of_Phishing_Websites_using_ML
 
Overview
This project uses machine learning techniques to identify phishing websites. Phishing attacks are attempts to acquire sensitive personal information through fraudulent websites or emails. This notebook demonstrates the steps involved in processing data, building models, and evaluating their performance to detect phishing websites effectively.

Features
Dataset with 50 features and 10,000 rows.
Data preprocessing includes converting data types for efficiency.
Exploratory Data Analysis (EDA) to understand feature correlations.
Machine learning models are trained and evaluated.
Visualization of model performance and insights.

Setup Instructions
Prerequisites: 

Install the following Python libraries:

pandas
numpy
matplotlib
seaborn
cuml
scikit-learn

Use the command:
pip install pandas numpy matplotlib seaborn scikit-learn

To install cuml, run the following command: 

!git clone https://github.com/rapidsai/rapidsai-csp-utils.git
!python rapidsai-csp-utils/colab/pip-install.py

Dataset:

Place your dataset in the Dataset/ directory.
Ensure the dataset is named data.csv.

Run the Notebook: Open the notebook in Jupyter or any compatible IDE and execute the cells sequentially.

Contents
Data Loading: Reads and preprocesses the dataset.
Data Preprocessing: Converts data types for efficiency and scales features for model training.
EDA: Visualizations and statistics to understand feature importance.

Model Building:
Classification models like logistic regression and Random Forest.
Model evaluation metrics like accuracy, precision, f1 score and recall.

Results
The notebook demonstrates the accuracy of various models and identifies the most suitable approach for phishing detection.

GithubRepo link: https://github.com/akashmuralidharan/Detection_of_Phishing_Websites_using_ML