# English–French Language Translator (LSTM Seq2Seq)

This project implements a **language translation application** using a **sequence-to-sequence (seq2seq) model** with LSTM layers in TensorFlow/Keras.  
The model translates **English sentences** into **French** and includes a **Tkinter GUI** for interactive use.

---

## 🚀 Features
- **Many-to-Many LSTM Encoder–Decoder Architecture**
- **One-Hot Encoding** for character-level training
- **Tkinter GUI** for real-time translation
- **Preprocessing pipeline** for input/output sequence handling
- **Model training & saving** for future use

---

## 📂 Project Structure
├── eng-french.txt # Dataset of English–French sentence pairs
├── langTraining.py # Script to train the LSTM model
├── LangTransGui.py # GUI application for translations
├── training_data.pkl # Pickled training metadata
├── s2s/ # Saved model files
└── README.md

---

## ⚙️ Requirements
- Python 3.8+
- TensorFlow 2.3+
- scikit-learn
- NumPy
- Pickle (built-in)
- Tkinter (built-in for most Python installations)
- 📊 Dataset

The dataset (eng-french.txt) contains English–French sentence pairs.

This project uses the first 10,000 pairs for faster training.

🛠 How to Run
1️⃣ Train the Model
python langTraining.py


This will:

Parse and preprocess the dataset

One-hot encode the sequences

Train the encoder–decoder LSTM model

Save the trained model and metadata

2️⃣ Launch the Translator GUI
python LangTransGui.py


📚 Learn More

This project is adapted from the DataFlair tutorial:
Language Translation using Machine Learning

📜 License

This code is for educational purposes only. Original tutorial by DataFlair.


Install dependencies with:
```bash
pip install tensorflow scikit-learn numpy

