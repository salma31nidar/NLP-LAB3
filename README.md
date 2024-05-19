# NLP-LAB3

## Overview

This repository contains the code and data for the Natural Language Processing (NLP) project conducted as part of the AISD Master's program at the Faculty of Sciences and Techniques of Tangier, Abdelmalek Essaadi University. The project focuses on language modeling, regression, and classification tasks using various NLP techniques and machine learning algorithms.

## Project Structure

- `part1/`: Code and data for Part 1 of the project, which involves language modeling and regression.
- `part2/`: Code and data for Part 2 of the project, which focuses on language modeling and classification.
- `data/`: Contains the datasets used in the project.
- `README.md`: This file, providing an overview of the project and instructions for usage.

## Part 1: Language Modeling / Regression

In Part 1, we followed these steps:

1. **Data Preprocessing**: We cleaned the text data by converting it to lowercase, removing punctuation and numbers, tokenizing, and lemmatizing.
2. **Data Encoding**: We encoded the data vectors using Word2Vec (CBOW and Skip Gram), Bag of Words, and TF-IDF techniques.
3. **Model Training**: We trained Support Vector Regression (SVR), Naive Bayes, Linear Regression, and Decision Tree models using the encoded data vectors.
4. **Model Evaluation**: We evaluated the models using Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).
5. **Interpretation of Results**: We observed that SVR and Linear Regression performed relatively better in terms of accuracy and overall regression metrics compared to Naive Bayes and Decision Tree. However, we noticed that the low accuracy of Naive Bayes and Decision Tree models still provided valuable insights, especially in predicting the majority classes.

## Part 2: Language Modeling / Classification

In Part 2, the workflow was as follows:

1. **Data Preprocessing**: We applied a similar preprocessing pipeline as Part 1 to clean and tokenize the text data.
2. **Data Encoding**: We encoded the data vectors using Word2Vec, Bag of Words, and TF-IDF techniques.
3. **Model Training**: We trained Support Vector Machine (SVM), Naive Bayes, Logistic Regression, and Ada Boosting models using the encoded data vectors.
4. **Model Evaluation**: We evaluated the models using Accuracy and F1 Score metrics.
5. **Interpretation of Results**: We found that SVM and Logistic Regression achieved the highest accuracy compared to Naive Bayes and Ada Boosting. However, all models provided valuable insights for sentiment analysis tasks.

## Synthesis

Through this project, we gained hands-on experience in preprocessing natural language data, encoding text into numerical features, training machine learning models, and evaluating model performance. We also learned about the strengths and limitations of different NLP techniques and algorithms in solving real-world problems.

## Repository Link

[Link to the GitHub Repository](https://github.com/your_username/your_repository)

Feel free to explore the code and data in the repository!

