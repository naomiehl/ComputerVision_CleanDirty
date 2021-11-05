# ComputerVision_CleanDirty

Understanding if a scene is dirty or clean scenes is crucial for automatic assignment of cleaning trucks in cities. The primary goal of this project is to classify images as dirty or clean, interpret the results (i.e., why the classifier made this decision) and artificially remove the waste from the dirty scenes. The team will need image processing skills and work with 2D ConvNets and interpretability. 

Dataset Clean dirty containers in Montevideo Kaggle link

**Task 1 Clean/dirty classification and analysis**:
Train a classifier with clean/dirty images and evaluate the accuracy
Failure case analysis: 
FP, TP, FN, accuracy
Visualization of all failure cases 

**Task 2 Network interpretation**: 
Localize garbage/waste in dirty image scenes using only image-level information using Class Activation Maps. 
Consider visualizing the activation maps in several convolutional layers 

**Task 3 Clean dirty city images**: 
For this, use Cycle GAN and train it to clean dirty streets (remove the waste from images). You will create one two-fold model: one that removes waste, one that adds it.
You will need two sets of images, one with and one without waste. 
Visualize success and failure cases 
