# MASHROOM

📁 Dataset
Filename: agaricus-lepiota.data
Source: UCI Machine Learning Repository
Description: Each record represents a mushroom with 22 categorical features and a target variable:

e: edible

p: poisonous

Attributes (Columns):

cap-shape, cap-surface, cap-color, bruises, odor, gill-attachment, gill-spacing, gill-size, gill-color, stalk-shape, stalk-root, stalk-surface-above-ring, stalk-surface-below-ring, stalk-color-above-ring, stalk-color-below-ring, veil-type, veil-color, ring-number, ring-type, spore-print-color, population, habitat

🧪 Project Steps
Data Preprocessing

Assign column names

Handle missing values (?)

Encode categorical variables using Label Encoding

Model Building

Split data into training and testing sets

Train a Random Forest Classifier

Use GridSearchCV for hyperparameter tuning

Evaluation

Check best parameters

Evaluate test accuracy

Optional: Feature importance visualization

🧮 Libraries Used
bash
Copy
Edit
pandas
numpy
scikit-learn
🔧 Hyperparameters Tuned
n_estimators: [50, 100, 150]

max_depth: [None, 5, 10]

min_samples_split: [2, 5]

min_samples_leaf: [1, 2]

criterion: ['gini', 'entropy']

🎯 Objective
To build a reliable classifier that can predict whether a mushroom is edible or poisonous based on its physical characteristics.
