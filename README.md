# Siamese-Network
Deep neural networks are the go to algorithm when it comes to image classification. This is partly because they can have arbitrarily large number of trainable parameters. However, this comes at a cost of requiring a large amount of data, which is sometimes not available.
But when large amount of data is not available then comes into picture is one shot learning. 
## In here we have implemented Siamese network.
The Siamese network consist of the two Similar Convolution neural network in that we pass the two images and the difference of  values from those convolution network are passed from into the dense layer this gives the score.
Now this denses layer gives the value whether the signature images that i have passed are similar or not.
