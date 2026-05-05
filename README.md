# Neural Network SMS Text Classifier

This is the final project of the **Machine Learning with Python** certification from **freeCodeCamp**. The goal of this challenge is to create a machine learning model that classifies SMS messages as either "ham" (normal message) or "spam" (advertisement or unsolicited message).

## 🚀 Project Overview
In this project, I built a Recurrent Neural Network (RNN) using **Long Short-Term Memory (LSTM)** layers to process and classify text data. Natural Language Processing (NLP) techniques like tokenization and padding were used to prepare the dataset for the model.

### Key Implementation Details:
* **Data Preprocessing:** * Cleaned and labeled the SMS Spam Collection dataset.
    * Converted text messages into numerical sequences using a `Tokenizer`.
    * Applied `padding` to ensure uniform input length for the model.
* **Model Architecture:**
    * **Embedding Layer:** To represent words in a dense vector space.
    * **LSTM Layer:** To capture the sequential dependencies in the text.
    * **Dense Layers:** For classification with `ReLU` and `Sigmoid` activation functions.
* **Functionality:** Created a `predict_message` function that returns the probability of spam and the corresponding label.

## 🛠️ Technologies Used
* **Python**
* **TensorFlow & Keras** (Deep Learning)
* **Pandas** (Data Manipulation)
* **Numpy**
* **Natural Language Processing (NLP)**

## 📊 Results
The model successfully identifies spam messages with high accuracy, passing all the test cases provided in the freeCodeCamp challenge.

## 🔗 Project Link
You can view the complete code and implementation in my Google Colab notebook:
👉 [Google Colab Notebook](https://colab.research.google.com/drive/1q33hwRFMLXFlrITwsDxcRWPRpOUAgPPk?usp=sharing)

---
*Completed by Md. Anwar Hossen as part of the freeCodeCamp Machine Learning Curriculum.*
