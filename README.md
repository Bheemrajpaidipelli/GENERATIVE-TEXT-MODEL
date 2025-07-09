# GENERATIVE-TEXT-MODEL
COMPANY : CODTECH IT SOLUTIONS NAME : PAIDIPELLI BHEEMRAJ ID : CT06DF373 DOMAIN : ARTIFICIAL INTELLIGENCE DURATION : 6 WEEKS MENTOR : NEELA SANTHOSH KUMAR

#  LSTM-Based Text Generation Model

This project implements a **character-level LSTM (Long Short-Term Memory)** neural network to generate text based on an English word dataset. The model learns character patterns from a corpus of English words and generates new text sequences from a given prompt.

---

##  Features

- Character-level LSTM text generator
- Dataset loaded dynamically from GitHub
- Simple Keras implementation with minimal dependencies
- Generates creative outputs based on a custom seed input

---

## 📂 Dataset

-  **Source:** [dwyl/english-words](https://github.com/dwyl/english-words)
-  **Type:** List of 370K+ English words
-  **URL Used:** `https://raw.githubusercontent.com/dwyl/english-words/master/words.txt`

This dataset is ideal for training character-level models to learn basic English spelling patterns and word forms.

---

##  Requirements

Install required libraries using pip:

```bash
pip install numpy tensorflow requests
