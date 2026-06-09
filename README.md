# MobileNetV2 Loss Function Comparison on CIFAR-10

## Team Members
- Sanskar Dave (AD25B1030)
- Vaibhav Rawat (CS25B1043)
- Mune Harshvardhan Jagdish (AD25B1022)

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
- Output Penalty (Custom Loss Function)

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

The performance of MobileNetV2 was evaluated on the CIFAR-10 test dataset using three different loss functions.

| Metric | Standard Loss | Label Smoothing Loss | Output Penalty Loss |
|----------|----------:|----------:|----------:|
| Accuracy (%) | 90.80 | 92.17 | 91.88 |
| Precision (%) | 91.20 | 92.25 | 91.95 |
| Recall (%) | 90.80 | 92.17 | 91.88 |
| F1 Score (%) | 90.83 | 92.19 | 91.86 |



## Team Contributions

This project was developed collaboratively by all three team members. Each member actively participated in implementation, experimentation and analysis. Each member focused more extensively on specific components of the project.

—- Sanskar Dave – Dataset Preparation and Model Architecture

* Conducted research on image classification techniques and transfer learning.
* Prepared and preprocessed the CIFAR-10 dataset using PyTorch and torchvision transformations.
* Implemented the MobileNetV2 architecture and modified the classifier layer for 10-class classification.
* Assisted in model training, debugging, and evaluation of all experiments.
* Contributed to comparative analysis and interpretation of results.

—- Mune Harshvardhan Jagdish – Loss Function Design and Experimental Setup

* Studied different loss functions and their impact on model performance.
* Implemented the standard Cross Entropy Loss and the custom Label Smoothing Loss.
* Developed the Output Penalty Loss function and integrated it into the training pipeline.
* Participated in hyperparameter tuning, model training, and performance evaluation.
* Collaborated in analyzing the effectiveness of different loss functions and validating experimental outcomes.

—- Vaibhav Rawat – Training Pipeline, Visualization, and Performance Analysis

* Researched optimization techniques, transfer learning strategies, and model evaluation methodologies.
* Designed and implemented the complete training pipeline using the Adam optimizer with loss and accuracy tracking.
* Managed experiment execution and ensured fair comparison by reinitializing the model before each training setup.
* Performed training and validation of multiple experiments across different loss functions.
* Developed visualization modules using Matplotlib to compare training loss and accuracy trends.
* Conducted performance analysis and summarized experimental results to assess the impact of each loss function.
* Contributed to documentation, result interpretation, and preparation of the final project report.

### Overall Contribution

All team members contributed equally throughout the project. Research, coding and result analysis were carried out collaboratively.


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