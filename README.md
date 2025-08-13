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

Install dependencies with:
```bash
pip install tensorflow scikit-learn numpy
