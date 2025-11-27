🎬 Sentiment Analysis Web App

A fully interactive Sentiment Analysis system built using Python, Streamlit, and multiple Machine Learning models, featuring a beautiful UI, graphs, dataset upload module, and real-time predictions.

🚀 Features
✔ Upload Your Own Dataset

Upload any IMDB-style CSV with review and sentiment columns.

✔ 5 Machine Learning Models

The app trains and compares:

Logistic Regression

Naive Bayes

XGBoost

SVM (LinearSVC)

Random Forest

✔ Modern UI & Dark Theme

Custom CSS

Gradient backgrounds

Styled prediction cards

Sidebar navigation

✔ Real-Time Predictions

Enter any movie review and instantly see predictions from the selected ML model.

✔ Model Performance Dashboard

Accuracy comparison bar chart

Confusion matrix heatmaps

Detailed evaluation per model

✔ Advanced Text Preprocessing

HTML removal

Stopword filtering

Lowercasing

Stemming

TF-IDF using unigrams + bigrams (max 50,000 features)

📁 Project Structure
.
├── app.py  
└── (Upload your dataset via the app interface)


No manual dataset placement is required — just upload it when the app starts.

🧠 Requirements

Python 3.8+

Streamlit

Scikit-Learn

XGBoost

Seaborn

NLTK

Install dependencies:

pip install streamlit scikit-learn xgboost seaborn nltk

▶️ Run the App
streamlit run app.py


Then open the local URL shown in the terminal.

