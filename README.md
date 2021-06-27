# Deep-Learning

Projects completed as part of the Udacity Deep Learning Nanodegree program. 

## List of projects

### 1. Predicting Bike-sharing Patterns 

Built a neural network which predicts daily bikesharing patterns. Predictions made are done using past data on the number of riders for each hour of each day from January 1 2011 to December 31 2012. The network built is a two layer network with a hidden layer and output layer. A sigmoid function is used for activations. The training goes through 1350 iterations, uses a learning rate of 0.55, has 3 hidden_nodes and 1 output node. 

Below shows a graph comparing the real data with the patterns predicted through the neural network: 

<img src="https://github.com/yunjia1/Deep-Learning/blob/main/file/bikesharing-%20predictions%20vs.%20real%20data.png" />

### 2. Landmark Classification & Tagging for Social Media

Wrote an algorithm for Landmark Classification. The project is composed of 4 parts. The algorithm was primarly written from scratch. 

1. Download Datasets and Install Python Modules
2. Create a CNN to Classify Landmarks (from Scratch)
3. Create a CNN to Classify Landmarks (using Transfer Learning)
4. Write Your Landmark Prediction Algorithm


### 3. Generate TV Scripts 

Makes use of LSTMS and TV Scripts from the Seinfeld dataset to generate new TV scripts. The model was ultimately able to generate the scripts with a loss of 3.43. Iterating through more epochs is likely to improve the accuracy of the model in generating realistic and feasible scripts. 

### 4. Generate Faces 

Makes use of a Deep Convolutional Generative Adversarial Network (DCGAN) on a training set of celebrity faces to generate fake faces. The project consists of data loading and pre-processing, creating the generator and discriminator classes, as well as training the network. After 50 epochs, fake faces are generated at the end of the file. 


## Credits 

Udacity, 2021
