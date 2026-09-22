# AI-Customer-Support-Chatbot
AI Customer Support Chatbot using Machine Learning and NLP
# AI Customer Support Chatbot

## Project Overview

This project demonstrates an AI-based Customer Support Chatbot using Natural Language Processing (NLP) and Machine Learning.

The system classifies customer queries into predefined intents and helps identify what type of support the customer needs.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF
- Logistic Regression
- Google Colab
- GitHub

## Dataset

The dataset contains 24 customer support queries belonging to 6 different intents.

### Intents

- Customer Support
- Order Cancellation
- Order Tracking
- Password Reset
- Payment
- Refund

Each intent contains 4 sample queries.

## Data Preprocessing

The text data was cleaned before training the Machine Learning model.

The preprocessing steps included:

- Converting text to lowercase
- Removing unnecessary characters
- Removing extra spaces
- Preparing clean text for feature extraction

## TF-IDF Feature Extraction

TF-IDF (Term Frequency-Inverse Document Frequency) was used to convert the cleaned text into numerical features.

The final feature matrix contained:

- 24 samples
- 52 TF-IDF features

## Model

A Logistic Regression model was used for intent classification.

The dataset was divided into:

- Training samples: 18
- Testing samples: 6

## Model Evaluation

The model achieved:

**Test Accuracy: 66.67%**

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Example Predictions

The trained model was tested with new customer queries such as:

**Query:** Where can I track my order?

**Predicted Intent:** order_tracking

**Query:** I need to cancel my order

**Predicted Intent:** order_cancellation

## Saved Model Files

The following files were saved for future predictions:

- `chatbot_intent_model.pkl`
- `tfidf_vectorizer.pkl`
- `label_encoder.pkl`

## Practical Applications

This project can be used as a basic foundation for:

- Customer support chatbots
- E-commerce support systems
- Helpdesk automation
- Customer query classification
- FAQ automation

## Conclusion

This project demonstrates how NLP and Machine Learning can be used to automatically classify customer queries into different support categories.

The project provides a basic foundation for developing an automated customer support system.
