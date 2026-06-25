# Spam-SMS-Detection-CodSoft-Internship

## Overview

Spam SMS Detection is a Machine Learning project that classifies SMS messages as either **Spam** or **Ham (Legitimate)**. The project uses Natural Language Processing (NLP) techniques to convert text messages into numerical features and applies a Multinomial Naive Bayes classifier for accurate prediction.

This project was developed as **Task 4** of the CODSOFT Machine Learning Internship.

## Repository

GitHub Repository:
https://github.com/piyushranjan07/Spam-SMS-Detection-CodSoft-Internship

## Features

* SMS message classification into Spam or Ham
* Text preprocessing and cleaning
* TF-IDF feature extraction
* Multinomial Naive Bayes classifier
* Model performance evaluation
* Confusion Matrix visualization
* Custom SMS prediction functionality

## Dataset

The dataset consists of SMS messages labeled as:

* **Ham** – Normal and legitimate messages
* **Spam** – Promotional, fraudulent, or unwanted messages

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Machine Learning Pipeline

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Label Encoding
5. Train-Test Split
6. TF-IDF Vectorization
7. Model Training using Multinomial Naive Bayes
8. Performance Evaluation
9. Custom Message Prediction

## Project Structure

```text
Spam-SMS-Detection-CodSoft-Internship/
│
├── SMS dataset.zip
├── spam_sms_detection.ipynb
├── README.md
├── requirements.txt
│
└── screenshots/
```

## Installation

Clone the repository:

```bash
git clone https://github.com/piyushranjan07/Spam-SMS-Detection-CodSoft-Internship.git
```

Navigate to the project directory:

```bash
cd Spam-SMS-Detection-CodSoft-Internship
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Required Libraries

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

## Model Used

### Multinomial Naive Bayes

Multinomial Naive Bayes is one of the most effective algorithms for text classification tasks. It performs well on high-dimensional text data and is widely used in spam filtering applications.

## Evaluation Metrics

The model is evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Classification Report
* Confusion Matrix

## Results

The trained model successfully classifies SMS messages as Spam or Ham with high accuracy. TF-IDF vectorization combined with Multinomial Naive Bayes provides an efficient and reliable solution for SMS spam detection.

## Sample Predictions

### Example 1

Input:

```text
Congratulations! You have won a free iPhone. Click here now.
```

Prediction:

```text
SPAM
```

### Example 2

Input:

```text
Hey, are we still meeting at 5 PM today?
```

Prediction:

```text
HAM
```

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload the SMS dataset.
3. Run all cells sequentially.
4. Train the model.
5. Evaluate performance using the provided metrics.
6. Test custom SMS messages using the prediction function.

## Future Enhancements

* Implement Support Vector Machine (SVM) for comparison
* Use advanced NLP techniques such as Word Embeddings
* Deploy the model using Streamlit or Flask
* Build a real-time SMS filtering application

## Internship Information

**Organization:** CODSOFT
**Domain:** Machine Learning
**Task:** Task 4 – Spam SMS Detection

## Author

**Piyush Ranjan**

GitHub: https://github.com/piyushranjan07

## License

This project was created for educational and internship purposes as part of the CODSOFT Machine Learning Internship Program.

