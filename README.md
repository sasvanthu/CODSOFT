Spam SMS Detector:
This is a simple machine learning project to detect spam SMS messages using Python and Naive Bayes.

Dataset
Used: SMS Spam Collection Dataset (from UCI)

How it works:
1. Loads and cleans the data
2. Converts text to numerical features using TF-IDF
3. Trains a Naive Bayes model
4. Predicts and evaluates on test data

To Run Locally
```bash
pip install -r requirements.txt
python spam_detector.py
