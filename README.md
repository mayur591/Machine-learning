# Machine-learning
We're using Keras to classify handwritten digits from the MNIST dataset.
We load the data, which consists of 60,000 training images and 10,000 test images, each 28x28 pixels.
We one-hot encode the label data.
You'll sketch the network's architecture and calculate its parameters.
Model.summary() provides insight into the model structure.
The network has 10 output neurons for classifying digits 0 to 9.
We use optimizers (e.g., SGD), loss functions (e.g., mean squared error), and metrics (e.g., accuracy) for training.
An epoch is a complete pass through the training data.
Batch size determines how many examples are used in each training iteration.
Training adjusts the model's parameters, while testing evaluates its performance.
Softmax function in the output layer converts scores to probabilities for multiclass classification.
