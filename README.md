# SMS_spam_detection

This repository contains the code and data for building and evaluating an SMS spam detection model using machine learning. The goal of this project is to classify SMS messages as either spam or ham (non-spam).

Table of Contents
Introduction
Dataset
Installation
Usage
Model
Evaluation
Contributing
License
Introduction

SMS spam detection is a common problem in natural language processing (NLP). The aim is to automatically identify and filter out unwanted spam messages. This project demonstrates how to use machine learning techniques to build a spam detection model.

Dataset
The dataset used in this project is the SMS Spam Collection Dataset from the UCI Machine Learning Repository. It contains 5,574 SMS messages labeled as ham (legitimate) or spam.

Installation
To run this project locally, you need to have Python installed. You can install the required dependencies using pip:

bash
Copy code
git clone https://github.com/yourusername/sms-spam-detection.git
cd sms-spam-detection
pip install -r requirements.txt
Usage
After installing the dependencies, you can run the main script to train and evaluate the model:

bash
Copy code
python main.py
You can also use the predict.py script to classify new messages:

bash
Copy code
python predict.py "Your message here"
Model
The model used in this project is a simple Naive Bayes classifier, which is suitable for text classification tasks. The main steps involved in building the model include:

Data preprocessing (tokenization, removing stop words, etc.)
Feature extraction (using TF-IDF vectorization)
Training the Naive Bayes classifier
Evaluating the model performance
Evaluation
The model is evaluated using metrics such as accuracy, precision, recall, and F1-score. The results are printed in the console after running main.py.

Contributing
Contributions are welcome! If you have any improvements or new ideas, feel free to fork the repository and submit a pull request. Please ensure your changes are well-documented and tested.

License
This project is licensed under the MIT License. See the LICENSE file for more details.
