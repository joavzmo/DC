**_Note_**: *the track is composed of six existing courses (1, 2, 3, 4, 7, 8) and two newly proposed courses (5, 6). See [TaskAnalysis.md](TaskAnalysis.md) for the rationale behind it. **For the existing courses, the marketing description is copied from the course website and shown here between quotes**. The prerequisites are not modified. The learning objectives, however, are created based on the course contents.*

# Skill Track: Deep Learning in Python

Deep learning is having a tremendous success in artificial intelligence, from speech recognition to drug design. Learn its fundamental concepts and start building deep neural networks with state-of-the-art Python libraries.

## 1 - [Deep Learning in Python](https://www.datacamp.com/courses/deep-learning-in-python)

**_Note_**: *to avoid giving the same name to the track and one of its courses, this title could be changed to **Introduction to Deep Learning in Python**.*

**_Note_**: *this is also the last course of the Machine Learning with Python Skill Track, which I do not consider a problem. On the contrary, it provides a natural bridge between the two skill tracks.*

"Deep learning is the machine learning technique behind the most exciting capabilities in diverse areas like robotics, natural language processing, image recognition and artificial intelligence (including the famous AlphaGo). In this course, you'll gain hands-on, practical knowledge of how to use deep learning with Keras 2.0, the latest version of a cutting edge library for deep learning in Python."
  * Learning objectives
    * Learner will be able to understand the fundamental concepts and terminology used in deep learning. 
    * Learner will be able to create neural networks with the Specify-Compile-Fit-Optimize-Validate Keras workflow.
  * Prerequisites
    * [Introduction to Python](https://www.datacamp.com/courses/intro-to-python-for-data-science)
      * I would remove this prerequisite, because it is already a prerequisite of Intermediate Python for Data Science.
    * [Intermediate Python for Data Science](https://www.datacamp.com/courses/intermediate-python-for-data-science)
    * [Supervised Learning with scikit-learn](https://www.datacamp.com/courses/supervised-learning-with-scikit-learn)

## 2 - [Deep Learning with Keras in Python](https://www.datacamp.com/courses/deep-learning-with-keras-in-python)

**_Note_**: *This course has substantial overlap with 1 - [Deep Learning in Python](https://www.datacamp.com/courses/deep-learning-in-python), which, in my opinion, has much higher quality. I would discuss with my experienced colleagues or manager the possibility of dropping it from the track. But then, what is the reason to have this course in the platform at all? Not having it in the track would relegate it to a second plane. Having a deeper insight into DataCamp's growth strategy would help me make a more informed decission.*

"Deep learning is here to stay! It's the go-to technique to solve complex problems that arise with unstructured data and an incredible tool for innovation. Keras is one of the frameworks that make it easier to start developing deep learning models, and it's versatile enough to build industry-ready models in no time. In this course, you will learn regression and save the earth by predicting asteroid trajectories, apply binary classification to distinguish between real and fake dollar bills, use multiclass classification to decide who threw which dart at a dart board, learn to use neural networks to reconstruct noisy images and much more. Additionally, you will learn how to better control your models during training and how to tune them to boost their performance."

Live since June 28, 2019.

  * Learning objectives
    * Learner will be able to interpret more advanced neural network metrics and architectures.
    * Learner will be able to select more adequate parameters for building and validating a neural network.
  * Prerequisites
    * [Supervised Learning with scikit-learn](https://www.datacamp.com/courses/supervised-learning-with-scikit-learn)

## 3 - [Advanced Deep Learning with Keras in Python](https://www.datacamp.com/courses/advanced-deep-learning-with-keras-in-python)

"This course shows you how to solve a variety of problems using the versatile Keras functional API. You will start with simple, multi-layer dense networks (also known as multi-layer perceptrons), and continue on to more complicated architectures. The course will cover how to build models with multiple inputs and a single output, as well as how to share weights between layers in a model. We will also cover advanced topics such as category embeddings and multiple-output networks. If you've ever wanted to train a network that does both classification and regression, then this course is for you!"

  * Learning objectives
    * Learner will be able to design deep neural networks with complex data flows, using Embedding, Flatten, Input, Concatenate, Add from Keras.
    * Learner will be able to create deep neural networks that solve regression and classification models simultaneously.
  * Prerequisites
    * [Deep Learning in Python](https://www.datacamp.com/courses/deep-learning-in-python)

## 4 - [Convolutional Neural Networks for Image Processing](https://www.datacamp.com/courses/convolutional-neural-networks-for-image-processing)

**_Note_**: *For consistency, I would add "in Python" to the title, unless it becomes too long for your standards.*

"Deep learning methods use data to train neural network algorithms to do a variety of machine learning tasks, such as classification of different classes of objects. Convolutional neural networks are deep learning algorithms that are particularly powerful for analysis of images. This course will teach you how to construct, train and evaluate convolutional neural networks. You will also learn how to improve their ability to learn from data, and how to interpret the results of the training."

  * Learning objectives
    * Learner will be able to understand how images are processed in a deep neural network.
    * Learner will be able to use convolution layers and max pooling in deep neural networks.
    * Learner will be able to use regularization methods in convolutional neural networks.
  * Prerequisites
    * [Deep Learning in Python](https://www.datacamp.com/courses/deep-learning-in-python)
  
## 5 - Recurrent Neural Networks for Sequence Processing in Python (new)

**_Note_**: *The course **_Recurrent Neural Networks for Language Modeling in Python by David Cecchini_**, currently in development, could be well suited here. I would like to check its contents in detail. According to [DataCamp's roadmap](https://trello.com/b/BLplifUB/datacamp-course-roadmap), the expected live date is September 26, 2019.*

Deep learning methods for sequence processing are showing outstanding potential in tasks such as automatic translation, timeseries forecasting, sentiment analysis or document classification. Recurrent neural networks are one of the main techniques to analyze sequential data where order matters, such as text or timeseries. They mimick the way humans read a book: processing the input word by word and keeping the storyline in mind. You will understand the main difference with other neural network approaches and will be able to predict tomorrow's temperature using a real dataset.
  * Learning objectives
    * Learner will be able to understand the main concepts regarding recurrent neural networks (RNNs), including Long Short Term Memory, Stacked RNNs and Bidirectional RNNs.
    * Learner will be able to create and use recurrent neural networks with Keras.
  * Prerequisites
    * [Deep Learning in Python](https://www.datacamp.com/courses/deep-learning-in-python)
  
## 6 - Generative Deep Learning in Python (new, [check outline](CourseOutline.md))

Neural networks are already able to create original and meaningful cultural content, from Google's DeepDream psychedelic artwork to artifical electronic music. In this course your technical skills will develop to meet your inner artist. You will do the transition from *passive* prediction and classification tasks to *active* content generation with neural networks. Bring your creativity to the limit, generate captivating images and write your first artificial Treatise on Philosophy.

  * Learning objectives
    * Learner will be able to understand the potential and fundamental concepts of generative deep learning.
    * Learner will be able to use generative recurrent networks to create artificial text.
    * Learner will be able to create artifical images based on Google's DeepDream algorithm.
  * Prerequisites
    * Recurrent Neural Networks for Sequence Processing in Python
  
## 7 - [Deep Learning with PyTorch](https://www.datacamp.com/courses/deep-learning-with-pytorch)

**_Note_**: *This course has no slides available for download. I suggest that they are added to the platform.*

"Neural networks have been at the forefront of Artificial Intelligence research during the last few years, and have provided solutions to many difficult problems like image classification, language translation or Alpha Go. PyTorch is one of the leading deep learning frameworks, being at the same time both powerful and easy to use. In this course you will use PyTorch to first learn about the basic concepts of neural networks, before building your first neural network to predict digits from MNIST dataset. You will then learn about convolutional neural networks, and use them to build much more powerful models which give more accurate results. You will evaluate the results and use different techniques to improve them. Following the course, you will be able to delve deeper into neural networks and start your career in this fascinating field."

Live since June 24, 2019.

  * Learning objectives
    * Learner will be able to use PyTorch objects and methods to define deep neural networks.
    * Learner will be able to distinguish the features and uses of PyTorch and Keras.
    * Learner will be able to create convolutional neural networks with PyTorch.
  * Prerequisites
    * [Supervised Learning with scikit-learn](https://www.datacamp.com/courses/supervised-learning-with-scikit-learn)
    * [Object-Oriented Programming in Python](https://www.datacamp.com/courses/object-oriented-programming-in-python)

## 8 - [Introduction to TensorFlow in Python](https://www.datacamp.com/courses/introduction-to-tensorflow-in-python)

"Not long ago, cutting edge computer vision algorithms couldn’t differentiate between images of cats and dogs. Today, a skilled data scientist equipped with nothing more than a laptop can classify tens of thousands of objects with greater accuracy than the human eye. In this course, you will use TensorFlow 2.0 to develop, train, and make predictions with the models that have powered major advances in recommendation systems, image classification, and FinTech. You will learn both high-level APIs, which will enable you to design and train deep learning models in 15 lines of code; and low-level APIs, which will allow you to move beyond off-the-shelf routines. You will also learn to accurately predict house prices, credit card borrower defaults, and images of sign-language gestures."

  * Learning objectives
    * Learner will be able to understand tensors and tensor operations in TensorFlow.
    * Learner will be able to compare the implementation of deep neural networks with a low-level approach (TensorFlow) VS a high-level approach (Keras).
    * Learner will be able to use the Estimators API to streamline the model definition and training process and to avoid errors.
  * Prerequisites
    * [Supervised Learning with scikit-learn](https://www.datacamp.com/courses/supervised-learning-with-scikit-learn)
