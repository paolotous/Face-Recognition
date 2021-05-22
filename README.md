# Face-Recognition
Machine Learning Model that recognizes the face by training on a dataset of images.

# What you can do
I would recommend at least 100 images for each person you would like the model to recognize.
You can either upload 100 images if you have an already existing dataset or you can use the FaceRegister.py and Opencv will save 100 screenshots of your face through the default webcam. You could then use that as your dataset.

# Managing the Data
The DatasetManager file will loop through each image, convert it to grayscale, crop the face and show you. If you're happy with the process and would like to include the image in the dataset then press y otherwise pressing any other key will ignore the image and move on to the next one.

# Training the Model
I'm using Scikit-Learn's SVM algorithm, I decided to make a pipeline with PCA as there are too many features. I plotted the graph so you would see the minimum number of components recommended by PCA. The mode is trained afterwards.

# Testing
You can either use some images to test it out or turn on the webcam and check if the model recognizes you. Both versions will be in different branches so feel free to try both.

# Tools used
Language / Environment: Python and Jupyter | 
Libraries: Scikit-Learn, Opencv, Numpy |
Algorithms: SVM and PCA
