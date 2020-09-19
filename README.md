# Face-detection-Using-FaceNet
This is a model of face detection using the weights of FaceNet that can be downloaded from https://drive.google.com/drive/folders/1ogd7fKXDy6Av3HBHk0l5-E9NOgAyDT-S?usp=sharing.

This is an implementation of transfer learning where we use weights pretrained on some other model and implement on our datset which is too small to train the neural network. Here I have used triplet loss function to calcualate the cost in training neural network. 

The images to be used must be of size 3X96X96 and then leads to an encoding of 128 elements. Here the primary agenda was to keep the encoding of two images of same person almost similar and that of two images of two different people to be entirely different.

This Ipython notebook has got two different functions one which is used to check whether the person is the same as he claims to be and the other function is working as a recognition system which means whether the person has got an identity in the database and if so then tells the name of the person.
Every step has been explained using the comments .
