# Deep-Learning-Project
This code is the python code for the Deep Learning module on automated speech recognition. 

The code does the following:

*   Pulls the data in from github: https://raw.githubusercontent.com/andrsn/data/main/speechImageData.zip
*   Unzips the data (12 classes)
*   Creates Keras training and validation datasets
*   Extracts input-output data from the Keras datasets
*   Neural Network baseline model building
*   Neural Network optimisation:
1. grid search over number of layers and filters per layer
2. training speedup
3. improve generalisation by model generalisation
4. hyperparameter optimisation

The Baseline model speech recognition accuracy reaches 60%

The classifier performance of baseline model across all classes:
<Figure size 1500x480 with 2 Axes>
The classifier performance after model averaging:
<Figure size 1500x480 with 2 Axes>
