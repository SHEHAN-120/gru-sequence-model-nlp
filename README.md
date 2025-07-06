# Next-Word Prediction Using GRU and Word Embeddings

This project demonstrates a language model for **next-word prediction** using TensorFlow and Keras, leveraging a GRU (Gated Recurrent Unit) instead of LSTM. It is trained on a small educational text corpus and uses tokenization, word embeddings, and a GRU layer to learn sequence patterns.

---

## 📒 Project Highlights

* Tokenization and sequence preparation using Keras Tokenizer
* Padding sequences to equal length
* Model architecture: Embedding → GRU → Dense (softmax)
* One-hot encoding of labels
* Predicting the next likely word based on a given phrase

---

## 🚀 Techniques Used

| Technique              | Purpose                                                |
| ---------------------- | ------------------------------------------------------ |
| Tokenization           | Convert text into integer sequences                    |
| Padding                | Standardize input sequence lengths                     |
| Embedding Layer        | Represent words as dense vectors                       |
| GRU                    | Capture sequence dependencies efficiently              |
| Softmax Classification | Predict the next word                                  |
| One-hot Encoding       | Prepare target variable for categorical classification |

---

## 💡 Technologies

* Python
* TensorFlow / Keras
* NumPy

---

## 📆 Dataset
Technology is changing the way we live and work. 
Every day, new devices and applications are introduced to make our lives easier. 
People use smartphones to communicate, search for information, and complete daily tasks. 
With the help of artificial intelligence, machines can now learn and make decisions. 
This transformation is creating new opportunities and challenges for society.


---

---

## 🎯 Results

* Predicts next likely word from short phrases
* Trained on small text corpus but scalable to larger datasets

---

## 🧠 Skills Gained

* NLP preprocessing (tokenization, padding, encoding)
* Building and training GRU models
* Understanding softmax-based word prediction
* Implementing and testing inference loops

