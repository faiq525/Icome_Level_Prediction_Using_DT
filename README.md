# Icome_Level_Prediction_Using_DT
This project analyzes the Adult dataset to predict whether an individual's annual income exceeds $50,000. By leveraging machine learning techniques, including decision trees and hyperparameter tuning, the model provides insights that can be applied to real-world scenarios like targeted marketing and recruitment strategies.

Table of Contents
Overview
Dataset
Techniques Used
Steps Performed
Results
Applications
Requirements
How to Run
Contributing
License
Overview
The project focuses on supervised learning to classify individuals based on income levels. It employs a decision tree classifier and optimizes its performance using GridSearchCV. Visualization and evaluation techniques are incorporated to gain deeper insights into the data and model performance.

Dataset
The Adult dataset from the UCI Machine Learning Repository is used. It includes various features such as:

Age
Work class
Education level
Occupation
Hours per week
Income (>50K or <=50K)
Techniques Used
Data Cleaning & Preprocessing: Removing unnecessary features, handling missing values, and one-hot encoding for categorical variables.
Exploratory Data Analysis (EDA): Using matplotlib and seaborn to visualize distributions and relationships in the data.
Machine Learning: Decision Tree Classifier.
Hyperparameter Tuning: GridSearchCV for optimizing decision tree parameters (e.g., criterion, tree depth).
Evaluation Metrics: Accuracy, confusion matrix, and classification report.
Steps Performed
Load and preprocess the dataset.
Explore data using visualizations.
Split data into training and testing sets.
Train a Decision Tree Classifier.
Tune hyperparameters with GridSearchCV.
Evaluate the model's performance.
Interpret results and draw conclusions.
Results
Achieved an accuracy of X% (replace with actual result) on the test set.
Model performance metrics:
Precision, Recall, and F1-Score were calculated for each income class.
Confusion Matrix provided insights into misclassifications.
Applications
This model can be applied in various real-world scenarios, such as:

Credit Card Marketing: Target high-income individuals for premium products.
Recruitment: Identify candidates for high-paying roles.
Insurance and Investment: Tailor offerings based on income levels.
Upscale Retail Targeting: Personalize advertisements and promotions.
Requirements
To run this project, you need the following Python libraries:

numpy
pandas
matplotlib
seaborn
scikit-learn
tqdm
How to Run
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/income-level-prediction.git
Navigate to the project directory:
bash
Copy code
cd income-level-prediction
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Open and run the Jupyter Notebook:
bash
Copy code
jupyter notebook Data_Science_Project.ipynb
Contributing
Contributions are welcome! Please fork the repository and create a pull request to propose changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.
