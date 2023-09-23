This project is an implementation of a toxicity detection model using deep learning techniques. The model is designed to identify and classify toxic comments in text data. Toxicity in text can include hate speech, offensive language, and other harmful content.

Dataset was taken from kaggle. The model is stored in "toxicity.h5" it can be used in any machine with the following provided tensorflow has already been installed-
model = tf.keras.models.load_model('toxicity.h5')

The model is built using TensorFlow.
There are 5 phases in which the built was divided into-


1.Preprocessing:
tokenisation- each word maps to a number such that only deep learning model understands.

2.Building the model: Creating a sequential model
1st layer-embedding layer(knows in depth, analogy=personality of a word.)

3.Make predictions:Multiple comments as a batch passed together

4.Evaluation:binary classification metrics(accuracy, precision and recall scores)

5.Testing:
Custom input.

There were only three epochs cycles run in this project, this value can be increased for higher efficiency.

