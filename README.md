# PrepoznavanjeZnamenki
Neural network that takes handwritten digits and reads them.

The project was made using Google Colaboratory. It allows you to import TensorFlow and use Google's graphic card to train the model.
The dataset has over 60 examples of each digit split into 2 groups(training and validation).
The project actually compares several algorithms with and without using dropout.
Tested algorithms: Adam, AdamMax, RMSprops and SGD.
The algorithm with the best results is AdamMax with dropout(all the algorithms performed better with dropout).
