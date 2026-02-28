Colorization using CNN

Problem Statement
This project converts grayscale images into color images using a Convolutional

Dataset :
Images converted to LAB color space
L channel used as input
AB channels predicted by the model

Methodology :
Load dataset using OpenCV
Convert images from BGR → LAB
Use L channel as input
Normalize input and output\
Train CNN model with Adam optimizer
Predict AB channels
Convert LAB → RGB

Model Architecture :
Conv2D (64 filters)
Conv2D (128 filters)
Conv2D (64 filters)
Conv2D (2 filters – output)
Loss Function: MSE
Optimizer: Adam

Results :
Training and validation loss decreased over epochs
Model successfully reconstructed basic color information

