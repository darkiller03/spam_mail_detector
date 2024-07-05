# Spam Mail Detection

This project demonstrates the detection of spam emails using machine learning techniques. The notebook includes data preprocessing, feature extraction, model training, and prediction steps.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)

## Introduction
The objective of this project is to classify emails as spam or not spam using a Random Forest classifier. The process involves text preprocessing, feature extraction with CountVectorizer, and model training with a labeled dataset.

## Dataset
The dataset used in this project is a CSV file named `spam_dataset.csv` containing the following columns:
- `Unnamed: 0`: Index
- `label`: Label indicating if the email is spam or not
- `text`: The content of the email
- `label_num`: Numerical representation of the label (0 for non-spam, 1 for spam)

## Requirements
- Python 3.11.7
- Pandas
- NumPy
- NLTK
- scikit-learn

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/darkiller03/spam_mail_detect.git
