# Hybrid Quantum Classical Neural Network for radar data

We want to classify drones based on RADAR signals using convolutional neural networks and using hybrid quantum neural networks. We also create a classical annd hybrid quantum model for binary classification for radar detection. The preprint of this work is available in https://arxiv.org/abs/2403.02080.  

### Data Generation
The dataset of STFT spectrograms of drone signals are generated based on the Martin-Mulgrew model [1] in ``` DataGeneration.ipynb ```. 

## Classifier Models
The Classical convoution neural network (CNN) used to classify drones from radar signals is available in ``` CNN_Classifier.ipynb ```.
The Hybrid Quantum Neural Network (CNN) used to classify drones from radar signals is available in ``` HQNN_Classifier.ipynb ```.

## Detector Models
The Classical convoution neural network (CNN) used to detect drones (binary classification) from radar signals is available in ``` CNN_Classifier.ipynb ```.
The Hybrid Quantum Neural Network (CNN) used to detect drones (binary classification) from radar signals is available in ``` HQNN_Classifier.ipynb ```.

### Referenence 
[1] J. Martin and B. Mulgrew, 'Analysis of the effects of blade pitch on the radar return signal from rotating aircraft blades', in 92 International Conference on Radar, Oct. 1992, pp. 446–449.
