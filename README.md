# Blender_Neural_Network
Create an Artificial Neural Network Model in Blender

Blender Neural Network is an addon for Blender that creates a panel in the 3D view. With this panel you can create the model of ANN.
This is the panel generated by the file

<h2>The Panel has four sections</h2>

1. **<h3>Neuron Aspect</h3>**
   1. **Neurons Aspect Mesh** change the mesh of the neurons: 0 > Iconesphere, 1 > Sphere, 2 > Text, 3 > Square
   2. **Neuron Model Size** change the scale of the neurons.
   3. **Connections Visibility** Hide the connections
   4. **Connecitons Radius** change the thickness of the connections. 
2. **<h3>Neuron Model Size</h3>**
   1. Set the number of the neurons for each layer.
3. **<h3>Neuron Model Shape</h3>**
   1. Here it is possible to change the 'SHAPE' of the neurons (it is not connected with Numpy, it is just for aesthetic purpose). For instance, MNIST handwritten is a dataset of image 28 x 28, if you are reading an array with one dimension, you will have 28x28 = 784 pixels, and this case the size will be 784 and the shape 28.
4. **<h3>Training Data</h3>**
   1. this section is for training the model and still in development. At the moment you can add the path of the dataset and it will be read directly in Animation Nodes. In this case the the size input of the dataset will be the length of the columns.
