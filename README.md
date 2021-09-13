# CommonLit-Text-Readability-Prediction

This repository contains implementation of a kaggle competition (CommonLit Readability) for predicting ease of reading of given excerpt. The output was continuous and hence a regression problem where higher the value easier it is to read.

### Dataset:

- [CommonLit Readability - Kaggle](https://www.kaggle.com/c/commonlitreadabilityprize/data)

### Summary of Implementation:

- Explored the given dataset.
- Kept useful columns for prediction.
- Cleaned the input data using regex and tokenized it.
- Created Embedding matrix for input tokens using GloVe Word Embeddings.
- Tried few different RNN architectures and evaluated the performance of models based on RMSE value. The final model consisted of a LSTM layer with Fully Connected Dense layers.
- Used checkpoint for Early Stopping the training and analyzed the Learning curves.
- Achieved RMSE score of 0.73 on test data.

### Libraries Used:

- Numpy
- Pandas
- Tensorflow
- Keras
- Matplotlib

### Contributors:

- [Jaydeep](https://github.com/Jaydeep2401)
- [Aynaan](https://github.com/Aynaan)