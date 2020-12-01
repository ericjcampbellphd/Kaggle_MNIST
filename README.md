# Kaggle_MNIST

Tackles the <a href="https://www.kaggle.com/c/digit-recognizer/overview">Kaggle Digit Recognizer challenge</a> using the MNIST image dataset.

A standard neural network is constructed using the TensorFlow/Keras framework.

The model layers are as follows:
<ol><li>Input Layer</li>
<li>Dense layer using 784 Neurons and RELU activation</li>
<li>Dropout layer at 25%</li>
<li>Dense layer using 784 Neurons and RELU activation</li>
<li>Dropout layer at 25%</li>
<li>Dense layer using 784 Neurons and RELU activation</li>
<li>Dropout layer at 25%</li>
<li>Dense layer using 784 Neurons and RELU activation</li>
<li>Dense layer using 10 Neurons with Softmax layer</li>
</ol>

The model is compiled using an Adam optimizer, and trained using an Early Stopping and ReduceLROnPlateau Callback.

It acheived 96.982% on the Kaggle test set.
