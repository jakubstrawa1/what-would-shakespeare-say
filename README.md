# What would shakespeare say?
This is a fully functional AI model predicting what William Shakespeare would say based on his sonnets.
    
This model was built with an Embedding layer, a bidirectional LSTM layer and another LSTM layer but this time only one-directional. 
To avoid overfitting i went with a dropout layer inbetween both lstms. 
