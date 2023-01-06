# How representation learning works (in deep NN)

- it is an iterative process, during which you repeatedly feed sample input data

- and gradually adjust behaviour of all layers of neurons in neural network

- During training, each layer of neurons leans to transform its inputs into a different representation. eventually, we reach final layer, which learns to transform the last representation into good predictions.

- each layer in effect, learns to make the next layers's job a little easier.

- when we just want to learn representions instead of prediction, then we discard the prediction and just keep the representations that it learnt during the course of training.

- we slice off its last layer, we end up with a slightly shorter neural network, when fed input data, outputs an abstract representation of it.

- we could feed the representations as inputs to a second neural network for a different learning task.

- the second neural network would benefit from the representational knowledge learned by the first one assuming that the prediction objectives you specified to train the first neural network useful for the second one.