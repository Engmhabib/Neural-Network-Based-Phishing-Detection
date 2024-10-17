# Neural Network-Based Phishing Detection

## Overview

This repository contains a project, that focuses on exploring how well neural networks, specifically Long Short-Term Memory (LSTM) and Bidirectional Encoder Representations from Transformers (BERT), can detect phishing attempts in emails. The project compares these advanced neural networks with traditional machine learning methods like logistic regression to assess their effectiveness in cybersecurity.

## Project Summary

Phishing attacks are a significant threat in the cybersecurity domain, targeting individuals and organizations by tricking them into revealing sensitive information. As phishing tactics evolve, traditional detection methods are becoming less effective. This project explores whether neural networks can offer a better solution for detecting phishing emails.

### Key Components:
1. **Data Source:** 
   - Kaggle's "Phishing Email Detection" dataset, containing 18,650 emails categorized as "Safe" or "Phishing."
   - [Dataset Link](https://www.kaggle.com/datasets/subhajournal/phishingemails)

2. **Models Used:**
   - **Long Short-Term Memory (LSTM):** A Recurrent Neural Network architecture designed to handle sequence data, particularly effective in text data processing.
   - **Bidirectional Encoder Representations from Transformers (BERT):** A state-of-the-art language model based on transformer architecture.
   - **Logistic Regression:** A simpler, traditional machine learning method used for baseline comparison.

3. **Evaluation Metrics:**
   - The models were evaluated based on accuracy, with the LSTM model achieving a validation accuracy of 96.15%, and the BERT and logistic regression models achieving slightly higher accuracy at 96.32%.

4. **Visual Analysis:**
   - Word clouds were generated to visualize common words in phishing and safe emails, providing insights into the language patterns used in each category.

## Methodology

The project followed these key steps:
1. **Data Preparation:** The dataset was balanced by downsampling, and text preprocessing steps were applied including tokenization, removal of stop words, vectorization, and sequence padding.
2. **Model Training:** LSTM, BERT, and logistic regression models were trained and validated using the prepared dataset.
3. **Performance Analysis:** The models' accuracy and loss were monitored over multiple epochs, with adjustments made as needed to optimize performance.
4. **Results & Conclusion:** The neural networks demonstrated high accuracy in phishing detection, though the marginal improvement over traditional methods suggests the need for further exploration in model selection based on specific organizational needs.

## Conclusion

The project highlights the potential of neural networks in enhancing phishing detection but also indicates that simpler machine learning models may still offer competitive performance depending on the application context. Continuous innovation in cybersecurity techniques remains essential as cyber threats evolve.


## How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/phishing-detection.git
