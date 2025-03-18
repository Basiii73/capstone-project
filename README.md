# Predicting Online Shopper Purchase Intentions Using Machine Learning

## Author
**Abdul Basith**

## Organization
**Entri Elevate**

## 1. Overview of Problem Statement
E-commerce businesses aim to understand customer behavior to optimize sales and user experience. Predicting whether an online shopper will make a purchase is crucial for targeted marketing and improving website performance. However, customer behavior is influenced by various factors like session duration, page visits, and previous purchases, making prediction a challenging task.

This project focuses on building a classification model to predict whether an online shopper will make a purchase based on their session characteristics.

## 2. Objective
To develop an accurate machine learning model for predicting online shopper purchase intentions using various classification algorithms.

## 3. Data Description
- **Source:** UCI Machine Learning Repository
- **Dataset:** `online_shoppers_intention.csv`

### Features:
- **Numerical Features:** Number of pages visited, session duration, bounce rate, exit rate, etc.
- **Categorical Features:** Operating system, browser type, region, traffic type, etc.
- **Target Variable:** `Revenue` (1 for purchase, 0 for no purchase)

## 4. Project Phases
### Phase 1: Data Exploration & Preprocessing
- Loading the dataset
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Exploratory Data Analysis (EDA)

### Phase 2: Model Building
- Train-test split
- Implementing classification models:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree Classifier
  - Random Forest Classifier
  - Gradient Boosting Classifier
  - AdaBoost Classifier
  - Naive Bayes Classifier
  - K-Nearest Neighbors (KNN)
  - Multi-Layer Perceptron (MLP) Classifier

### Phase 3: Model Evaluation & Optimization
- Evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - ROC Curve & AUC Score
- Hyperparameter tuning
- Model comparison & selection

## 5. Installation & Setup
To run this project, install the required libraries using:
```bash
pip install numpy pandas seaborn matplotlib scikit-learn
```

## 6. Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-repo
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 7. Results & Conclusion
- The best-performing model was identified based on evaluation metrics.
- Insights from the model can help businesses tailor their marketing strategies and improve customer engagement.

## 8. Contributions
Feel free to contribute by raising issues or submitting pull requests!

## 9. License
This project is licensed under the MIT License.

