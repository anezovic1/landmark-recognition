# Description of the project

The Landmark Recognition System project was undertaken as part of the _Image Processing_ course. The project's objective was to utilize various shape recognition techniques, image processing, and computer vision to create a model that would efficiently identify landmarks from different parts of Egypt.

## Dataset

_Egypt Landmarks_ dataset is a subset of the much larger _Google Dataset V2_. This subset contains 5391 images belonging to a total of 279 different landmarks in Egypt. The size of all images is 244x244 pixels. The images are not evenly distributed among classes, as some classes have up to 200 images, while others have only one image.

The dataset can be found at: https://www.kaggle.com/datasets/aymanmostafa11/eg-landmarks

## Model Description

The selected model is ResNet50, suitable for landmark classification. ResNet50 is a deep neural network architecture belonging to the class of convolutional neural networks (CNN).

After 32 epochs, the accuracy of the model on the test data is **63.71%**. Given the context of the problem and the limitations regarding the dataset, we can consider this accuracy acceptable.
