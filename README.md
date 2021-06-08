# Dynamic Backpropagation
 This is a Backpropagation implemented dynamically, meaning all the layers can be flexibly added/deleted/updated.

 - There is a Layer Class and a MyNeuralNetwork Class.
 - A Network can be initialised via inputting given arguements : number of layers, layer sizes, activation function for the network, learning rate, method to initialise weights, batch size
 - Methods to initialise weights include "random", "normal", "zero".
 - Activation functions that can be given as input include "tanh", "sigmoid", "linear", "relu".
 - In the last layer, softmax activation is automatically activated.
 - I used the MNIST dataset (a small counterpart provided by my institute IIIT-Delhi). The dataset is labeled as "train_set.pkl" and "test_set.pkl".

 After using different activation functions these are the scores that I recieved:

 (I as told to use [784, 256, 128, 64, 10] as layer sizes and learning rate as 0.1 with normal weight initialisations and epochs as 100, I used batch_size as 70)

 - sigmoid,   SCORE = 91%
 - relu,      SCORE = 94.7%
 - linear, learning_rate=0.002,      SCORE = 77.75%
 - tanh,      SCORE = 93.85%

 Furthur explainations are present in the notebook itself as comments.
 Predict proba, predict, score and TSNE plotting functionality also present.

 I am also attaching the Loss per Epoch graphs for all the above mentioned calculations:

 Sigmoid - 

 ![alt text](https://github.com/GaganMalik025/Dynamic-Backpropagation/blob/main/Graphs/Sigmoid.png?raw=true)

 ReLU -

 ![alt text](https://github.com/GaganMalik025/Dynamic-Backpropagation/blob/main/Graphs/ReLU.png?raw=true)

 Tanh - 

 ![alt text](https://github.com/GaganMalik025/Dynamic-Backpropagation/blob/main/Graphs/Tanh.png?raw=true)

 Linear -

 ![alt text](https://github.com/GaganMalik025/Dynamic-Backpropagation/blob/main/Graphs/Linear.png?raw=true)



