# Generative Deep Learning in Python

## Chapter 1: Generative deep learning for text

### Lesson 1.1: Introducing generative deep learning

  * Learner will be able to name some of the recent applications of generative deep learning.
  * Learner will be able to understand the potential of generative deep learning.

### Lesson 1.2: Reweighting probability distributions with the softmax temperature

  * Learner will be able to distinguish between greedy and stochastic sampling.
  * Learner will be able to create a function that reweights a given probability distribution to control the degree of stochasticity.

### Lesson 1.3: Parsing the *philosopher* dataset

  * Learner will be able to understand the *philosopher* dataset, which contains many texts from {choose your favorite philosopher}.
  * Learner will be able to use *keras.utils.get_file* to load the dataset from the web.

### Lesson 1.4: Vectorizing sequences of characters

  * Learner will be able to prepare the training and target data to be used later in a later *model.fit*; this is achieved extracting partially overlapping sequences from the *philosopher* dataset, together with the characters that come after each sequence. 

## Chapter 2: Implementing a text generator with Keras

### Lesson 2.1: Creating a Long Short Term Memory neural network for character prediction

  * Learner will be able to create a neural network suited for character prediction; this is achieved compiling a neuran network with a Long Short Term Memory layer.

### Lesson 2.2: A sampling function based on model's predictions

  * Learner will be able to create a function that generates new characters based on the model's prediction and a given softmax temperature.

### Lesson 2.3: The artificial text generation loop

  * Learner will be able to create a loop of the previous function that generates a full text, inspired in the philosopher's style.

### Lesson 2.4: The effect of temperature on the generated text

  * Learner will be able to experiment with the effects of the softmax temperature in the artificial text.
  * Learner will be able to judge the potential of deep learning for text generation.

## Chapter 3: Generative deep learning for images

### Lesson 3.1: Visual art with generative deep learning 

  * Learner will be able to understand the potential of generative deep learning for visual art and artificial images.

### Lesson 3.2: DeepDream's Inception model

  * Learner will be able to create a DeepDream model with *from keras.applications import inception_v3*.
  * Learner will be able to choose a setup configuration for the DeepDream model.

### Lesson 3.3: Defining the loss measure

  * Learner will be able to understand why the loss measure needs to be *maximized*.
  * Learner will be able to construct a loss measure.

### Lesson 3.4: The gradient-ascent process

  * Learner will be able to understand why the gradient needs to *ascend*.
  * Learner will be able to construct the gradient-ascent process.

## Chapter 4: Implementing DeepDream with Keras

### Lesson 4.1: Some auxiliary functions

  * Learner will be able to understand the auxiliary functions that will be called to preprocess and postprocess the images.

### Lesson 4.2: Looping over scales

  * Learner will be able to create the main part of the DeepDream algorithm: a loop over different image scales, characterized by a size ratio between scales.

### Lesson 4.3: The effect of the size ratio between scales

  * Learner will be able to experiment with the effects of the ratio between scales in the generated images.

### Lesson 4.4: The future of generative deep learning

  * Learner will be able to discover the current trends in generative deep learning.
  * **_Note_**: *I like when courses end up with a short interview to a renowned speaker. Would it be interesting to invite [the guys that first developed DeepDream](https://ai.googleblog.com/2015/07/deepdream-code-example-for-visualizing.html)?*

# Notes

This outline is mainly based on:

  * François Chollet, "Chapter 8: Generative Deep Learning," in *Deep Learning with Python*, Manning Publications, 2018.
  
As project manager, I would work with the legal team and the course instructor to ensure that there are no copyright issues with the code and datasets employed.
