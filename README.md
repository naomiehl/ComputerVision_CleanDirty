# ComputerVision_CleanDirty

During the first quarantine in 2020 neighbors were worried about the garbage in the Montevideo container. The main objective of this project is to implement an AI that understands if a street is dirty or clean and interpret the results in order to request the automatic maintenance of cleaning trucks in the dirtiest streets. A CNN algorithm is used to classify the dirty and clean streets, and the Grad-Cam algorithm is used in a second step to visualize the waste to better understand which pixels of that image have contributed to the final output  of  the  model. 

You can find the original Montevideo Container Dataset on Kaggle.
![Dataset](DataSet.png)

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
