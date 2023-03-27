# Facial-Emotion-Expressions
This code is used to build a facial expression classifier using deep learning. The dataset used is a zipped archive containing images of people displaying seven different emotions. The code first defines the parameters such as image width, height, batch size, and number of epochs.

The model architecture consists of several layers including convolutional, dropout, max pooling, and dense layers. The model is compiled using the categorical cross-entropy loss function and the Adam optimizer.

Data preprocessing and augmentation is done using the ImageDataGenerator class from Keras. The data is then split into training and validation sets. The model is trained using the fit() function and the training history is saved for visualization. Finally, the model is saved and a graph is plotted showing the accuracy and loss over time.
