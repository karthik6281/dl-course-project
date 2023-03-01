
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


