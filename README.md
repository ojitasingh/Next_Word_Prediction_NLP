Next Word Prediction using LSTM

This project implements a basic Natural Language Processing (NLP) model to predict the next word(s) in a given input sentence using LSTM (Long Short-Term Memory) neural networks.

📌 Project Overview

* **Input**: A text file (`pizza.txt`) containing natural language sentences.
* **Output**: A sequence of predicted words based on a given seed phrase.
* **Model**: LSTM-based Sequential model using TensorFlow and Keras.

🧠 Features

* Text preprocessing with sentence tokenization and padding.
* N-gram sequence generation for supervised learning.
* One-hot encoding of output labels.
* Training a text generation model using Embedding + LSTM + Dense layers.
* Predicts next word(s) for a given seed text.

🚀 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Regex (for sentence splitting)

📂 File Structure

* `next_word_nlp.py`: Main Python script that reads text, processes data, trains the model, and generates predictions.
* `pizza.txt`: (Required) Text file containing training sentences.

🛠 How to Run

1. Ensure you have Python installed (preferably 3.7+).
2. Install required packages:


   pip install tensorflow numpy regex
  
3. Place your training data in `pizza.txt` in the same directory.
4. Run the script:


   python next_word_nlp.py
 

🔄 Sample Output

```
Seed text: "Pizza is very"
Predicted continuation: "Pizza is very delicious and cheesy to eat"
```

📈 Model Summary

* Embedding layer: Maps words to a 10-dimensional vector space.
* LSTM layer: Captures temporal dependencies in sequences.
* Dense layer: Outputs probability distribution over vocabulary.

📑 Notes

* Increase the training data and epochs for better results.
* Pretrained embeddings can improve model performance.
* Use a more advanced tokenizer (e.g., SpaCy) for real-world applications.

