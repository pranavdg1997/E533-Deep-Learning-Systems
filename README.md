# E533-Deep-Learning-Systems
## This repository contains solutions to amazing E533-Deep Learning Systems Course instructed by Prof. Minje Kim at Indiana University, Bloomington
### Assignment - 1
This assignment deals with using basic linear neural networks for Image classification and Sound denoising. The highlight  is demostrating how 98% accuracy can be gained on the MNIST model using only linear neural networks
### Assignment - 2
In this assignment we deep dive into using Convolutional Neural networks to denoise a noisy signal. We first frame the problem  in a non sequential way and use 1-D Convolutions followed by a sequential prediction exercise using 2D convolutions. 
### Assignment - 3
#### Problem - 1
Problem 1 deals with using SVD to compress our Neural Network model(used in Assignment-1) to get similar accuracy while saving on computation
#### Problem - 2
Problem 2 deals with removing noise from sound signals using LSTMs. The highlight here is, the lengths of the sound signals in the input vary quite a bit and padding them affects loss greatly as we to have the pad the output(clean signal) as well. Thus numerous (y=0,x=0) data points are present for the LSTM to figure out. 
### Assignment - 4
#### Problem - 1
Problem 1 deals with using Siamese networks for one shot speech detection. We have 500 sound signals(10 signals each for 50 unique speakers) and we need to identify which speaker each of the su=ignals in test data belong to. This can be achieved by using Siamese networks to to train a model which predicts if given two distinct sound signals, do they pbelong to the same speaker or not.
#### Problem - 2
This problem deals with creating latent vectors for image data. We create latent vectors for image data using variational autoencoders. We validate the excercise by observing how close to real images our decoder produces based on randomly initializes latent vectors. We then analyze which latent dimension nfluences rotation in an image.
