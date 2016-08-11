# Terminology

## Inputs   
An input vector is the data given as one input to the algorithm. Written as x, with elements x <sub>i</sub> , where i runs from 1 to the number of input dimensions, m.

##Weights
 w<sub>ij</sub> are the weighted connections between nodes i and j. For neural networks these weights are analogous to the synapses in the brain. They are arranged into a matrix W.

## Outputs 
The output vector is y, with elements y<sub>j</sub>, where j runs from 1 to the number of output dimensions, n. We can write y(x, W) to remind ourselves that the output depends on the inputs to the algorithm and the current set of weights of the network.

## Targets  
The target vector t, with elements t<sub>j</sub>, where j runs from 1 to the number of output dimensions, n, are the extra data that we need for supervised learning, since they provide the ‘correct’ answers that the algorithm is learning about.

##Activation Function
 For neural networks, g(·) is a mathematical function that describes the firing of the neuron as a response to the weighted inputs, such as the threshold function. 

##Error E
 A function that computes the inaccuracies of the network as a function of the
outputs y and targets t.