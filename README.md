# FashionMNIST_CNN_CIFAR10_DATA_Augment


FashionMNIST Dataset building CNN model :
Train a simple convnet on the Fashion MNIST dataset.In this, we will see how to deal with image data and train a convnet for image classification task.
** with 2 Conv layers having 32 3x3 filters in both convolutions with relu activations and flatten before passing the feature map into 2 fully connected layers (or Dense Layers) having 128 and 10 neurons with relu and softmax activations respectively. Now, using categorical_crossentropy loss with adam optimizer train the model with early stopping patience=5 and no.of epochs=10. **



DATA AUGMENTATION ON CIFAR10 DATASET
One of the best ways to improve the performance of a Deep Learning model is to add more data to the training set. Aside from gathering more instances from the wild that are representative of the distinction task, we want to develop a set of methods that enhance the data we already have. There are many ways to augment existing datasets and produce more robust models. In the image domain, these are done to utilize the full power of the convolutional neural network, which is able to capture translational invariance. This translational invariance is what makes image recognition such a difficult task in the first place. You want the dataset to be representative of the many different positions, angles, lightings, and miscellaneous distortions that are of interest to the vision task.
