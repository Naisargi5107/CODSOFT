 📩 Spam SMS Detection using Machine Learning

 🚀 Project Overview

This project builds a Machine Learning model to classify SMS messages as **Spam** or **Ham (Legitimate)**.

It uses **Natural Language Processing (NLP)** techniques like TF-IDF vectorization along with classification algorithms to accurately detect spam messages.

🧠 Technologies Used

* Python 🐍
* Pandas
* NLTK (Natural Language Toolkit)
* Scikit-learn

⚙️ Features

* Text preprocessing (lowercasing, regex cleaning, stopword removal)
* TF-IDF vectorization (unigrams + bigrams)
* Machine Learning model (Naive Bayes)
* Model evaluation (Accuracy + Classification Report)
* Real-time SMS prediction via user input

📂 Dataset
* Dataset file: `spam.csv`
* Contains labeled SMS messages:

  * **spam**
  * **ham**

⚠️ If dataset is large, provide Google Drive link here.

🔄 Workflow
1. Load dataset
2. Clean and preprocess text
3. Convert text into numerical features using TF-IDF
4. Train model using Naive Bayes
5. Evaluate performance
6. Predict new SMS messages

📊 Model Performance
* Accuracy: ~95%+ (depends on dataset split)
* Includes precision, recall, and F1-score

💡 Example
Enter a message: Congratulations! You won a free ticket
Spam Probability: 0.92
Result: SPAM

📌 Future Improvements

* Add Logistic Regression / SVM models
* Use word embeddings (Word2Vec, GloVe)
* Deploy as a web app (Streamlit / Flask)
* Improve preprocessing with stemming/lemmatization

⭐ Conclusion

This project demonstrates how Machine Learning and NLP can be applied to solve real-world problems like spam detection effectively.

