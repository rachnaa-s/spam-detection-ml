# 📩 Spam Detection using Machine Learning

A Machine Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques.

## 📌 Project Overview

Spam messages are unwanted messages that may contain advertisements, fraudulent offers, or suspicious links.

In this project, a machine learning model is trained to automatically identify whether an SMS message is **Spam** or **Ham**.

The project uses **TF-IDF** for text feature extraction and **Multinomial Naive Bayes** for classification.

## 🎯 Objectives

- Detect spam messages automatically.
- Preprocess and convert text data into numerical features.
- Train a machine learning classification model.
- Evaluate the model using standard ML evaluation metrics.
- Test the model on new, user-provided messages.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Natural Language Processing (NLP)

## 🤖 Machine Learning Model

### Multinomial Naive Bayes

Multinomial Naive Bayes is used because it is efficient for text classification problems and works well with word-based features.

### TF-IDF

TF-IDF (Term Frequency–Inverse Document Frequency) converts text messages into numerical feature vectors that can be processed by the machine learning model.

## 📊 Dataset

The project uses the **SMS Spam Collection Dataset**, containing SMS messages labelled as:

- **Ham** – Legitimate/normal message
- **Spam** – Unwanted or suspicious message

The dataset is divided into:

- **80% Training Data**
- **20% Testing Data**

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Preprocessing
   ↓
Label Encoding
   ↓
Train-Test Split
   ↓
TF-IDF Feature Extraction
   ↓
Multinomial Naive Bayes
   ↓
Prediction
   ↓
Model Evaluation
```

## 📈 Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 🧪 Example Predictions

```text
"Congratulations! You have won a free iPhone. Click now to claim your prize!"
→ SPAM

"Hey, are we meeting at 5 pm today?"
→ HAM
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/spam-detection-ml.git
```

### 2. Open the notebook

Open:

```text
Spam_Detection_ML_Lab.ipynb
```

in **Google Colab** or Jupyter Notebook.

### 3. Run the cells

Execute the cells sequentially to:

1. Download the dataset
2. Load and preprocess the data
3. Extract TF-IDF features
4. Train the Naive Bayes model
5. Evaluate the model
6. Test custom messages


## 🔮 Future Improvements

- Build a web interface for real-time spam detection.
- Try other classification algorithms such as Logistic Regression and SVM.
- Improve text preprocessing using advanced NLP techniques.
- Add probability/confidence scores for predictions.
- Deploy the model as a web application.
