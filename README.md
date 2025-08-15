# Spam Detection using Naive Bayes

This project implements a spam detection system using the Naive Bayes algorithm, specifically tailored for classifying SMS messages as spam or not spam. The system is built using Python and scikit-learn, leveraging the SMS Spam Collection dataset to train and evaluate the model. The project includes text preprocessing, feature extraction using TfidfVectorizer, and evaluation of the model using accuracy and classification metrics.

## How It Works
1. **Dataset**: The SMS Spam Collection dataset is used, which contains labeled text messages marked as "spam" or "ham" (not spam).
2. **Preprocessing**: The text data is cleaned by removing punctuation, numbers, and extra spaces. The text is then converted into numerical features using the TfidfVectorizer.
3. **Model**: A Naïve Bayes classifier is trained on the dataset to predict whether a message is spam or not.
4. **Evaluation**: The model's accuracy is evaluated using standard classification metrics such as precision, recall, and F1-score.
   
   **Visualizations**:
   - **Confusion Matrix Plot**: Shows the actual vs predicted values for spam and ham.
   - **Bar Chart**: Displays the precision, recall, and F1-score for both "ham" and "spam" classes.

## Author
This project was developed by **Subaru Sir!**.
