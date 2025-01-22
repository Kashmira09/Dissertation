# Predectitive Analysis of Social Media Sentiments and Its Impact on Mental Health
## About the Project
This project focuses on predicting mental health outcomes using sentiment analysis on social media data. The aim is to analyze and understand emotional patterns in textual data from platforms like Twitter, Reddit, and other social networks. By leveraging machine learning techniques, this research identifies sentiments and their impact on mental health, providing actionable insights for early intervention.

## Methodologies Used
1. Natural Language Processing (NLP):
    * Applied NLP techniques for text preprocessing, including tokenization, lemmatization, and removal of stop words, URLs, and special characters.
    * Utilized TF-IDF vectorization to transform raw textual data into numerical features suitable for sentiment classification.
2. Support Vector Machine (SVM):
    * Implemented SVM as a robust machine learning algorithm to classify text data into binary classes (mental health concerns vs. normal).
    * Leveraged its ability to handle high-dimensional data, ensuring effective sentiment classification.
3. Logistic Regression:
    * Used Logistic Regression as a simple and interpretable baseline model for sentiment analysis.
    * Incorporated SMOTE to address class imbalance, ensuring fair representation of minority classes during training.
4. Multinomial Naive Bayes:
    * Implemented Naive Bayes to classify sentiments efficiently based on probabilistic learning principles.
    * Its computational efficiency made it an effective choice for benchmarking against other models.

## Dataset Used
* The dataset was sourced from Kaggle and consists of 53,074 records of textual data categorized into six mental health classes, including Normal, Anxiety, Depression, Stress, Bipolar, and Personality Disorder.
* The data includes diverse entries from platforms like Twitter and Reddit, ensuring comprehensive coverage of social media sentiment.

## Literature Review
* Reviewed studies on sentiment analysis and mental health to identify limitations in cross-platform emotional analysis.
* Focused on insights into text classification techniques like TF-IDF, SVM, and deep learning methods for emotion recognition.
* Integrated findings to justify the use of lightweight yet effective machine learning models.

## Project Deliverables
1. Code Files:
    * Python scripts for data preprocessing, SMOTE balancing, and model implementation (SVM, Logistic Regression, and Naive Bayes).
2. Dataset:
    * Provided a cleaned and preprocessed version of the dataset used for training and evaluation, ensuring reproducibility.
3. Report:
    * A comprehensive report detailing project objectives, methodologies, results, and conclusions.
4. Presentation:
    * A concise presentation summarizing the problem, methodologies, experiments, results, and future scope.

## GitHub Repository
 All project materials, including code files, datasets, report, and presentation, are available in the GitHub repository. This ensures transparency, collaboration, and accessibility for future research and development.
