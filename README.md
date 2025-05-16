# 🍷 Red Wine Quality Prediction

This project focuses on building a machine learning model to predict the **quality of red wine** based on its physicochemical properties. By applying data analysis and classification techniques, we aim to determine which features most influence wine quality and how accurately it can be predicted.

## 🎯 Objective

- Analyze the relationship between various chemical features and wine quality.
- Build and evaluate machine learning models to classify wine samples.
- Identify key features contributing to high or low-quality wine.

## 🧰 Tools & Technologies

- **Python 3**
- **Pandas / NumPy** – Data manipulation and numerical operations
- **Matplotlib / Seaborn** – Data visualization and EDA
- **Scikit-learn** – Machine learning models and evaluation
- **Jupyter Notebook** – Interactive development environment

## 🗂️ Dataset

The dataset includes information on red wine samples with the following features:
- `fixed acidity`, `volatile acidity`, `citric acid`
- `residual sugar`, `chlorides`, `free sulfur dioxide`, `total sulfur dioxide`
- `density`, `pH`, `sulphates`, `alcohol`
- `quality` (target variable – score between 0 and 10)

> Source: [UCI Machine Learning Repository - Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

## 📊 Workflow

1. **Data Exploration & Cleaning**
   - Check for null values and data types
   - Summary statistics and outlier detection
2. **Exploratory Data Analysis (EDA)**
   - Distribution of wine quality scores
   - Correlation matrix between features
   - Pair plots and histograms
3. **Model Building**
   - Train/Test split
   - Classification models (e.g., Logistic Regression, Random Forest, Decision Tree)
4. **Model Evaluation**
   - Accuracy, precision, recall, F1-score
   - Confusion matrix and feature importance

## ✅ Results

- Achieved high classification accuracy with tree-based models.
- Alcohol, sulphates, and volatile acidity were among the most influential features.
- The dataset is imbalanced, with more medium-quality wines than low/high quality.

## 📌 Insights

- Wines with higher alcohol and sulphates tend to have better quality ratings.
- Volatile acidity is negatively correlated with wine quality.
- Certain physicochemical features have little to no impact on classification and can be excluded to simplify models.

## 🧠 Skills Demonstrated

- Data preprocessing and feature selection
- Classification model training and tuning
- Performance evaluation and interpretation
- Scientific communication through visualizations

## ▶️ How to Run

1. Clone the repository or download the `.ipynb` file.
2. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3.Open Determining Red Wine Quality.ipynb in Jupyter Notebook.
4. Run the notebook to see data analysis, visualizations, and model results.
