# rnn-text-generation-tensorflow
Character-level text generation using Recurrent Neural Networks (RNN) built with TensorFlow and Keras. The model learns patterns from text and generates new text sequences.

# 📝 Character-Level Text Generation using RNN

A Deep Learning project that generates text character by character using a Recurrent Neural Network (RNN) built with TensorFlow and Keras.

The model is trained on a sample text corpus, learns character patterns, and generates new text based on a user-provided starting string.

---

## 🚀 Features

- Character-level text generation
- TensorFlow & Keras implementation
- Vocabulary creation and character encoding
- Sequence generation for training
- SimpleRNN architecture
- Model training and saving
- Text generation with temperature-based sampling
- Beginner-friendly deep learning project

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy

---

## 📂 Project Structure

```
rnn-text-generation-tensorflow/
│
├── main.py
├── rnn_text_generator.keras
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/rnn-text-generation-tensorflow.git
```

Move into the project folder:

```bash
cd rnn-text-generation-tensorflow
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python main.py
```

---

## 📖 Workflow

1. Load the training text
2. Create a character vocabulary
3. Encode characters as integers
4. Generate input-target sequences
5. Build a SimpleRNN model
6. Train the neural network
7. Save the trained model
8. Generate new text from a starting prompt

---

## 🧠 Model Architecture

- Embedding Layer
- SimpleRNN Layer (128 Units)
- Dense Output Layer
- Adam Optimizer
- Sparse Categorical Crossentropy Loss

---

## 📊 Sample Output

Input Prompt:

```
Artificial
```

Generated Text:

```
Artificial intelligence is transforming the world...
```

*(Output varies because text is generated probabilistically.)*

---

## 🚀 Future Improvements

- Replace SimpleRNN with LSTM
- Replace SimpleRNN with GRU
- Train on larger datasets
- Word-level text generation
- Beam Search decoding
- Attention mechanism
- Transformer-based language model
- Streamlit web interface
- Interactive text generation

---

## 📚 Learning Outcomes

- Recurrent Neural Networks (RNNs)
- Character-level language modeling
- Sequence preprocessing
- TensorFlow & Keras workflows
- Neural network training
- Temperature-based text sampling
- Deep Learning fundamentals

---

## 📄 License

This project is licensed under the MIT License.
