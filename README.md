# Emotion Classification

This project explores emotion classification using the GoEmotions dataset by implementing and comparing various machine learning and deep learning models. We fine-tune pre-trained Large Language Models (LLMs), such as BERT and GPT-2, using the Hugging Face Transformers library, optimizing the classification head for single-label emotion prediction.

Additionally, we implement a Naive Bayes classifier from scratch using a bag-of-words representation and benchmark its performance against a baseline model (Softmax Regression, Random Forest, or XGBoost).

## Methodology
- **Data Preprocessing**: The dataset is filtered to retain only single-label samples, reducing complexity while preserving approximately 85% of the original data.
- **Model Implementation**:
  - Fine-tuned and pre-trained LLMs (BERT, GPT-2)
  - Naive Bayes classifier
  - Baseline models (Softmax Regression, Random Forest, or XGBoost)
- **Evaluation**:
  - Classification performance is compared across models.
  - Attention matrices from transformer models are analyzed to interpret predictions, including both correct and incorrect classifications.

## Insights & Findings
This project provides a comparative evaluation of modern deep learning models and traditional machine learning techniques, highlighting their respective strengths and limitations in emotion classification.
