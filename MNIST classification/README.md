# MNIST Classification project

In this project I'm going to classify images coming from the MNIST dataset. It contains more than 60k images coming from the NIST database, they represent numbers in the range [0, 9] handwritten by students and workers. It's usually used in the machine learning field as training set for new classification systems on images.

<img src="https://github.com/dav7deRouge/Portfolio-projects/blob/main/MNIST%20classification/images/mnist-examples.png" alt="" width="300" height="300" />

## Libraries
For this project I used the following libraries:
* numpy;
* matplotlib for graphics
* tensorflow for the modelling part;
* sci-kit learn

After I downloaded the images from the *keras datasets*, I rescaled the pixels and built a simple shallow neural network in order to do a first try. Before even doing any kind of hyperparameter tuning I decided to create the model with 100 hidden nodes, *sigmoid function* as activation and *softmax* as output function in order to receive a probability for each predicted target (obviously the output layer has got 10 nodes).

The metric used to evaluate the performance of the model was the *accuracy*, the *loss function* chosen was the *cross-entropy*.
The model was trained for 25 epochs with a learning rate equal to 0.001; the training set contained 48k images while the validation set used contained 12k. The test set had 10k images instead.

The following picture shows how much *loss* and accuracy change during the 25 epochs training:

<img src="https://github.com/dav7deRouge/Portfolio-projects/blob/main/MNIST%20classification/images/mnist-training-graphs.png" alt="", width="300", height="300" />

After I trained the model, I evaluated it on the test set; it resulted to have a 97.5% of accuracy so I decided to not continue with more tests involving, for example, a better hyperparameter tuning.
