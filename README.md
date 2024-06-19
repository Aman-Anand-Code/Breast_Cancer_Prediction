# Breast_Cancer_Prediction

Breast Cancer Classification using SVM
Project Overview
This project involves developing a machine learning model to classify breast cancer as benign or malignant using a Support Vector Machine (SVM). The dataset used for this project includes various features representing breast cancer measurements. The project focuses on data preprocessing, exploratory data analysis, model development, and performance evaluation.

Table of Contents
Project Overview
Dataset
Installation
Usage
Project Structure
Results

Dataset
The dataset used in this project contains features related to breast cancer measurements, including:

mean_radius
mean_texture
mean_perimeter
mean_area
mean_smoothness
diagnosis (target variable: 0 for benign, 1 for malignant)
Installation
To run this project, you need to have Python installed along with the following libraries:

NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
You can install the required libraries using pip:

bash
Copy code
pip install numpy pandas matplotlib seaborn scikit-learn
Usage
Clone this repository:
bash
Copy code
git clone https://github.com/your-username/breast-cancer-classification-svm.git
Navigate to the project directory:
bash
Copy code
cd breast-cancer-classification-svm
Run the Jupyter notebook or Python script to see the results:
bash
Copy code
jupyter notebook Breast_Cancer_Classification.ipynb
# or
python Breast_Cancer_Classification.py
Project Structure
css
Copy code
breast-cancer-classification-svm/
│
├── data/
│   └── Breast_cancer_data.csv
│
├── notebooks/
│   └── Breast_Cancer_Classification.ipynb
│
├── src/
│   └── Breast_Cancer_Classification.py
│
├── README.md
├── requirements.txt
└── LICENSE

Results
EDA: Visualized data distributions and correlations.
Modeling: Implemented and tuned SVM using Grid Search and Cross-Validation.
Evaluation: Achieved high accuracy, precision, recall, and F1-score.
Insights: Provided actionable insights for better diagnosis and treatment.
