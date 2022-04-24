# CNN--Cat-and-Dog-image-detection
Detecting images of cats and dogs

This file implements a CNN to detect images of cats and dogs using a dataset containing 4000 cats images and 4000 dogs images as training and 1000 cats and 1000 dogs images as a test.
After importing packages, image augmentation is done to get a better fit.
Then, a CNN model is created, training is done, and the model is evaluated using test data.
In the end, a prediction of an unseen image is done. The only point here is that the new image must be changed into a 2d array in order to be able to predict.
