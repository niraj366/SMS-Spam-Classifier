# SMS-Spam-Classifier

A machine learning-based classifier that can predict whether an SMS message is **spam** or **ham (not spam)**. This project demonstrates text preprocessing, feature extraction using TF-IDF, and binary classification using machine learning algorithms.

---

## 🚀 Features
- Classifies messages as **Spam** or **Ham**
- Text preprocessing pipeline (cleaning, removing stopwords, stemming)
- Feature extraction using **TF-IDF vectorizer**
- ML model built using **Multinomial Naive Bayes**
- Web interface using **Streamlit** (if applicable)
- Trained and tested on real SMS dataset

---

SMS-Spam-Classifier/
│
├── data/                 # Dataset (CSV file of SMS messages)
├── notebooks/            # Jupyter notebooks for EDA & model building
├── src/                  # Source code (preprocessing, training, prediction)
│   ├── preprocessing.py
│   ├── train_model.py
│   ├── predict.py
│
├── app.py                # Streamlit web app (if implemented)
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
│
├── model.pkl             # Trained ML model
└── vectorizer.pkl        # TF-IDF vectorizer used for feature extraction


📊 Dataset

The dataset contains SMS messages labeled as Spam or Ham.

Commonly used dataset: SMS Spam Collection Dataset (UCI Repository)
.

📈 Model Performance

Algorithm Used: Multinomial Naive Bayes

Evaluation Metrics: Accuracy, Precision, Recall, F1-Score

Achieved ~97% accuracy on test data

🛠️ Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, NLTK, Streamlit

Visualization: Matplotlib, Seaborn

