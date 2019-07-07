Exercise corresponding to the course [Generative Deep Learning in Python](CourseOutline.md), *Lesson 2.1: Creating a Long Short Term Memory neural network for character prediction*.

# Specifying the model for character prediction

## Context

Now that you pre-processed the writings of the philosopher, you will create the neural network model. The model will later be used to predict the next character in the artificial generated text.

Remember that `maxlen` is a number specifying the length of the character sequences that you extracted, and that `chars_list` is a sorted list of the unique characters in the writings. Both are pre-loaded.

## Instructions

## Shown script

```python
import keras
from keras.layers import Dense, LSTM
from keras.models import Sequential
from keras.optimizers import RMSprop

# Specify the model
model = Sequential()
model.add(LSTM(128, input_shape=(maxlen, len(char_list))))
model.add(Dense(len(chars), activation='softmax'))

# Compile the model
optimizer = RMSprop(lr=0.01)
model.compile(loss='categorical_crossentropy', optimizer=optimizer)
```

## Full solution

```python
import keras
from keras.layers import Dense, LSTM
from keras.models import Sequential
from keras.optimizers import RMSprop

# Specify the model
model = Sequential()
model.add(LSTM(128, input_shape=(maxlen, len(chars_list))))
model.add(Dense(len(chars), activation='softmax'))

# Compile the model
optimizer = RMSprop(lr=0.01)
model.compile(loss='categorical_crossentropy', optimizer=optimizer)
```

## Motivational feedback message

## Tests and Hints
