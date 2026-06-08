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
MobileNetV2 (Pretrained)

## Loss Functions
- Cross Entropy Loss
- Focal Loss
- Label Smoothing Loss

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

## How to Run
Open the notebook and run all cells.

## Results

Standard Loss Accuracy: 94.87%

Custom Label Smoothing Accuracy: 95.77%

Improvement: +0.89%

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