# ec601-miniproject2

  This is the submission of ec601 miniproject2.
  
  
  The model was trained to be able to classify daisies and roses. To build our training set, I selected 726 images for each category and named them in the format of ''category' (num)'. As for testing set, 43 images of daisies and 57 of roses were stored in the same naming format respectively. Then, I gave each image a label. '0' stands for daisies, while '1' stands for roses. At last, for the convenience of our training, I resized every image into 32*32 pixels.
  
  To build the model, I used 2 convolutional layers and 1 maxpooling layer to extract the features and a softmax function was designed to show the probabilities of each category at the end of the model. To minimize the loss, for every epoch, I choosed to use sgd optimization method. After training the model for 30 epochs, model.evaluate method was utilized to evaluate the accuracy of our model.
  
  The accuracy of our model can reach 85 percent, which indicate that it works desirably.
