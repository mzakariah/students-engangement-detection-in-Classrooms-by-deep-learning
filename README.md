# students-engangement-detection-in-Classrooms-by-deep-learning
This model is building a Convolutional Neural Network (CNN) model in Tensorflow using the Keras API to detect student engagement using the FER (Facial Expression Recognition) images dataset. The model consists of multiple layers such as Conv2D (Convolution 2D) layers, MaxPooling2D, Dropout, Flatten, Dense, BatchNormalization, etc. 

The Conv2D layers are used to extract features from the image, MaxPooling2D is used for down-sampling, Dropout is used for regularization, Flatten is used to convert the high dimensional data into a 1D vector, Dense layers are used for the final output prediction, and BatchNormalization is used to normalize the activations of the previous layer. The model is compiled using the Adam optimizer, categorical cross-entropy loss, and accuracy as the metrics. 

The model is trained on the training set for 30 epochs, and the history of the model's accuracy and loss during training and validation is recorded. The training accuracy of the model is 94% and validation accuracy is 92%.
