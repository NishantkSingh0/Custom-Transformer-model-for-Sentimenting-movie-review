# About the Model
This repository contains an implementation of a Transformer Encoder Layer using TensorFlow and Keras for sentiment analysis. Sentiment analysis is the task of classifying the sentiment of a piece of text, in this case, movie reviews from the IMDB dataset, as either positive or negative.

# Implementation
The core component of this repository is the custom TransformerEncoderLayer built using TensorFlow's subclassing method. This layer is inspired by the Transformer architecture, which revolutionized natural language processing tasks. The TransformerEncoderLayer includes:

![Screenshot (88)](https://github.com/NishantkSingh0/Custom-Transformer-model-for-Sentimenting-movie-review/assets/166206623/698a82ee-2bce-4868-b35c-8c7645e10d27)


## Multi-Head Attention: 
Enables the model to weigh the importance of different words in context.
## Feed-Forward Neural Network: 
Processes information from attention layers to capture complex relationships.
## Layer Normalization: 
Stabilizes and accelerates training by normalizing the outputs of attention and feed-forward layers.
## Dropout:
Regularizes the model to prevent overfitting during training.

# Training and Dataset
The model was trained using the IMDB dataset, which consists of movie reviews labeled as positive or negative sentiment. Each review is represented by a sequence of word indices, and in this implementation, the first 200 words of each review were used for training.

![Screenshot (87)](https://github.com/NishantkSingh0/Custom-Transformer-model-for-Sentimenting-movie-review/assets/166206623/f75ff0cf-e534-48bd-b3c0-1648269725f2)


# Accuracy
The model achieved an accuracy of over 95% on the IMDB dataset, even when using basic numerical embeddings that do not capture semantic meaning. This high accuracy highlights the effectiveness of the Transformer Encoder Layer in capturing complex relationships in text data.
