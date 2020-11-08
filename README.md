# AutoEncoders
Autoencoders are self-supervising artificial neural network that by design,reduces data dimension by learning how to ignore the noise in the input data.

Autoencoders consists of 4 main parts:

1.Encoder - model compresses the input data and reduces the input dimensions 

2.Bottleneck - the layer of the model which contains the compressed part of the input data.

3.Decoded - model reconstructs the compressed data 

4.Reconstruction loss - model tries to minimize the loss and reconstruct the compressed data as close as to the input data.

This Reposistry consists the implementation of deep autoencoders and denoising autoencoders and their applications in real world.
