# Digit-Classifier
Digit Classifier using MNIST


This is a program for digit classification using MNIST dataset and keras framework using Tensorflow backend. Lets discuss about the files one by one.

Dense Training.ipynb is a ipython notebook file(runs in Jupyter Notebook) where we trained the model using Dense Layers only and attain the accuracy of 98.75% on training set and 98.12% on test set in just 5 minutes of training and 10 epochs. There is also prediction code block in that notebook where we can predict on our own drawing. 

Test.zip is a zip file which is a folder named Test where we have nine test images which we can test on our classifier.

CNN Training.ipynb is also a ipython notebook file where we trained the model using CNN or Constitutional Layer and Dense Layers both and attain the accuracy of 98.95% on training set and 98.49% on test set in just 5 minutes of training and 10 epochs. There is also prediction code block in that notebook where we can predict on our own drawing.

CNN.h5 is the trained model which have the training weights and we can directly import that model in the Prediction.ipynb file and the "img.jpg" file is already setup in that notebook, we can open that jpg file in any drawing tool and draw any digit and 'save as' that file. 

After that we can run the prediction function in that notebook and we get the result.
