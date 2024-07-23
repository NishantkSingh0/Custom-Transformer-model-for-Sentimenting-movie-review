# About the Model
This repository contains a sentiment analysis model built from scratch using the Transformer architecture. The model is designed to classify movie reviews as either positive or negative. The dataset used for training and evaluation is the IMDb dataset, which consists of 25,000 highly polar movie reviews for training and 25,000 for testing.

# Implementation
The model leverages the Transformer architecture, which is known for its efficiency and scalability in handling sequential data.

![Screenshot (88)](https://github.com/NishantkSingh0/Custom-Transformer-model-for-Sentimenting-movie-review/assets/166206623/698a82ee-2bce-4868-b35c-8c7645e10d27)

The architecture is relatively complex due to the inclusion of multi-head attention and the need for extensive computations within the Transformer layer. However, this complexity allows the model to capture intricate patterns and relationships within the data, leading to improved performance.

# Performance: 
The model was trained on the IMDb dataset and evaluated without using any pretrained weights or models. Despite the complexity of the architecture and the challenge of training from scratch, the model achieved an impressive accuracy of 98% on the test set. This high level of accuracy demonstrates the effectiveness of the Transformer architecture in handling sentiment analysis tasks.

# Dataset preview:
## Review: 
Basically there's a family where a little boy (Jake) thinks there's a zombie in his closet & his par...
## Sentiment:
negative

# Training and Dataset
The model was trained using the IMDB dataset, which consists of movie reviews labeled as positive or negative sentiment. Each review is represented by a sequence of word indices, and in this implementation, the first 200 words of each review were used for training.

![Screenshot (87)](https://github.com/NishantkSingh0/Custom-Transformer-model-for-Sentimenting-movie-review/assets/166206623/f75ff0cf-e534-48bd-b3c0-1648269725f2)


# Conclusion
This project showcases the power of the Transformer architecture in a real-world application. By building the model from scratch and achieving high accuracy without relying on pretrained weights, this project highlights the potential of Transformers for various natural language processing tasks.
