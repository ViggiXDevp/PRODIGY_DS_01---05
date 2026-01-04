# Bank Marketing – Decision Tree Classifier - Task 3 🌳

## Overview 🌐
Built a decision tree classifier to predict whether a bank customer will subscribe to a term deposit (`y` = yes/no) using the Bank Marketing Dataset from Kaggle.  
The project covers data preprocessing, model training, and evaluation on real marketing campaign data.

## Dataset 📁
- **Name:** Bank Marketing Dataset  
- **Source:** [Kaggle](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset)  
- **Description:** Marketing calls from a Portuguese bank, with customer info, campaign details, and whether they subscribed to a term deposit.  

**Example columns:**  
- Demographics: `age`, `job`, `marital`, `education`  
- Financial: `balance`, `housing`, `loan`, `default`  
- Campaign: `contact`, `month`, `day`, `duration`, `campaign`, `pdays`, `previous`, `poutcome`  
- **Target:** `y` (client subscribed to term deposit: yes / no)

## What I Implemented ✅
- **Data Loading & Cleaning**
  - Loaded the CSV with `pandas` and checked structure, missing values, and basic statistics.  
  - Handled missing/unknown categories and prepared features for modeling.

- **Feature Engineering & Encoding**
  - Encoded categorical variables (e.g., job, marital, contact, month) using techniques like one-hot or label encoding for scikit-learn.  
  - Optionally scaled or normalized numerical features where helpful.

- **Model Building – Decision Tree**
  - Split data into training and testing sets (e.g., 80/20) using `train_test_split`.  
  - Trained a `DecisionTreeClassifier` (Gini/Entropy) on the processed features to predict `y`.  
  - Tuned hyperparameters such as `max_depth`, `min_samples_split`, and `criterion` to reduce overfitting.

- **Evaluation & Interpretation**
  - Evaluated the model using accuracy, precision, recall, F1-score, and confusion matrix.  
  - Visualized the tree or inspected feature importances to understand which attributes influence subscription decisions the most.

## Tech Stack 🛠️
- **Language:** Python  
- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`  
- **Environment:** Jupyter Notebook / Google Colab
