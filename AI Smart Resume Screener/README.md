📄 AI Smart Resume Screener

This project demonstrates how machine learning and NLP techniques can be applied to automate the process of comparing job descriptions (JDs) with candidate resumes. It acts as a proof-of-concept for building intelligent recruitment tools.

📌 Objective

Predict whether a candidate’s resume is a good fit for a given job description.

Label 1 → Match (resume fits the JD)

Label 0 → Not a Match (resume doesn’t fit)

📊 Dataset

A small, manually created dummy dataset of JD–Resume pairs.

Each pair is annotated with a binary label (1 = Match, 0 = Not Match).

Example:

JD: “Looking for a Python developer with ML and AWS experience.”

Resume: “Python engineer skilled in ML and AWS.”

Label: 1

⚙️ Preprocessing

The text data is cleaned and transformed before model training:

Lowercasing

Removal of punctuation and numbers

Stopword removal

Feature extraction using TF-IDF vectorization

🤖 Models Implemented

Two machine learning models were tested:

Random Forest Classifier

Decision Tree Classifier

Both models are trained on TF-IDF features of JD–Resume text pairs.

🚀 Workflow

Prepare JD–Resume dataset

Preprocess and clean text data

Convert text into numerical features using TF-IDF

Train and evaluate machine learning models

Test predictions on unseen JD–Resume pairs
