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

🔧 Installation
To install the necessary libraries:
"pip install tensorflow pandas numpy scikit-learn" 

▶️ Running the Notebook
Open the Jupyter Notebook notebook/Quora_Spam_Model_.ipynb.

Run all the cells to train the model.

Ensure that the train.csv and glove.6B.100d.txt files are placed in the /data folder if you’re re-running the model.

After training, save the model to /model/quora_spam_model.h5.

📥 Using the Trained Model
You can load the trained model with Keras:
"from keras.models import load_model

model = load_model('model/quora_spam_model.h5')"


💡 Model Architecture
Embedding Layer: Pre-trained GloVe 100D word embeddings

LSTM Layer: 64 units with dropout for regularization

Dense Output Layer: Sigmoid activation for binary classification

The model is trained for 5 epochs using a batch size of 128 and binary crossentropy loss.

📈 Performance
Training Accuracy: ~95.6%

Validation Accuracy: 95.87%

Loss: 0.1064






