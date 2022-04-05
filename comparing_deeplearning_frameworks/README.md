# Jackson, Curry

# Overview
The end product of my work for in this folder is to create a guide that new users would find helpful when deciding which deep learning framework to use (Tensorflow vs PyTorch vs scikitlearn) for their specific purpose.

## ComparingFrameworks.ipynb
Throughout this report I exclusively use the cifar10 dataset.  I first do a general exploration of the dataset with several visualizations that allow me to gain more insight into the dataset.  Next I implement general classification models for this dataset using each of the 3 frameworks (tensorflow/keras, scikit-learn, and pytorch).  
-I make a convolutional neural network model in tensorflow and I find that using keras it is pretty straight forward to implement a model that yields validation accuracy around 70% which is very good!  
-Then I use the MLPClassification module in scikit-learn to create a neural network model for this same dataset.  I find that this library is very high level and makes it hard/restrictive to do some of the more specific convolutions that I might want to do in the future which is bad.  Also this model was only able to have an accuracy of 40% which is still better than the 10% we would expect from random guessing but isn't great. 
Finally I follow along with a tutorial for the pytorch implementation of a CNN.  By doing this I see that this is a much lower level framework which is good because it allows for more flexibility.  However I feel that it most likely requires much more user knowledge and time to implement basic things which can be a drawback.  I also saw that the people doing this tutorial were able to get a model with 56% accuracy which makes it better than scikit-learn for this application and worse than tensorflow for this specific dataset.

# Conclusions and Ultimate Framework Decision for my Purposes
Overall taking into account the pros and cons of these different frameworks I feel that I plan to spend more time this semester learning tensorflow/keras.  I feel that this framework is correct for me because keras allows for quicker high level development of implementations, while the full tensorflow library allows me to have more flexibility if I am really trying to dive deeply into a dataset/model. Also from doing some research I learned that the performance of this library is generally close to that of pytorch meaning that it can develop really complex and high performing models!
