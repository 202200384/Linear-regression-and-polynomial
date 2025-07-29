📘 Project Title: Breast Cancer Classification using Logistic Regression and Decision Tree
📝 Description
This project focuses on analyzing and classifying breast cancer data using two supervised learning algorithms: Logistic Regression and Decision Tree. The goal is to detect potential overfitting or underfitting by evaluating model performance on training, validation, and testing sets.

📂 Project Structure
Task_1_Arabian (4).ipynb – Main Jupyter notebook containing all preprocessing, training, evaluation, and visualization steps.

🧪 Dataset
The dataset used is the Breast Cancer Wisconsin (Diagnostic) Dataset, typically available via:

python
Copy
Edit
from sklearn.datasets import load_breast_cancer
It contains:

Features computed from digitized images of a breast mass

Target: Diagnosis (M = Malignant, B = Benign)

🔍 Project Workflow
Data Loading & Exploration

Load dataset and convert to DataFrame

Analyze target distribution and feature info

Data Preprocessing

Feature scaling using StandardScaler

Train-test-validation split (60% training, 20% validation, 20% testing)

Model Training

Train Logistic Regression model

Train Decision Tree Classifier

Model Evaluation

Evaluate accuracy on training, validation, and test sets

Compare model performance to detect overfitting/underfitting

Visualization

Boxplot for features such as radius_mean by diagnosis

Visualization of accuracy scores across the datasets

📈 Results
Accuracy for Logistic Regression and Decision Tree was evaluated separately on:

Training set

Validation set

Test set

Performance comparison helped identify if any model was overfitting (e.g., high training but low validation accuracy).

⚙️ Requirements
bash
Copy
Edit
pip install pandas matplotlib seaborn scikit-learn
🚀 How to Run
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook Task_1_Arabian (4).ipynb
Run the cells sequentially to see the data analysis and model results.

📌 Future Improvements
Add cross-validation for more robust evaluation.

Use more models like Random Forest or SVM.

Perform feature selection to optimize model accuracy.

