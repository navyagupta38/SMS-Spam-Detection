A machine learning model to classify SMS messages as spam or ham using the SMS Spam Collection dataset. Applied NLP techniques like tokenization and TF-IDF vectorization, and trained a Naive Bayes classifier. Achieved over 95% accuracy. Tools used include Python, Scikit-learn, Pandas, NumPy, Matplotlib and Seaborn.

Workflow:

Data Collection: Used the open-source "SMS Spam Collection" dataset.

Data Preprocessing:

Removal of punctuation and stopwords

Lowercasing

Tokenization and vectorization (CountVectorizer or TF-IDF)

Model Training:

Split data into training and test sets

Train model (e.g., Naive Bayes) on processed data

Evaluation:

Accuracy, Precision, Recall, F1-Score

Confusion Matrix visualization

Prediction Interface:

A simple script or UI where users can input a message and get instant classification.
