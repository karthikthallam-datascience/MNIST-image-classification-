# MNIST-image-classification-
Classifying the hand-written single digit Gray-scaled Images using Convolutional Neural Netwrok(CNN)

Used Keras inbuilt Dataset called mnist

Data contains 4-D arrays of 60,000 training images and 10,000 test images

These are Gray scaled hand written single digit images from 0 to 9

Step involved:

1) Load the Data

    a) Tuple unpacking the data into X_train, y_train and X_test, y_test from mnist default Keras dataset
    
2) Visualize a sample image using matplotlib

3) Pre-processing the Data

    a) Convert the labels' values into categorical using OneHotEncoding
    
    b) Normalize both the training and testing images 
    
    c) Reshaping the image size
    
4) Creating a CNN model

5) Evaluation
