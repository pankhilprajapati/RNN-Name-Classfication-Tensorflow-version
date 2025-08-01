# 🧠 Character-Level RNN Classification (TensorFlow Version)

This repository provides a TensorFlow 2.x implementation of the [PyTorch Char-RNN Classification Tutorial](https://pytorch.org/tutorials/intermediate/char_rnn_classification_tutorial.html). It trains a character-level RNN to classify names into their corresponding languages.

---

## 📌 Overview

- Classifies names like "Satoshi", "Schmidt", "O’Neill" into languages such as Japanese, German, Irish, etc.
- Each input is a name (as a sequence of characters), and the output is the predicted language.
- This is a direct port of the original PyTorch example into **TensorFlow 2.x using the Keras API**.

---

## 🗂️ Project Structure
├── CharRnn.ipynb  # Contains name notebook 

#📚 References
- 📘 [Original PyTorch Tutorial] (https://pytorch.org/tutorials/intermediate/char_rnn_classification_tutorial.html)
- 📘 [TensorFlow RNN Guide] (https://www.tensorflow.org/guide/keras/working_with_rnns)
