# Spam/Ham Email Detection using Machine Learning

## Overview
This project builds a **Spam/Ham Email Detection System** using Machine Learning and Natural Language Processing (NLP). 
The system analyzes email messages and classifies them as **Spam** or **Ham (Not Spam)**.

The project uses **TF-IDF Vectorization** to convert text messages into numerical features and a **Logistic Regression** model to perform binary classification.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Jupyter Notebook (Anaconda)

---

## Dataset
Dataset used: **mail_data.csv**

Columns:
- Category (Spam or Ham)
- Message (Email text)

Label encoding used in the project:
Spam = 0  
Ham = 1

---

## Machine Learning Workflow
1. Import required libraries
2. Load dataset
3. Data preprocessing
4. Label encoding (Spam/Ham)
5. Train-test split
6. Feature extraction using TF-IDF
7. Train Logistic Regression model
8. Evaluate model accuracy
9. Predict new email message

---

## Model Used
**Logistic Regression**

Why Logistic Regression?
- Works well for binary classification problems
- Efficient for text classification tasks
- Simple and interpretable model

---

## Model Performance

Example output:

Training Accuracy: ~0.99  
Testing Accuracy: ~0.96

---

## Example Prediction

Input:
"Click on this link to avail free free free money"

Output:
Spam Email

---

## Project Structure

Spam-Ham-Email-Detection/                                                                                                                                         
│                                                                                                                                                                 
├── mail_data.csv                                                                                                                                                 
├── spam_ham_email_detection.ipynb                                                                                                                                
├── README.md                                                                                                                                                     
└── requirements.txt                                                                                                                                              

---

## Author
Balamurugan S  
Computer Science Student  
Interested in Machine Learning and Data Science
