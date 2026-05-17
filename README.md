# part-3-nlp-sequence-modeling
# NLP and Sequence Modeling Mini Project

## Objective
Build an NLP pipeline to classify customer support messages into sentiment categories.

Target Labels:
- positive
- neutral
- negative

---

# Dataset Overview

Dataset:
customer_support_text_classification.csv

Important Columns:
- customer_message
- sentiment_label
- channel
- urgent_flag

---

# Tasks Covered

- Dataset exploration
- Text preprocessing
- TF-IDF vectorization
- Baseline NLP model
- Sequence model architecture
- Attention and transformer reflection

---

# Technologies Used

- Python
- Pandas
- Scikit-learn
- TensorFlow/Keras
- NLTK

---

# Sequence Model Explanation

## Input Sequence
Text is converted into sequences of integers using tokenization.

## Embedding Layer
Transforms words into dense numerical vectors.

## LSTM Layer
Learns sequential dependencies and contextual meaning.

## Output Layer
Predicts sentiment category.

## Loss Function
Categorical Crossentropy

## Evaluation Metric
Accuracy

---

# Attention and Transformers

## Why RNNs struggle
RNNs forget earlier information in long sequences because gradients vanish over time.

## How LSTMs help
LSTMs use memory cells and gates to preserve long-term dependencies.

## What attention solves
Attention helps models focus on important words in a sequence.

## Why transformers matter
Transformers process sequences in parallel and power modern AI systems like ChatGPT and BERT.

---

# Dataset Source

Provided in project shared drive.
