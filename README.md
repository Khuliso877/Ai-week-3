# 🧠 AI Portfolio Projects by Khuliso

Part 1 and 3 on the week-3 folder

This repository showcases multiple machine learning and NLP projects built using Python, TensorFlow, spaCy, and Streamlit. Each project includes data preprocessing, model training, evaluation, and optional deployment.

---

## 📁 Projects Included

### 1. MNIST Digit Classifier (CNN)
- **Dataset**: MNIST Handwritten Digits
- **Goal**: Train a CNN to classify digits with >95% accuracy
- **Tools**: TensorFlow, Matplotlib
- **Deployment**: Streamlit app with drawing canvas
- **Features**:
  - Model architecture and training loop
  - Evaluation metrics: accuracy
  - Visualization of predictions
  - Web interface for digit input

### 2. Iris Species Classifier
- **Dataset**: Iris.csv
- **Goal**: Predict iris species using a decision tree
- **Tools**: scikit-learn, pandas
- **Features**:
  - Data preprocessing (missing values, label encoding)
  - Model training and evaluation (accuracy, precision, recall)
  - Clean, commented Jupyter notebook

### 3. Amazon Reviews NLP Analysis
- **Dataset**: Sample Amazon product reviews
- **Goal**: Extract named entities and analyze sentiment
- **Tools**: spaCy, rule-based sentiment logic
- **Features**:
  - Named Entity Recognition (NER) for brands/products
  - Rule-based sentiment classification (positive/negative)
  - Output visualization and interpretation

---

## 🧪 Ethical Considerations
- **Bias Detection**: MNIST may underrepresent diverse handwriting styles; Amazon reviews may reflect language or brand bias.
- **Mitigation Tools**: TensorFlow Fairness Indicators and spaCy’s rule-based overrides were explored to reduce bias.


## 📦 Installation
```bash
pip install -r requirements.txt
