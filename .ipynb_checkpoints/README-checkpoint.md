# Birds-Recognizer-Ai

### Objective:

The goal of this project is to utilize neural networks to classify bird species with best accuracy possible.

### Requirements:

<ul>
<li>Tensorflow</li>
<li>Matplotlib</li>
</ul>

### Approach:

We will import the train, test, and valid folders containing the bird species we want to address with the model. We will look at a sample of what we have and build a Convolutional Neural network using Tensorflow to fit the model on the Training set and later test it on the test set and compare it with the validation set to analyze if overfitting took place.

<img src = "./assets/birds.PNG" alt = "birds species">

### Results:

<img src = "./assets/scores.PNG" alt = "scores">

We observe a training accuracy of ~99% while the validation accuracy is below 50% which suggests we have overfitting. Overfitting is a very common problem when using neural networks. Same issue is noticable with the loss function where we have a higher loss for the validation than the training set. This all allows us to safely assume we have an ovewrfitting issue which requires further enhancements to perfect.