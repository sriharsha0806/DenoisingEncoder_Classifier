# Denoising Encoder_Classifier
Implemented a CNN denoising autoencoder in which the input is a noisy number and the output is a denoised number
using MNIST dataset. Used Gaussian distribution to add noise to the input. 

Built a classifier based on the trained Auto encoder. Extracted the trained encoder and fine tuned only the fully connected layer to classify the digits (the input is a noisy number)

