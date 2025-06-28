# Fakenewsdetector
Key Features of This Implementation:
Text Preprocessing Pipeline:

URL removal, punctuation removal, lemmatization
Stopword removal and tokenization
Machine Learning Components:

Uses TF-IDF vectorization for feature extraction
Implements PassiveAggressiveClassifier (good for text classification)
Includes model evaluation metrics (accuracy, confusion matrix)
Practical Features:

Model saving and loading functionality
Interactive menu system for training/testing
Sample test cases for demonstration
Visualization:

Class distribution chart
Confusion matrix visualization
Error Handling:

Graceful handling of missing data
Warning suppression for cleaner output
To use this project, you'll need a dataset with news articles labeled as real (0) or fake (1). The expected CSV format should have at least 'text' and 'label' columns. You can find suitable datasets on Kaggle (search for "fake news dataset").

Required Python packages:

pandas
numpy
nltk
scikit-learn
matplotlib
seaborn
joblib
Install them with:


Run
Copy code
pip install pandas numpy nltk scikit-learn matplotlib
