# Graduation-Project-2023
Proteins are flexible molecules, and their dynamics are intimately connected to their function
(Chu et al., 2013). Proteins always exist in a dynamic state and each state is called a
conformation, this conformation is a 3d structure which consists of X, Y, Z that represents the
position of the atom at a given time. Computational methods like molecular dynamics can be
used to define their conformational space in order to clarify the relationship between their
molecular structure and function in an organism. The paper that we replicate had tried a lot of
techniques to get all the states of the protein but only the molecular dynamics technique
maintained the high accuracy. However, the cost of running the MD simulation leads us to use
deep learning to predict those conformations instead of running the simulation for every single
protein which this project provides by replacing the MD simulation by a generative neural
network which will be trained on a protein coming from the simulation. Deep learning such as
autoencoder and variational autoencoder are types of neural network that attempts to first
compress and then decompress a multidimensional input, so that the difference between input
and output is minimized. As a whole, this study shows that neural networks may be used to
investigate the molecular conformational space.
