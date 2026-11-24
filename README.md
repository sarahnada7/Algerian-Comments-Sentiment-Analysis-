# 🌿 Algerian Daridja Sentiment Analysis

## 📌 Project Overview

This project focuses on **sentiment analysis of Algerian Daridja**, using Deep Learning to classify comments into positive, negative, and neutral sentiments.

It uses a **Bidirectional LSTM (Bi-LSTM)** model trained on two Algerian dialect datasets, each with its own classification system.

## 🧠 Methodology

- **Dataset Preparation:** Load and explore two datasets (DarijaDZ_SA and Zenodo).
- **Text Preprocessing:** Clean comments, normalize Arabic characters, remove noise, and handle Arabizi.
- **Model Development:** Build and train a Bidirectional LSTM using TensorFlow/Keras.
- **Evaluation:** Measure performance using accuracy, classification reports, confusion matrices, and learning curves.
- **Model Saving:** Save trained models, vocabularies, and configurations for reuse.

## 🖥️ User Interface

The project includes an interactive **Gradio web interface** where users can:
- Enter comments in Algerian Daridja (Arabic script, Arabizi, or mixed French).
- Choose between the two classification systems.
- Get real-time sentiment predictions.
- View confidence scores for each sentiment class.

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Bidirectional LSTM
- Scikit-learn
- Pandas & NumPy
- Matplotlib & Seaborn
- Gradio

## 🚀 Getting Started

The notebook is designed to run on Google Colab.

1. Open the notebook in Google Colab.
2. Enable GPU acceleration (recommended).
3. Run all cells sequentially.
4. Launch the Gradio interface and access the generated public link.

## 🎯 Objective

To explore the use of Deep Learning and Natural Language Processing (NLP) for understanding sentiment in Algerian Daridja and provide an accessible tool for automatic sentiment classification.
