# Emotion-Classification-of-Arabic-Twitter-Data


## Overview
This project focuses on sentiment classification of Arabic Twitter data. The objective is to develop a model that can classify Arabic tweets into different sentiment categories. The project involves various preprocessing techniques, model comparison, and the use of Explainable AI tools to gain insights into the models' predictions.

## Preprocessing
The following preprocessing steps were performed on the Arabic text data:

Importing Libraries: The necessary libraries and dependencies were imported to facilitate data preprocessing, modeling, and analysis.

Text Preprocessing: The Arabic text was preprocessed by removing diacritics, links, English letters, numbers, and repeated characters. These steps help in cleaning the text data and preparing it for further analysis.

Punctuation Removal: Punctuation marks were removed from the text data to eliminate noise and standardize the text format.

Emoji Replacement: Emojis were replaced with text equivalents to improve the model's performance. This step allows the model to capture the sentiment associated with different emojis.

Text Normalization: The Arabic text was normalized to ensure consistent representation and improve the accuracy of the models.

Tokenization and Stemming: The preprocessed text was tokenized, and two different stemmers were applied to obtain the root form of the words. This step helps in reducing the dimensionality of the text data and improving model performance.

## Modeling Phase
The modeling phase involved comparing several machine learning models for sentiment classification. The following models were evaluated:

Naive Bayes
Decision Tree
Support Vector Machine (SVM)
Logistic Regression
Ensemble Learning
Each model was trained on the preprocessed Arabic Twitter data to predict the sentiment category of the tweets. Model performance metrics, such as accuracy, precision, recall, and F1 score, were calculated to assess and compare the models' effectiveness.

## Explainable AI with LIME
In order to gain insights into the models' predictions and understand the features that affected the predictions, LIME (Local Interpretable Model-Agnostic Explanations) was used. LIME is an Explainable AI tool that helps to explain black-box machine learning models.

The project utilized LIME to analyze the sentiment classification models and identify the important features that influenced the predictions. By calculating the mean weight for each word for each class, the project aimed to determine the words that significantly impacted each sentiment category.

## Contributors
This project was made possible by the contributions of the following individuals:

Mahmoud Alaa
Karim Anani
Alaa Mahmoud
Mirna Maher

## Conclusion
This project demonstrates the sentiment classification of Arabic Twitter data using various preprocessing techniques and machine learning models. The project highlights the importance of text preprocessing in improving model performance. By comparing multiple models, the project identifies the most effective model for sentiment classification.

The utilization of LIME for explainability provides valuable insights into the models' predictions and the words that contribute significantly to each sentiment category. These insights can aid in understanding the sentiment patterns in Arabic Twitter data and guide future improvements in sentiment analysis tasks.
