# Sentiment Analysis

### Sentiment Analysis on Stanford Dataset

I have done sentiment analysis on Stanford Sentiment Dataset (https://nlp.stanford.edu/sentiment/treebank.html) 
•	Used pytreebank which is used for pre-processing the dataset
•	Used pre trained Glove embedding and Pytext
•	Used three data augmentation: Backtranslation(google translate), Random deletion, Random swap
•	Used two layer LSTM and dropout as regularization and Adam optimizer
•	Trained for 25 epochs

### Sentiment Analysis on IMDB Dataset

- Used ImDB dataset for sentiment analyzer
- packed padded sequences
- Words in sentences are reversed
- Used pre-trained word glove embeddings
- Used Spacy tokenizer
 - 3 layer LSTM is ued using for loop
 - Dropout as regularization
 - Adam optimizer
 - Use Batch size 64
- Got test accuracy of 87.61% and best validaation: 89.44%
- Trained for 25 Epochs
