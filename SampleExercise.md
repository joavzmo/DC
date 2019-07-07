
## Context

## Instructions

## Shown script

```python
import keras
from keras.layers import Dense, LSTM
from keras.models import Sequential
from keras.optimizers import RMSprop

model = Sequential()
model.add(LSTM(128, input_shape=(maxlen, len(chars))))
model.add(Dense(len(chars), activation='softmax'))

# 
optimizer = RMSprop(lr=0.01)
model.compile(loss='categorical_crossentropy', optimizer=optimizer)
```

## Full solution

```python
import keras
from keras.layers import Dense, LSTM
from keras.models import Sequential
from keras.optimizers import RMSprop

model = Sequential()
model.add(LSTM(128, input_shape=(maxlen, len(chars))))
model.add(Dense(len(chars), activation='softmax'))

# 
optimizer = RMSprop(lr=0.01)
model.compile(loss='categorical_crossentropy', optimizer=optimizer)
```

## Motivational feedback message

## Tests and Hints
