# Emojify

## Abstract
With advances in AI and deep learning, much progress has been made in the field of computer vision and high accuracies have been achieved for classification tasks. This deep learning project essentially aims to use a convolutional neural network architecture to recognize facial expressions and will then display an emoji corresponding to the expression.

## Project
- We used the FER-2013 dataset to train our model that contained about 28709 training examples.
- The Keras API integrated with Tensorflow was used to classify the images into one of 7 categories(Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral).
- A total number of layers were 17 including Convolutional 2D layers, Dropout layers, Batch Normalization layers, MaxPool(2x2) layers and Dense layers.
- The ReLu activation function was used as the main activation function, and a softmax function was used for the final layer.
- The Adam optimizer was used along with the ‘Categorical Cross-Entropy’ loss function.

- To further improve accuracy, following techniques were used:

      a) Image data generation - preprocessing technique to augment image data

      b) Batch normalization - to reduce the risk of vanishing gradients

      c) Dropout - as a form of regularization

## Results

- The model achieved a validation accuracy of 63% which is good considering that the highest accuracy achieved for the same task in a Kaggle challenge is 68%.

## References

- [Facial Expression Recognition Challenge](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/notebooks)
- [FER2013 Dataset](https://datarepository.wolframcloud.com/resources/FER-2013)
