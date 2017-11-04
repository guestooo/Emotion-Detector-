## Emotion Detector
Deep learning text analyzing engine for web services and video games.  
(Only Russian language for now)  
You could test it [here](https://guestooo.github.io/Emotion-Detector-/run_model.html)
  
  
#### Model structure
![model structure](model.png )
  
  
Trained on **257** sentences and tested on **10** sentences with current accuracy **57.64%** (Where 0% is a pure random and 100% full match of data. Calculated from average of distances between actual and predicted vectors)

#### Instruments
Model implementation: [Keras](https://github.com/fchollet/keras)  
JS integration: [Keras.js](https://github.com/transcranial/keras-js)

