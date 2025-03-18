# IMDB Sentiment Analysis Using LSTM

## 📌 Project Overview
This is a project I developed that implements a **Long Short-Term Memory (LSTM) network** for **sentiment analysis**, classifying text as positive or negative. The dataset used contains 50,000 reviews from Movies on IMDB. The goal is to be able to classify these reviews as positive or negative.  LSTM was chosen as the model of choice because it is well-suited for sequential data like text, enabling the model to capture long-range dependencies and context within sentences.

## Features
- **Text Preprocessing**: Cleaning and tokenizing text for better model performance.
- **LSTM Model**: Captures sequential dependencies to improve sentiment classification.
- **Word Embeddings**: Converts text into numerical vectors for meaningful analysis.
- **Dropout Regularization**: Prevents overfitting for better generalization.
- **Efficient Training**: Uses Adam optimizer and binary cross-entropy loss for stability.

## 🔧 Tech Stack
- **Python**
- **TensorFlow/Keras** (for LSTM model)
- **NLTK & spaCy** (for text preprocessing)
- **NumPy & Pandas** (for data handling)
- **Matplotlib & Seaborn** (for visualization)

## 📂 Project Structure
```
├── data/                  # Dataset files
├── notebooks/             # Jupyter notebooks for experimentation
├── models/                # Trained models
├── src/                   # Source code
│   ├── preprocessing.py   # Text cleaning & tokenization
│   ├── model.py           # LSTM model architecture
│   ├── train.py           # Training script
│   ├── evaluate.py        # Model evaluation
│   ├── predict.py         # Sentiment prediction script
├── requirements.txt       # Required dependencies
├── README.md              # Project documentation
```

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sentiment-analysis-lstm.git
   cd sentiment-analysis-lstm
   ```
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Download and prepare the dataset (modify `IMDB Dataset.csv` if neccessary).


## 📊 Results
- Achieved **87% accuracy** on the test set.
- Model effectively captures **context and sentiment nuances** in text.
- Can be improved further with **pre-trained embeddings (e.g., GloVe, Word2Vec)** or **bidirectional LSTMs**.

## 📌 Future Improvements
- Fine-tune with **larger datasets** for better generalization.
- Integrate **pre-trained embeddings** to enhance text understanding.
- Deploy as a **REST API** or web app for real-world usage.

## 🤝 Contributing
Feel free to **fork this repository**, submit issues, or create pull requests. Contributions are welcome!

## 📝 License
This project is licensed under the **MIT License**.

 
