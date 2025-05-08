# Quora Spam Detector 🛡️

This project builds a machine learning model using LSTM and GloVe embeddings to classify whether a Quora question is spam.

## 📁 Structure

- `notebook/Quora_Spam_Model_.ipynb`: Full training code
- `model/quora_spam_model.h5`: Trained model (95.87% accuracy)
- `data/`: (Optional) Put `train.csv` and `glove.6B.100d.txt` here if re-running

## 🧠 Model Details

- LSTM-based classifier
- Pre-trained GloVe word embeddings (100D)
- Accuracy on validation: **95.87%**

## 🚀 How to Run

1. Install the required libraries (TensorFlow, Pandas, etc.)
2. Open the notebook and run all cells
3. To use the model, load the `.h5` file with Keras




