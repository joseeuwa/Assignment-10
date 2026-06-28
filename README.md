# Amazon Alexa Customer Review Sentiment Analysis

## Project Overview

This project demonstrates the application of Natural Language Processing (NLP) and Machine Learning techniques to classify Amazon Alexa customer reviews as either positive or negative. The project includes data preprocessing, feature engineering, traditional machine learning models, hyperparameter tuning, model evaluation, and sentiment analysis using a pre-trained BERT model.

This project was completed as part of the **Artificial Intelligence – Lesson 10 Assignment**.

---

## Dataset

The project uses the **Amazon Alexa Reviews Dataset**, a publicly available dataset containing customer reviews of Amazon Alexa products.

Dataset features include:

- Rating
- Date
- Product Variation
- Verified Review
- Feedback (Target Variable)

- **Feedback = 1:** Positive Review
- **Feedback = 0:** Negative Review

Dataset Size:

- **3,150 customer reviews**
- **5 original features**

---

## Project Workflow

The project follows these main steps:

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning and Preprocessing
4. Feature Engineering
5. Text Vectorization
   - Bag of Words (CountVectorizer)
   - TF-IDF
6. Model Training
7. Hyperparameter Tuning using GridSearchCV
8. Model Evaluation
9. Sentiment Prediction using BERT
10. Result Interpretation

---

## Machine Learning Models

The following models were implemented:

- Random Forest Classifier
- Logistic Regression
- Support Vector Machine (SVM)
- DistilBERT (Hugging Face Transformers)

---

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve
- ROC-AUC
- Feature Importance

### Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 90.79% |
| Random Forest | 93.17% |
| Support Vector Machine | 93.97% |
| DistilBERT | Demonstrated highly accurate sentiment predictions on sample reviews |

Among the traditional machine learning models, **Support Vector Machine (SVM)** achieved the highest classification accuracy.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- Transformers (Hugging Face)
- PyTorch

---

## Results

The project demonstrates that machine learning algorithms can effectively classify customer sentiment from text reviews.

Key findings include:

- Customer reviews are predominantly positive.
- Support Vector Machine achieved the highest traditional machine learning accuracy.
- Random Forest also performed well with strong overall classification performance.
- DistilBERT produced highly confident predictions on unseen review examples.
- ROC Curve analysis showed strong discriminative ability for the trained models.

---

## Future Improvements

Possible enhancements include:

- Fine-tuning BERT using the Amazon Alexa dataset.
- Performing Word2Vec or GloVe embedding visualization.
- Deploying the model using Flask or FastAPI.
- Building a web application for real-time sentiment prediction.

---

## Author

Prepared by Josee U
