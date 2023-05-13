# Hand-written Recognition

## Description
This is a project that uses machine learning to recognize hand-written digits from images. The project uses the MNIST dataset, which contains 60,000 training images and 10,000 test images of digits from 0 to 9. The project uses a convolutional neural network (CNN) to train and test a model that can classify the images into 10 classes.

The project uses Python and several libraries, such as TensorFlow, Keras, OpenCV, and matplotlib, to perform data preprocessing, model building, training, testing, and visualization. The project consists of the following steps:

- Data preprocessing: loading and reshaping the images into a suitable format for the CNN
- Model building: creating a CNN model with multiple layers, such as convolutional, pooling, dropout, and dense layers
- Model training: compiling and fitting the model on the training data using categorical crossentropy loss and Adam optimizer
- Model testing: evaluating the model on the test data and calculating the accuracy and loss
- Visualization: plotting the accuracy and loss curves for the training and validation data, and displaying some sample predictions

## How to run the project
To run the project, you need to have Python 3 and the required libraries installed on your machine. You can use pip or conda to install the dependencies. You also need to download the MNIST dataset from [this link](http://yann.lecun.com/exdb/mnist/) and unzip it in the same folder as the code files.

To execute the code, you can use any Python IDE or run it from the command line. The main file is `Final_Project.ipynb`, which contains all the functions and logic for the project. You can modify the parameters and variables in the file to change the number of epochs, batch size, learning rate, etc.

The output of the code is saved as a demo video named `Demo_Video.mp4`.

## Contact
If you have any questions or feedback about this project, feel free to contact me at dk3828u@gmail.com. I would love to hear from you! 😊
