🚗 Car Brand Classification using Decision Tree
This project aims to build a machine learning model that classifies cars into their respective brands — such as US, Japan, and Europe — based on several car features using a Decision Tree Classifier.

📂 Dataset Description
The dataset used is cars.csv, which contains various specifications of cars and their brand origin. Key features include:
Horsepower
Cubic Inches
Weight
Model Year
MPG (Miles per Gallon)
Acceleration
...and more

The target column is:
Brand: Categorical label indicating whether the car is from US, Japan, or Europe.

🧪 Project Workflow
1. Data Preprocessing
Handled missing values using mean imputation.
Removed duplicate records.
Selected numerical features for model training.
Encoded categorical labels (Brand) if needed.

2. Model Training
Applied Decision Tree Classifier from scikit-learn.
Split dataset into training (70%) and testing (30%).

3. Evaluation
Evaluated using accuracy score.
Visualized the decision tree structure using plot_tree().
