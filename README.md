# Hand-Gesture-Detection-EfficientNet-B4
## Dataset 
I use ASL Alphabets Dataset( https://www.kaggle.com/grassknoted/asl-alphabet )

## Composition of Dataset 
29 class(A-Z, 'del', 'space', 'no gesture').
3000 images @class. there are 87000 images in dataset
each class I take 450 images randomly for validation set, then for each class I take 450 images again randomly for testing set, then I leave the rest for training set

## Model
Convolutional Neural Network with Efficient-Net B4 Architecture

## Experiment
I do experiment about the effect of input size variation and Cyclical Learning Rate to model performance.
I train in only 30 epochs
