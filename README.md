# Cat Breed Classification

## Project Members

1. Myra Jasmeen Daniella Binti Bakar Jamili
2. Muhammad Bin Iskandar

## Description

This project is an image classification project for the **Principle of Artificial Intelligence** course. The selected domain is **Animal subspecies**, focusing on cat breed classification using the Oxford-IIIT Pet Dataset.

The project uses Convolutional Neural Network transfer learning to classify five cat breeds:

- Abyssinian
- Bengal
- Birman
- Bombay
- British Shorthair

Three pretrained CNN models are used and compared:

- ResNet50
- DenseNet121
- MobileNetV3Small

The goal is to identify which model performs best based on accuracy, mean average precision, training time, model parameters, loss/accuracy graphs, and confusion matrices.

## Overview

The complete workflow is included in one Google Colab notebook:

[Open Notebook in Colab](https://colab.research.google.com/github/myrajamili-stack/AI-Image-Classification-Project/blob/main/notebooks/00_full_cat_breed_project_colab.ipynb)

The notebook performs the following steps:

1. Downloads the Oxford-IIIT Pet Dataset.
2. Filters the dataset to the selected five cat breeds.
3. Splits the dataset into training, validation, and testing sets.
4. Visualizes the dataset distribution and sample cat images.
5. Trains ResNet50 for 50 epochs.
6. Trains DenseNet121 for 50 epochs.
7. Trains MobileNetV3Small for 50 epochs.
8. Evaluates each model using accuracy and mAP.
9. Displays accuracy/loss graphs and confusion matrices.
10. Compares the three models and generates a final conclusion.

Before running the notebook in Colab, enable GPU:

```text
Runtime > Change runtime type > Hardware accelerator > GPU
```

## Contents

```text
notebooks/
  00_full_cat_breed_project_colab.ipynb

results/
  README.md

README.md
```

### notebooks

Contains the main all-in-one Google Colab notebook for dataset preparation, model training, evaluation, and result visualization.

### results

Stores output files generated after running the notebook, such as:

- model comparison table
- final conclusion text
- accuracy and loss graphs
- confusion matrices
- classification reports

## Model Comparison

| Model | Accuracy | mAP | Training Time | Parameters |
|---|---:|---:|---:|---:|
| ResNet50 | TBD | TBD | TBD | TBD |
| DenseNet121 | TBD | TBD | TBD | TBD |
| MobileNetV3Small | TBD | TBD | TBD | TBD |

The final results will be added after the notebook is run in Google Colab.

