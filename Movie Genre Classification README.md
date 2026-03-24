This project focuses on predicting the genre of a movie using its plot summary with the help of Natural Language Processing (NLP) and Machine Learning techniques. The goal is to build a model that can automatically classify movies into genres based on textual data.

Movie genres play an important role in recommendation systems and content organization. In this project, we use text-based features extracted from movie plots and apply machine learning algorithms to classify them into different genres. The model is trained and evaluated using standard performance metrics like Accuracy, F1-score, and Confusion Matrix.
Dataset: CMU Movie Summary Dataset
Contains:
Movie metadata (title, genres)
Plot summaries
Target Column: Genre (converted into numerical labels using encoding)
Note:
Only top 10 most frequent genres are used
Each movie is assigned a single primary genre

The model achieves good accuracy and balanced F1-score
Performs well across the most frequent genres
Confusion matrix helps visualize prediction performance

Future Improvements: Use multi-label classification (movies can have multiple genres), Apply deep learning models (LSTM, BERT), Perform hyperparameter tuning, Add more models for comparison (Naive Bayes, Logistic Regression), Deploy as a web application (Streamlit).
