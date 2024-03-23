# TextClassification
 I will introduce you to a text classification model with TensorFlow on movie reviews as positive or negative using the text of the reviews. This is a binary classification problem, which is an important and widely applicable type of machine learning problem.

I’ll walk you through the basic application of transfer learning with TensorFlow Hub and Keras. I will be using the IMDB dataset which contains the text of 50,000 movie reviews from the internet movie database. These are divided into 25,000 assessments for training and 25,000 assessments for testing. The training and test sets are balanced in a way that they contain an equal number of positive and negative reviews.
TensorFlow Text provides a collection of text related classes and ops ready to use with TensorFlow 2.0. The library can perform the preprocessing regularly required by text-based models, and includes other features useful for sequence modeling not provided by core TensorFlow.

The benefit of using these ops in your text preprocessing is that they are done in the TensorFlow graph. You do not need to worry about tokenization in training being different than the tokenization at inference, or managing preprocessing scripts.
