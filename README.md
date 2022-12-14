<img src=https://see.fontimg.com/api/renderfont4/KpAp/eyJyIjoiZnMiLCJoIjo1NywidyI6MTAwMCwiZnMiOjU3LCJmZ2MiOiIjN0NDOEY3IiwiYmdjIjoiI0ZGRkZGRiIsInQiOjF9/QXV0b1NvdXJjZUlELVNlZ21lbnRhdGlvbg/kg-second-chances-sketch.png>




# Description
ASID-S is an algorithm for the source segmentation in single band optical images. 
ASID-S uses cutouts of 32x32 pixels of sources localized by AutoSourceID-Light (ASID-L) and predicts their segmentation mask.
A preliminary U-Net network is being tested. 


## Table of Contents 
- [Work in progress](#work_in_progress)


# Work in progress

The hyperparameter space is being explored with the help of the great Weights & Biases software.

Trainining results with three U-net of different sizes:

<img src="https://github.com/FiorenSt/AutoSourceID-Segmentation/blob/main/Plots/Accuracy_segmentation.png" width=50% height=50%> 


Predictions on test set for the best model, Big U-net:

<img src="https://github.com/FiorenSt/AutoSourceID-Segmentation/blob/main/Plots/PreliminaryResults.PNG" width=100% height=100%> 



