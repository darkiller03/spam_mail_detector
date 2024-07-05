#Spam Mail Detection

This project demonstrates the detection of spam emails using machine learning techniques. The notebook includes data preprocessing, feature extraction, model training, and prediction steps.
Table of Contents

    Introduction
    Dataset
    Requirements
    Installation
    Usage
    Project Structure
    Results
    Contributing
    License

Introduction

The objective of this project is to classify emails as spam or not spam using a Random Forest classifier. The process involves text preprocessing, feature extraction with CountVectorizer, and model training with a labeled dataset.
Dataset

The dataset used in this project is a CSV file named spam_dataset.csv containing the following columns:

    Unnamed: 0: Index
    label: Label indicating if the email is spam or not
    text: The content of the email
    label_num: Numerical representation of the label (0 for non-spam, 1 for spam)

Requirements

    Python 3.11.7
    Pandas
    NumPy
    NLTK
    scikit-learn

Installation

    Clone the repository:

    bash

git clone https://github.com/darkiller03/spam_mail_detect.git

Navigate to the project directory:

bash

cd spam_mail_detect

Install the required libraries:

bash

    pip install pandas numpy nltk scikit-learn

Usage

    Download the spam_dataset.csv file and place it in the project directory.
    Open the spam_mail_detect.ipynb notebook and run all the cells to execute the entire process.
    To classify a new email, modify the email_toclassify variable with the email content and run the corresponding cells.

Project Structure

    spam_mail_detect.ipynb: The main Jupyter notebook containing the code for the project.
    spam_dataset.csv: The dataset file (not included in the repository, should be downloaded separately).

Results

The Random Forest classifier is trained on the provided dataset and can classify new emails as spam or not spam. The performance of the model can be evaluated by splitting the dataset into training and testing sets and calculating metrics such as accuracy, precision, recall, and F1-score.
Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.
