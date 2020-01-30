Generative Adversarial Networks comprise of a Generator(G) and a Discriminator(D). 

Generator(G) is a neural network that takes as input random noise and transforms it into a sample from the model distribution.

Discriminator(D) too is a neural network that distinguishes between output data(Fake) from the generator and training data samples(Real).

The model data is created by the Generator and training data is used as input to train the network. The overall network is trained such that Pmodel(data)~Ptraining(data).

Discriminator outputs the probability of a particular sample being real or fake (output from discriminator ranging from 0 to 1).




