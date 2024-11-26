# Skimlit: Text Summarization of Medical Abstracts

## 📜 Overview

Skimlit is a project designed to automate the process of summarizing medical abstracts using machine learning techniques. By analyzing the structure of medical research papers, this tool identifies and classifies essential sentences into categories such as background, objective, method, results, and conclusion, enabling faster comprehension of medical literature.

This project leverages the PubMed RCT dataset to train and evaluate a state-of-the-art deep learning model for extractive text summarization. It is particularly useful for researchers, healthcare professionals, and medical students navigating vast amounts of scientific data.

**Motive**
![image](https://github.com/user-attachments/assets/b1d05e7f-b1d3-438d-84d6-903015f4885f)


---

## ✨ Features

- **Dataset**: Uses the PubMed RCT dataset, a collection of medical abstracts with sentence classification.
- **Deep Learning Model**: Implements a Transformer-based architecture for text summarization.
- **Sentence Classification**: Automatically labels sentences into key categories (e.g., *Background*, *Methods*, *Results*).
- **Performance Metrics**: Evaluates using metrics like accuracy, F1 score, and loss trends during training.
- **Preprocessing**: Custom tokenization and input formatting for optimal model performance.

---

## 📂 Project Structure

```plaintext
Skimlit/
├── data/
│   ├── train.txt
│   ├── dev.txt
│   ├── test.txt
├── notebooks/
│   ├── Skimlit.ipynb  # Main Jupyter Notebook for training and evaluation
├── models/
│   ├── model_weights.pth  # Saved model weights
├── utils/
│   ├── data_preprocessing.py  # Functions for data cleaning and preparation
│   ├── metrics.py  # Evaluation metrics implementation
├── README.md  # Project documentation
```
---

## 🛠 Architecture
- Below is the Architecture  of the Tri-embedding model
![image](https://github.com/user-attachments/assets/372fde97-fae1-4796-946d-06171f0f8d99)
