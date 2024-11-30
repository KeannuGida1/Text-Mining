# Hate Speech Multilabel Classification - Text Mining Project

## Overview  
This project aims to build a multilabel classification model for identifying hate speech on social media. Using pretrained Large Language Models (LLMs) such as IndoBERT, the model classifies texts into various hate speech categories, including Hate Speech (HS), Abusive Language, and subcategories such as HS_Individual, HS_Group, HS_Race, HS_Religion, and more.  

## Objectives  
1. Automate the detection of hate speech on social media to support efficient decision-making.  
2. Develop a robust model capable of handling multiple hate speech labels.  
3. Leverage advanced machine learning techniques for high-performance classification.  

---

## Steps Involved

### 1. Data Preprocessing  
- Cleaned text data by removing URLs, mentions, special characters, and unnecessary whitespace.  
- Tokenized and preprocessed text for compatibility with embedding models.  
- Applied stemming using Sastrawi and removed stopwords in Bahasa Indonesia.  
- Encoded labels for multilabel classification.

### 2. Model Selection and Training  
- Utilized pretrained IndoBERT for text embedding and multilabel classification.  
- Fine-tuned the model on a curated dataset with labeled hate speech data.  
- Tuned hyperparameters such as learning rate and batch size using grid search to optimize performance.  

### 3. Evaluation Metrics  
- Evaluated the model using the following metrics:  
  - **Accuracy**: Overall correct predictions.  
  - **Precision**: Relevance of predicted labels.  
  - **Recall**: Correct identification of actual labels.  
  - **F1-Score**: Balancing precision and recall.  
- Analyzed results on training, validation, and test datasets to assess generalization capabilities.  

---

## Results  
- **Training Data**: Demonstrated near-perfect performance with precision, recall, and F1-score of 1.00, indicating excellent classification capability.  
- **Validation Data**: Maintained high performance, showing robust generalization.  
- **Test Data**: Achieved consistent results, validating the model's reliability on unseen data.  

---

## Conclusion  
This project successfully developed a multilabel hate speech classification model using pretrained IndoBERT. The model demonstrates high accuracy and reliability, making it a valuable tool for identifying hate speech on social media.  
