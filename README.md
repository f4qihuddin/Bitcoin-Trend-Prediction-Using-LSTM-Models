# What i do in this project?

Conducting predictive analytics on bitcoin time series data. Bitcoin is unpredictable, so it's hard to find clear pattern
in the data. However, it turns out that even data as unpredictable as bitcoin has a pattern if you decompose the data into it's 
own components. You'll see it has a seasonal pattern which is a pattern that is repeated after a certain period of time passed, 
furthermore, you'll see a trend which can tell you wheter the price will go up or go down in the near future.

# What model to use when the data is unpredictable?

A simple linear regression won't work. That's why LSTM which stands fo Long Short Term Memory exists. with LSTM, you can build
a predictive analytics model that not just predict 1 value in the future, but, a lot of values in the near future at once. In this, project
i built and compare the result of 2 LSTM models. First, is the usual LSTM model as a baseline and second is a Sequence to Sequence model.
