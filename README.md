# Cotton Disease Prediction




### Problem Statement

Detect if a cotton plant and leaf has disease based on it's image.


### Model

I have used transfer learning technique to complete the task.

1. I have used pretrained VGG-19 model.
2. A Flatten layer was added to and the output is fed to a Dense layer having 4 units for classification and "softmax" activation function.


### Training

The model has been trained for 7 epochs. 

For training the loss started from 1.3 and ended at 0.18. The accuracy started from 61% and ended in 94%.

For validation the loss started from 0.42 and ended at 0.19. The accuracy started from 80% and ended in 93%

##### Accuracy Graph

<img src="https://github.com/mahesh863/cotton-disease-prediction/blob/main/graphs/acc.png" width="500px" >


##### Loss Graph


<img src="https://github.com/mahesh863/cotton-disease-prediction/blob/main/graphs/loss.png" width="500px">




### Results


<img src="https://github.com/mahesh863/cotton-disease-prediction/blob/main/images/diseased.png" width="400px">


<img src="https://github.com/mahesh863/cotton-disease-prediction/blob/main/images/fresh.png" width="400px">

