# Fair Apparent Age Estimation
Using Convolutional Neural Network to create apparent age estimation model. 
Experiment with a number of methods to research their impact on the training 
process and different kid of biases.

## `ApparentAgeEstimation.pdf`
The final report with the summary of contribution and the results discussion. 

## `base_model.ipynb`
Load the dataset, and the ResNet50 model. Use transfer learning to adjust the 
model for the given task and perform fine-tuning. 

## `bias_simple.ipynb`
Investigate the dataset with respect to the underlying biases. Implement simple
methods like data augmentation and weighted samples to improve the training. 

## `bias_custom.ipynb`
Experiment with complex custom solutions for reducing biases, 
like complex weights or custom loss functions.
