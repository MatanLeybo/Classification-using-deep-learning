# Classification-using-deep-learning
Using Cats vs Dog DB for Classification by using CNN and optimizing accuracy with different method.
In this project, I was able to achieve a classifier accuracy of 94.64% without using pre-existing models.

By building an appropriate neural network (with convolutional and max pooling layers) suitable for image classification, and using techniques 
to optimize the training process:
data normalization
Improving the CNN with BatchNormalization layer and Dropouts ass needed when there is an indication of overfitting
Data Augmentation to artificially expand the amount of data
Testing hyper parameters and finding the ones which yield the best results 
Using the regularization ReduceLROnPlateau 

The method: monitoring and checking the accuracy and the cost functions of the validation and the test sets,
we want to manipulation the prooccess using the tools above, the graphs behave:
Making them more and more consolidated and until they reach the lowest possible point where we reach a good amunnot of loss
I'll mantion that for that kind of leaeeningg the graphes are more noisy by nature,  a stochistic grdiant diesnt is very noisy
we prefer to use the adam ooptimazer for less noise and faster Convergence due to the adaptivee Convergence and the momentum coomponnent 

Also trying to make the grapths with less spikes foor - to get more accurate result, so smothing it is an option. 
a good modle will look like this:


![image](https://github.com/user-attachments/assets/64b4be99-fffa-4234-8714-d38fc6926b19)

ה

