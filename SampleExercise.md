Exercise corresponding to the course [Generative Deep Learning in Python](CourseOutline.md), *Lesson 2.1: Creating a Long Short Term Memory neural network for character prediction*.

# Specifying the model for character prediction

## Context

Now that you pre-processed the writings of the philosopher, you will create the neural network model. The model will later be used to predict the next character in the artificial generated text.

Remember that `maxlen` is a number specifying the length of the character sequences that you extracted, and that `chars_list` is a sorted list of the unique characters in the writings. Both are pre-loaded.

## Instructions

  * Create a `Sequential` model called `model`.
  * Add an `LSTM`layer with `128` units, and and `input_shape` equal to `(maxlen, len(chars_list))`.
  * Add a `Dense` output layer with the `softmax` activation function. How many units should it have?
  * Compile the model with the given `optimizer` and `categorical_crossentropy` as the loss function.

## Take Hint
  * The number of units in the output layer should be `len(chars_list)`. This is the number of unique characters in the philosopher's writings, and those are the characters that we want in our artificial text.

## Shown script

```python
import keras
from keras.layers import Dense, LSTM
from keras.models import Sequential
from keras.optimizers import RMSprop

# Specify the model
model = ___
model.___(___(___, input_shape = ___))
model.___(___(___, activation = ___))

# Compile the model
optimizer = RMSprop(lr = 0.01)
model.compile(optimizer = optimizer, loss = ___)
```

## Full solution

```python
import keras
from keras.layers import Dense, LSTM
from keras.models import Sequential
from keras.optimizers import RMSprop

# Specify the model
model = Sequential()
model.add(LSTM(128, input_shape = (maxlen, len(chars_list))))
model.add(Dense(len(chars_list), activation = 'softmax'))

# Compile the model
optimizer = RMSprop(lr = 0.01)
model.compile(optimizer = optimizer, loss = 'categorical_crossentropy')
```

## Motivational feedback message

## Tests

## Note
  * We can choose an actual philosopher and directly refer to him in the exercise. In the reference that I consulted, writings of Nietzsche are used.
