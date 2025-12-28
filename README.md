# Traffic Sign Classification with CNN (GTSRB)

## Project Description
This project implements and compares two Convolutional Neural Network (CNN) architectures for classifying traffic signs using the GTSRB (German Traffic Sign Recognition Benchmark) dataset. The project was developed as part of the **SEN 4107 Introduction to Neural Networks** course.

**Team Members:**
* [Emir Filik]
* [Atıf Erdem Yeter]
* [Elif Yildirim]

## Models
We implemented two models to observe the effects of network depth and regularization:

1.  **Model 1 (Baseline):** A shallow CNN architecture with 2 convolutional layers and basic pooling.
2.  **Model 2 (Improved):** A deeper architecture with increased filter capacity (32/64 filters) and **Dropout (0.25)** layers to prevent overfitting.

## Results
The models were trained for 10 epochs. The comparison results are as follows:

## Results
The models were trained for 10 epochs. The comparison results are as follows:

| Model | Test Accuracy | Final Loss |
|-------|---------------|------------|
| Model 1 (Baseline) | 87.31% | 0.0478 |
| Model 2 (Improved) | **87.46%** | **0.0185** |

*While the accuracy improvement is marginal (+0.15%), Model 2 achieved a significantly lower loss value (0.0185 vs 0.0478), indicating much higher confidence and stability in its predictions compared to the baseline model.*

## Requirements
* Python 3.x
* PyTorch
* Torchvision
* Matplotlib
