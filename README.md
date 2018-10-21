# ec601-miniproject2

  This is the submission of ec601 miniproject2.
  
  
  The model is trained to be able to classify daisies and roses. To build our training set, I selected 726 images for each category and named them in the format of ''category' (num)'.As for testing set, 43 images of daisies and 57 for roses was stored in the same naming format respectively.
  
  To build the model, I used 2 convolutional layers and 1 maxpooling layer to extract the features and a softmax function was designed to show the probabilities of each category at the end of the model. To minimize the loss, for every epoch, I choosed to use sgd optimization method. After training the model for 30 epochs, model.evaluate method was utilized to evaluate the accuracy of our model.
  
  The accuracy of our model can reach 85 percent, which can indicate that it works desirably.
