# IMDB Movie Review Sentiment Analysis

## About the Project
This project uses Machine Learning to classify IMDB movie reviews as **Positive** or **Negative**. It uses the IMDB Dataset of 50K Movie Reviews.

## Dataset
- **Name:** IMDB Dataset of 50K Movie Reviews
- **Total Reviews:** 50,000
- **Classes:** Positive and Negative

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- XGBoost
- Logistic Regression
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow
1. Load and explore the dataset.
2. Clean and preprocess the movie reviews.
3. Extract text features using TF-IDF Vectorization.
4. Split the data into training and testing sets.
5. Train two Machine Learning models:
   - Logistic Regression
   - XGBoost Classifier
6. Evaluate the models using accuracy, precision, recall, F1-score, and confusion matrices.
7. Save the trained models and predictions.

## Models and Results

The models were evaluated on a held-out test set.

| Metric | XGBoost | Logistic Regression |
|---|---:|---:|
| Accuracy | 85.62% | 89.27% |
| Precision | 84.30% | 88.62% |
| Recall | 87.90% | 90.33% |
| F1-score | 86.06% | 89.50% |

**Best Performing Model:** Logistic Regression

Logistic Regression achieved better results than XGBoost across all four reported evaluation metrics.
