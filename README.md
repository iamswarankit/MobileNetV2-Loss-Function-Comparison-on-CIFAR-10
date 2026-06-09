# MobileNetV2 Loss Function Comparison on CIFAR-10

## Team Members
- Sanskar Dave
- Vaibhav Rawat
- Mune Harshvardhan Jagdish

## Objective
Compare different loss functions on MobileNetV2 using the CIFAR-10 dataset.

## Dataset
CIFAR-10

## Model
MobileNetV2 
- Efficient CNN Architecture
- Lightweight Deep Learning Model
- Computationally Efficient CNN
- Optimized for Image Classification
- Resource-Efficient Neural Network

## Loss Functions
- Cross Entropy Loss
- Label Smoothing Loss (Custom Loss Function)

## Optimizer
Adam

## Evaluation Metrics
- Accuracy
- Training Loss
- Validation Loss

## Technologies Used
- Python
- PyTorch
- Torchvision
- Matplotlib
- Numpy
- Kaggle

## How to Run
Open the notebook and run all cells.

## Results

Standard Loss Accuracy: 94.87%

Custom Label Smoothing Accuracy: 95.77%

Improvement: +0.89%

## Team Contributions

This project was developed collaboratively by all three team members. Each member actively participated in problem formulation, literature review, implementation, experimentation, debugging, and analysis. While responsibilities overlapped and all decisions were made collectively, each member focused more extensively on specific components of the project.

### Sanskar Dave – Dataset Preparation and Model Architecture

* Conducted research on image classification techniques and transfer learning.
* Prepared and preprocessed the CIFAR-10 dataset using PyTorch and torchvision transformations.
* Implemented the MobileNetV2 architecture and modified the classifier layer for 10-class classification.
* Assisted in training, debugging, and evaluation of all experiments.
* Contributed to the comparative analysis and result interpretation.

### Mune Harhsvardhan Jagdish – Loss Function Design and Experimental Setup

* Studied different loss functions and their impact on model performance.
* Implemented the standard Cross Entropy Loss and the custom Label Smoothing Loss.
* Developed the Output Penalty Loss function and integrated it into the training pipeline.
* Participated in hyperparameter tuning, model training, and performance evaluation.
* Collaborated in analyzing the effectiveness of different loss functions.

### Vaibhav Rawat(Rajput) – Training Pipeline, Visualization, and Performance Analysis

* Researched optimization techniques and training strategies for deep learning models.
* Developed the training framework using the Adam optimizer and implemented accuracy and loss tracking.
* Conducted multiple experiments to ensure fair comparison between loss functions by reinitializing the model.
* Generated graphical visualizations of training loss and accuracy using Matplotlib.
* Prepared the final performance summary and contributed to documentation and interpretation of results.

### Overall Contribution

All team members contributed equally throughout the project. Research, coding, debugging, experiment design, and result analysis were carried out collaboratively. The division above represents the areas where each member devoted additional focus, while maintaining continuous involvement in every stage of the project.

## Conclusion

Custom Label Smoothing Loss achieved a final accuracy of 95.77% compared to 94.87% with Standard Loss.

The experiment shows that label smoothing improves model generalization and reduces overconfidence in predictions.
<br>
CIFAR-10 Dataset<br>
       ↓<br>
Data Preprocessing<br>
       ↓<br>
MobileNetV2<br>
       ↓<br>
Loss Functions<br>
   ├─ Standard Loss<br>
   └─ Label Smoothing Loss<br>
       ↓<br>
Training<br>
       ↓<br>
Accuracy Comparison<br>