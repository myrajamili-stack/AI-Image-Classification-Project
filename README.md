# AI Image Classification Project

Course: ISB46703 Principle of Artificial Intelligence  
Assessment: Project, 20%

## Project Overview

This project compares three convolutional neural network models for an image classification task:

- ResNet50
- DenseNet121
- MobileNetV3

The models will be trained using transfer learning for 50 epochs each. Their performance will be compared using accuracy, mean average precision, training time, model size/parameters, loss and accuracy curves, and confusion matrices.

## Assessment Requirements

The project must include:

- A dataset from one selected domain:
  - Forestry
  - Medical imaging
  - Agriculture health
  - Animal subspecies
  - Plant subspecies
- At least 3 image classes, up to 10 classes.
- Training, validation, and testing dataset splits.
- Three CNN models trained for 50 epochs each.
- Evaluation using accuracy and mAP.
- Training time recorded for each model.
- Graphs for model loss and accuracy.
- Confusion matrix for each model.
- Final comparison and conclusion.

## Suggested Folder Structure

```text
dataset/
  train/
  validation/
  test/

notebooks/
  01_data_preparation.ipynb
  02_resnet50_training.ipynb
  03_densenet121_training.ipynb
  04_mobilenetv3_training.ipynb
  05_model_comparison.ipynb

results/
  graphs/
  confusion_matrices/

models/
docs/
```

## Team Roles

| Role | Responsibility |
|---|---|
| Data Engineer | Collect images, standardize data, create dataset splits |
| Data Scientist | Build CNN models, train models, tune hyperparameters |
| Data Analyst | Visualize dataset, evaluate models, compare results |

## Model Comparison Table

| Model | Accuracy | mAP | Training Time | Parameters | Notes |
|---|---:|---:|---:|---:|---|
| ResNet50 | TBD | TBD | TBD | TBD | TBD |
| DenseNet121 | TBD | TBD | TBD | TBD | TBD |
| MobileNetV3 | TBD | TBD | TBD | TBD | TBD |

## Final Conclusion

The final conclusion will choose the best model for the classification task by considering:

- Accuracy
- mAP
- Training time
- Number of parameters
- Confusion matrix performance
- Overall suitability for the selected dataset

