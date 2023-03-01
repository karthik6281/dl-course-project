# perceptron.ipynb

Implementing perceptron algorithm for classifying a linearly separable dataset in 2D.

The code contains a function which create random points around a line .

The plotting is done for different levels of separabality.

**Observation** : The number of iterations required to perfectly classify the data decreases with increase the level of separability(gamma)

# mini_batch_gradientdescent.ipynb

Gradient descent for training a linear classifier

The code contains a function which create random points around a line .

**Hinge Loss** is used

**Batch Size of 64**

Plot the linear classifier after tesing .

# MLP_one_hidden_layer.ipynb

A binary classification dataset that is **not linearly separable** in 2D

a **Multi layer perceptron (MLP) with a single hidden
layer** for classifying

**Cross Entropy Loss** is used

**Backpropapagation**

**Stochastic Gradient Descent** is used

Finally accuracy checking on testing data.

# convolution_and_pooling_functions.ipynb

**Convolution function:** It accepts an image input, a filter kernel, stride, padding and the non-linear function.

The function convolves the input image (after padding if specified) with the
kernel (at the specified stride size) and generate an output activation after applying the specified
non-linearity.

The plotting is done for different levels of separabality.

**Pooling function** : It accepts as input the activation map output from the convolution function,a pooling function, and stride.

The function outputs the appropriately pooled activation map.

# convolution_layer_and_pooling_layer_functions.ipynb

**Convolution layer function:** It accepts as input a volume (image or activation maps), number of filters, kernel dimensions, stride, padding and the non-linear function.

The function convolves the input volume (after padding if specified) with each of the kernels (at the specified stride size) and generates an output activation volume after applying the specified non-linearity.

**Pooling layer function:** It accepts as input the activation map volume, the pooling function,stride, and generates a pooled output volume.

**Global Average Pooling** is provided.


