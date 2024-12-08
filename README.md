
# Sentiment Analysis of Tweets

This project demonstrates a step-by-step process for performing sentiment analysis on a dataset of tweets using a Recurrent Neural Network (RNN) and Word2Vec embeddings.

## Steps in the Project

1. **Import Data**: Load the dataset containing tweets labeled with sentiments (positive/negative).
2. **Preprocess Data**: Clean the tweets by removing URLs, special characters, and unnecessary symbols.
3. **Generate Word Embeddings**: Use Word2Vec to create embeddings that capture the semantic meaning of words.
4. **Build the Model**: Train an RNN model (e.g., LSTM) for sentiment classification.
5. **Evaluate and Save**: Test the model's performance and save it for future use.
6. **Predict New Data**: Use the trained model to predict sentiments of new tweets.

## How to Run the Code

### Prerequisites
- Python 3.7 or above
- Required libraries: 
  - `numpy`
  - `pandas`
  - `tensorflow`
  - `gensim`
  - `sklearn`

Install the dependencies using pip:
```bash
pip install numpy pandas tensorflow gensim scikit-learn
```

### Steps to Execute

1. Clone the repository or download the notebook file.
2. Place the dataset file (`training.1600000.processed.noemoticon.csv`) in the same directory as the notebook.
3. Open the Jupyter Notebook and run all cells sequentially:
   ```bash
   jupyter notebook Final_sentiment-analysis.ipynb
   ```
4. To use the model for new predictions, ensure the tweet input is preprocessed similarly to the training data.

### Notes
- The dataset must be in CSV format with the following columns:
  - `sentiment`, `ids`, `date`, `flag`, `user`, `tweet`
- Update the dataset path in the notebook if it's located in a different directory.

### Outputs
- The trained model will be saved as a file for future use.
- The predictions will display the sentiment of the input tweets.

### Future Work
- Experiment with more advanced architectures like transformers.
- Incorporate more complex features such as emojis or hashtags.

---

If you encounter any issues, feel free to raise them in the project discussion!
