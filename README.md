**NOTE: For users interested in multi-GPU, we recommend looking at the newer [cifar10_estimator](https://github.com/tensorflow/models/tree/master/tutorials/image/cifar10_estimator) example instead.**

---

CIFAR-10 is a common benchmark in machine learning for image recognition.

http://www.cs.toronto.edu/~kriz/cifar.html

Code in this directory demonstrates how to use TensorFlow to train and evaluate a convolutional neural network (CNN) on both CPU and GPU. We also demonstrate how to train a CNN over multiple GPUs.

Detailed instructions on how to get started available at:

http://tensorflow.org/tutorials/deep_cnn/

changed in cifar1.py
local3 and local4 from fully-connected to locally-connected

output is changed to probability using tf.nn.softmax
