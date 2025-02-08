# 📖 Next Word Prediction with GRU & LSTM 🚀

## Overview

This application uses Gated Recurrent Unit (GRU) and Long Short-Term Memory (LSTM) models to predict the next word in a sequence from Shakespeare's Hamlet. Built with TensorFlow, Keras, and Streamlit, it leverages deep learning to generate context-aware predictions based on previous words. The interactive Streamlit UI allows users to input text and receive predictions, showcasing the power of LSTM and GRU models in natural language processing.



## 🔗 Links

- 🌐 **Live Demo:** [LLVE Demo](https://gru-rnn-next-word-prediction-z3yqw82qfxbf3wqeeruhhg.streamlit.app/)
- 📂 **GitHub Repo:** [GRU-RNN-Next-Word-Prediction](https://github.com/laavanjan/GRU-RNN-Next-Word-Prediction)

## ✨ Features

- 🔥 Implements both **GRU** and **LSTM** for next-word prediction.
- 📜 Uses **tokenization** and **sequence padding** for input processing.
- 🖥️ Provides an interactive **Streamlit** web app for predictions.
- ⏳ Trained with **early stopping** to optimize performance.

## 🛠️ Tech Stack

- 🐍 **Python 3.11**
- 🤖 **TensorFlow 2.28/Keras** for deep learning
- 🌐 **Streamlit** for UI
- 🗄️ **Pickle** for tokenizer storage
- 🔢 **NumPy,Pandas** for numerical computations



## 🏗️ Installation

Clone this repository:

```bash
 git clone https://github.com/laavanjan/GRU-RNN-Next-Word-Prediction
 cd GRU-RNN-Next-Word-Prediction
```

Create and activate a **Conda** virtual environment:

```bash
 conda create --name nextword_env python=3.11
 conda activate nextword_env
```

Install dependencies:

```bash
 pip install -r requirements.txt
```

## 🚀 How to Use

1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
2. Enter a sequence of words in the text box.
3. Click the "Predict Next Word" button to get the model's prediction.

## 📂 File Structure

```
📂 GRU-RNN-Next-Word-Prediction
├── app.py  # Streamlit app for predictions
├── next_word_lstm.h5  # Trained LSTM model
├── tokenizer.pickle  # Saved tokenizer
├── requirements.txt  # Dependencies
└── experiments.ipynb  # Jupyter notebook for training
```

## 🔮 Future Improvements

- 🔄 Add support for **bi-directional LSTMs**
- 📈 Train with **larger datasets** for better accuracy
- 🌍 Deploy the model as a **REST API**
- 📊 Include **visualizations and model performance metrics**

## 🖼️ Images



## 📜 License

This project is open-source under the **GPL License**.

