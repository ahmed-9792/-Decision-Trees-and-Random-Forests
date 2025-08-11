Decision Trees and Random Forests

📌 Objective:
The goal of this task is to learn and implement tree-based models for classification using Decision Trees and Random Forests.
We use the Heart Disease dataset (heart.csv) to predict whether a patient has heart disease.

📂 Dataset:
File: heart.csv

Target Variable: target (0 = No Disease, 1 = Disease)

Features: Age, sex, cholesterol, blood pressure, maximum heart rate, etc.

🛠 Tools & Libraries Used:
Python (3.x)

Pandas – Data manipulation

Scikit-learn – Machine learning models & evaluation

Matplotlib & Seaborn – Visualization

Graphviz (optional) – Better Decision Tree visualization

🚀 Steps Implemented:
Load Dataset

Read heart.csv into a Pandas DataFrame.

Data Preparation

Split dataset into features (X) and target (y).

Perform train-test split (80% train, 20% test).

Decision Tree Classifier

Train a Decision Tree with max_depth=4 to prevent overfitting.

Visualize the Decision Tree using plot_tree.

Random Forest Classifier

Train a Random Forest with 100 estimators (n_estimators=100).

Evaluate accuracy and generate classification report.

Feature Importances

Plot the most important features using a bar chart.

Cross-Validation

Perform 5-fold cross-validation for both models.

📊 Evaluation Metrics:
Accuracy – Percentage of correct predictions.

Classification Report – Precision, Recall, F1-Score.

Cross-Validation Accuracy – Mean accuracy over multiple folds.

📈 Example Output:
Decision Tree Accuracy: ~80-85%
Random Forest Accuracy: ~85-90%

Feature importance example (Random Forest):

cp              0.25
thalach         0.20
oldpeak         0.15
ca              0.10

▶️ How to Run the Code:
Install dependencies:

pip install pandas scikit-learn matplotlib seaborn graphviz
Run the script:

python task5_decision_tree_random_forest.py
For better Decision Tree visualization:

pip install graphviz

📌 Notes:
Adjust max_depth and n_estimators to experiment with model performance.

Cross-validation helps prevent overfitting by evaluating the model on multiple subsets of the data.

Random Forest usually performs better due to averaging multiple trees.

