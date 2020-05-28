# __Classification using Keras (Fashion MNIST)__

* __Dataset Used__: Fashion MNIST
* __Layers__: Flatten, Dense
* __Activation__: ReLU, Softmax
* __Loss__: SparseCategoricalCrossentropy
* __Metrics__: Accuracy
* __Optimizer__: Adam


## * Dataset  
### __Fashion MNIST__  
- This is a dataset of 60,000 28x28 grayscale images of 10 fashion categories, along with a test set of 10,000 images.  
[read more](https://keras.io/api/datasets/fashion_mnist/)  

## Layers  
### __Flatten__  
- Transforms the format of the images from a two-dimensional array to a one-dimensional array. Think of this layer as unstacking rows of pixels in the image and lining them up. This layer has no parameters to learn; it only reformats the data.  
[read more](https://keras.io/api/layers/reshaping_layers/flatten/)  

### __Dense__  
- These are densely connected, or fully connected, neural layers.  
[read more](https://keras.io/api/layers/core_layers/dense/)  

## Activation Functions
### __ReLU__  
- Applies the rectified linear unit activation function. With default values, this returns the standard ReLU activation: max(x, 0), the element-wise maximum of 0 and the input tensor.  
[read more](https://keras.io/api/layers/activations/)  

### __Softmax__  
- Softmax converts a real vector to a vector of categorical probabilities. The elements of the output vector are in range (0, 1) and sum to 1.  
[read more](https://keras.io/api/layers/activations/)

## Loss  
### __SparseCategoricalCrossentropy__  
- Computes the crossentropy loss between the labels and predictions.  
[read more](https://keras.io/api/losses/probabilistic_losses/#sparsecategoricalcrossentropy-class)

## Metrics  
### __Accuracy__  
Calculates how often predictions equals labels.  
[read more](https://keras.io/api/metrics/accuracy_metrics/#accuracy-class)

## Optimizer
### __Adam__  
Adam optimization is a stochastic gradient descent method that is based on adaptive estimation of first-order and second-order moments. 
[read more](https://keras.io/api/optimizers/adam/)
