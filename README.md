
# SMS/Email Spam Classifier

This project is an **SMS/Email Spam Classifier** built using Natural Language Processing (NLP) techniques. The classifier can detect whether a given message (SMS or Email) is spam or not.

## Technologies Used

- **Python**
- **Streamlit** - for the web interface
- **scikit-learn** - for machine learning algorithms
- **NLTK** - for text preprocessing
- **Pickle** - for saving and loading models and vectorizers

## Setup Instructions

### 1. Clone the repository:

```bash
git clone https://github.com/Piyushkhandalkar/sms-Email-spam-detector.git
```

### 2. Install dependencies:

It is recommended to use a virtual environment. You can install all the required dependencies by running:

```bash
pip install -r requirements.txt
```

### 3. Run the application:

To run the Streamlit app locally, use the following command:

```bash
streamlit run p.py
```

### 4. Access the application:

Once the app starts, open your browser and go to the following URL:

```
http://localhost:8501
```

## Features

- **Spam Detection**: Input any SMS or Email message, and the model will predict whether it's spam or not.
- **Preprocessing**: The model tokenizes and processes the input message by removing stopwords, punctuation, and performing stemming.

## Model

The model uses a machine learning classifier trained on a dataset of spam and non-spam messages. The vectorizer used is **TF-IDF**.

### Files Included

- **p.py**: The main application code for running the Streamlit app.
- **vectorizer.pkl**: The pre-trained TF-IDF vectorizer used to transform the input message.
- **model.pkl**: The trained machine learning model that predicts if a message is spam or not.
- **requirements.txt**: List of Python dependencies required to run the project.
- **.gitignore**: Git ignore file to exclude unnecessary files from being tracked.
